<div style="text-align: center;">

![Imagen](icon.png)

# Tutorial Completo de Markdown

</div>

<details>
    <summary>Índice</summary>

- [Tutorial Completo de Markdown](#tutorial-completo-de-markdown)
  - [Encabezados](#encabezados)
  - [Estilos](#estilos)
  - [Listas](#listas)

</details>

## Encabezados

Los headers en Markdown son una forma de crear títulos y subtítulos en un documento. Se utilizan para estructurar el contenido y hacerlo más legible.

En Markdown, los headers se crean utilizando símbolos de numeral (#) seguidos del texto del título. El número de símbolos de numeral indica el nivel de título.

```Markdown
# Encabezado 1
## Encabezado 2
### Encabezado 3
#### Encabezado 4
##### Encabezado 5
###### Encabezado 6
```

> # Header 1
>
> ## Header 2
>
> ### Header 3

## Estilos

En Markdown, los estilos se refieren a la forma en que se presentan los elementos de texto. Para aplicar estilos a los elementos de texto, Markdown utiliza una sintaxis simple y fácil de leer

```Markdown
Itálicas se usan con *astericos* o _barras_
Negritas se usan con doble **astericos** o __barras__
Puedes tachar el texto con ~~doble tilde~~
Puedes resaltar el texto con ==doble signos igual==
Puedes combinar **~~Varios estilos a tu antojo~~**
```

>Itálicas se usan con *astericos* o _barras_  
>Negritas se usan con doble **astericos** o __barras__  
>Puedes tachar el texto con ~~doble tilde~~  
>Puedes resaltar el texto con ==doble signos igual==[^1]  
>Puedes combinar **~~Varios estilos a tu antojo~~**

## Listas

En Markdown, las listas son una forma sencilla de presentar información en una forma clara y organizada. Hay dos tipos de listas: listas ordenadas y listas desordenadas.

Las listas desordenadas se crean utilizando asteriscos (*), guiones (-) o signos de suma (+) seguidos de un espacio y el texto de la lista

```Markdown
* Item 1
* Item 2
* Item 3
```

>- Item 1
>- Item 2
>- Item 3

Las listas ordenadas se crean utilizando números seguidos de un punto (.) y un espacio, y luego el texto de la lista

```Markdown
1. Item 1
2. Item 2
3. Item 3
```

>1. Item 1
>2. Item 2
>3. Item 3

Puedes combinar ambos tipos de listas y realizar sublistas como en el siguiente ejemplo

```Markdown
1. Item 1
    * Subitem 1
    * Subitem 2
2. Item 2
    - Subitem 3
    - Subitem 4
3. Item 3
    1. Subsubitem 1
    2. Subsubitem 2
        * Subsubsubitem 1
        * Subsubsubitem 2
```

1. Item 1
    - Subitem 1
    - Subitem 2
2. Item 2
    - Subitem 3
    - Subitem 4
3. Item 3
    1. Subsubitem 1
    2. Subsubitem 2
        - Subsubsubitem 1
        - Subsubsubitem 2

[^1]: No todos los renders de Markdown aceptan resaltado de texto  
