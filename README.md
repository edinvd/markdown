<div align = "center">
    <h1><strong>Markdown</font></strong></h1>
</div>

<div align = "center">
    <img src="https://upload.wikimedia.org/wikipedia/commons/4/48/Markdown-mark.svg"  width="100px" alt="Markdown logo">
</div>

Lenguaje de marcado ligero para crear formatos sofisticados con sintaxis simple.
 
## Encabezados
Para crear un encabezado, agrega uno a seis símbolos `#` antes del encabezado del texto. La cantidad de `#` que usas determinará el tamaño del ecanbezado.

```markdown
# El encabezado más largo
## El segundo encabezado 
### El tercer encabezado
#### El cuarto encabezado
##### El quinto encabezado 
###### El encabezado más pequeño
```

# El encabezado más largo
## El segundo encabezado 
### El tercer encabezado
#### El cuarto encabezado
##### El quinto encabezado 
###### El encabezado más pequeño


## Estilo de texto
Puedes indicar énfasis con texto en negrita, cursiva o tachado.

| Estilo | Sintaxis | Atajo del teclado | Ejemplo | Resultado
|--|--|--|--|--|
| Negrita | `** ** o __ __` | command/control + b |` **Este texto está en negrita** ` | __Este texto está en negrita__ |
| Cursiva | `* * o _ _` | command/control + i | `*Este texto está en cursiva*` | _Este texto está en cursiva_ |
| Tachado | `~~ ~~` | | `~~Este texto está equivocado~~` | ~~Este texto está equivocado~~|
| Cursiva en negrita y anidada | `** ** y _ _` | | `**Este texto es _extremadamente_ importante**` | **Este texto es** _extremadamente_ **importante** |
| Todo en negrita y cursiva	| `*** ***` | | `***Todo este texto es importante***` | ***Todo este texto es importante***|


## Cita de texto
Puedes citar texto con un `>`.

```markdown
Make humanity a multiplanet species!
> Elon Musk
```

Make humanity a multiplanet species!

> Elon Musk


## Código de cita
Puedes indicar un código o un comando dentro de un enunciado con comillas simples. El texto dentro de las comillas simples no será formateado.

```
Usa `git status` para enumerar todos los archivos nuevos o modificados que aún no han sido confirmados.
```

Usa `git status` para enumerar todos los archivos nuevos o modificados que aún no han sido confirmados.

Para formatear código o texto en su propio bloque distintivo, usa comillas triples.

```
Algunos de los comandos de Git básicos son:

```->
git status
git add
git commit
```<-
```

Algunos de los comandos de Git básicos son:

```
git status
git add
git commit
```
