# Ligas

En Markdown puedes añadir dos tipos de ligas: dentro del párrafo y referencias.

En ambos estilos, la liga está delimitada por [corchetes cuadrados].

1Para crear una liga en el párrafo:
1. Dentro de los corchetes cuadrados, escribe el texto que ligará a un sitio web o URL.
2. Inmediatamente después, escribe un par de paréntesis regulares.
3. Dentro de los paréntesis, pega el URL al cual quieres que paunte la liga.
4. Opcional: añade título opcional para la liga entre comillas.

Ejemplos:

```markdown
[I'm an inline-style link](https://www.google.com)

[I'm an inline-style link with title](https://www.google.com "Google's Homepage")

[I'm a reference-style link][arbitrary case-insensitive reference text]

[I'm a relative reference to a repository file](../blob/master/LICENSE)
```

Las ligas de referencia usan un segundo par de corchetes cuadrados. Dentro de ellos se coloca una etiqueta de tu elección para identificar la liga.
```markdown
This is [an example][id] reference-style link.
```

Puedes usar un espacio para separar ambos pares de corchetes cuadrados:

```markdown
This is [an example] [id] reference-style link.
```

Luego, en cualquier parte del documento (de preferencia al final), define la estiqueta de tu referencia de la siguiente manera:

```markdown
[id]: http://example.com/ "Optional Title Here"
```
Debe abarcar una sola línea por etiqueta.

**GitHub** y **GitBook** pueden autogenerar ligas para URLs estándar. 

https://www.google.com 
