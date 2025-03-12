
# **Paso a Paso para Realizar la Release v1.0**

### **1. Hice un Fork del Proyecto**
1. Fui a la URL del proyecto: [https://github.com/damiancastelao/ExamenCOD](https://github.com/damiancastelao/ExamenCOD).
2. Clicando en **Fork** en la esquina superior derecha para crear la copia del repositorio en mi cuenta de GitHub.

---

### **2. Cloné el Repositorio en mi local**

1. Abrí IntelliJ IDEA.
2. Seleccioné en la pestaña **Git** la opcion **Clone**.
3. Pegué la URL de mi repositorio (`https://github.com/SGRuzo/ExamenCOD.git`).

---

### **3. Creé la rama readme y añadí el archivo README.md**

1. En la parte inferior derecha haciendo clic en la rama main
2. Seleccionando **New Branch** y llamndo readme a la nueva rama.
3. Dentro de esta nueva rama creé un archivo README.md.
4. Añade contenido al README.md explicando los pasos que vas realizando, los comandos y las decisiones tomadas.

---

### **4. Creé un commit**

1. Cree un commit en la rama Readme seleccionando el archivo de readme.md y lo llamé "Creacion Rama Readme y archivo readme."

---

### **5. Creé un Tag y generé un Release**

1. En Git>New Tag y lo llamé v1.0
2. A continuación hice un push.
3. En GitHub cliqué en Release, seleccioné el tag v1.0
4. Cliqué en Publish release.

### **6. Fusion de ramas**

1. Eliminé el último commit de interface con el comando `git reset --hard HEAD~1`
2. Descubrí que a saber como me desapareció la rama datos...
3. Selecioné Git>Merge desde la rama main y escogí interface y la opción squash.
