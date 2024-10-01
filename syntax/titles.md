# Encabezados

Lo primero que necesitamos al escribir un texto en markdown son un título y algunos sub-headers.

Markdown permite dos estilos de "headers", Setext y atx.

Los encabezados con estilo Setext están “subrayados” usando signos de igual (para los encabezados de primer nivel o títulos) y guiones bajos (para los ecabezados de segundo nivel). Ejemplo:


```markdown
This is an H1
=============

This is an H2
-------------
```

Cualquier número de =’s o -’s funciona.

el estilo Atx usa de 1-6 caracteres de gato (o número) al inicio de cada línea, los cuales corresponden a los niveles del uno al seis. Por ejemplo:

```markdown
# Este es un H1

## Este es un H2

###### Este es un H6
```

De manera opcional, puedes “cerrar” los encabezados atx. Esto es meramente cosmético — puedes usarlo si crees que se ve mejor. Los "gatos" al final no tienen que coincidir con los que están al inciio. (El número de gatos que abre es el que determina el nivel del encabezado.) :

```markdown
# Este es un H1 #

## Este es un H2 ##

### Este es un H3 ######
```
