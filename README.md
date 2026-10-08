Nombre: Jelika Duanny Lezama Rodriguez
Curso: Lenguaje de Programacion II
Proyecto: T2_Lezama_Rodriguez

Descripcion
Repositorio Git local creado para controlar las versiones de un proyecto Java/Maven. Contiene la linea base del proyecto, un archivo .gitignore con las exclusiones propias de Eclipse y Maven, y el historial de cambios que permite verificar su trazabilidad.
## Evidencia T2
Evaluación T2 de Lenguaje de Programación II, Pregunta 01: preparación, configuración y línea base de un repositorio Git.
sed -i 's|</project>|  <description>Proyecto Maven de la evaluacion T2 de Lenguaje de Programacion II desarrollado por Jelika Lezama</description>\n</project>|' pom.xml
cat pom.xml
cat >> README.md << 'EOF'

## Control de cambios
En esta actividad se practicó el control de cambios con Git: se modificaron README.md y pom.xml, se creó el archivo observaciones.txt y se gestionaron los cambios entre el Working Directory, el Staging Area y el repositorio local.

## Gestión de ramas
Rama utilizada: feature-lezama.
Cambio: se creo la clase ControlVersion_Lezama.java en src/main/java, que muestra un mensaje de identificacion del estudiante. Esta funcionalidad se desarrolló de forma independiente en la rama feature-lezama para luego unirla con la rama principal.
