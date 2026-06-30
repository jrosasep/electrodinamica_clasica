# Electrodinámica 2

Apunte personal de **Electrodinámica 2**, elaborado a partir de notas tomadas en clases y reorganizado en formato LaTeX tipo `book`.

El objetivo del repositorio es reunir y ordenar el material del curso en una estructura editable por capítulos, manteniendo el énfasis en la formulación físico-matemática de la electrodinámica clásica.

## Estado del proyecto

Apunte en desarrollo. El contenido puede cambiar a medida que se incorporen nuevas secciones, correcciones, ejemplos y comentarios.

## Contenido actual

- estructura local de la electrodinámica clásica;
- conservación local de la carga;
- ecuaciones de Maxwell en el vacío;
- ecuaciones de onda electromagnéticas;
- ondas planas, polarización y superposición espectral;
- potenciales electromagnéticos y gauge;
- potenciales retardados;
- energía y momentum del campo electromagnético;
- formulación tensorial y covariante;
- apéndices breves de apoyo conceptual y matemático.

## Estructura del repositorio

```text
main.tex
preamble.tex
frontmatter.tex
logo-udec.png
main.pdf
README.md
electrodinamica2_monolitico_original.tex
chapters/
  00_introduccion.tex
  01_estructura_local_de_la_electrodinamica_clasica.tex
  02_ecuaciones_de_onda_electromagneticas_en_el_vacio.tex
  03_potenciales_electromagneticos_y_gauge.tex
  04_potenciales_retardados_y_fuentes_en_movimiento.tex
  05_electrodinamica_en_medios_materiales.tex
  06_energia_momentum_y_formulacion_tensorial.tex
  07_relatividad_especial_y_formulacion_covariante.tex
  ap_a_nota_breve_sobre_la_palabra_gauge.tex
  ap_b_conexion_util_con_el_apunte_de_optica_ondulatoria.tex
  ap_c_comentario_matematico_sobre_l_2_ortogonalidad_y_fourier.tex
```

El archivo principal del libro es:

```text
main.tex
```

Los archivos dentro de `chapters/` pueden editarse de forma individual y también compilarse por separado gracias al paquete `subfiles`.

## Compilación

Para compilar el libro completo:

```bash
latexmk -pdf main.tex
```

También puede compilarse con `pdflatex`:

```bash
pdflatex main.tex
pdflatex main.tex
```

En **Overleaf**, el documento principal debe ser `main.tex`. Si Overleaf intenta compilar `preamble.tex`, se producirá un error porque `preamble.tex` contiene únicamente paquetes, comandos y configuración del documento.

## Asistencia

Este material fue reorganizado y editado con apoyo de IA para tareas de LaTeX, estructuración del documento, revisión local de redacción y ordenamiento de archivos. El contenido final fue revisado y editado por el autor; la responsabilidad por el texto, omisiones y posibles errores remanentes corresponde al autor.

## Autor

**José Rosas**  
Licenciatura en Ciencias Físicas  
Universidad de Concepción
