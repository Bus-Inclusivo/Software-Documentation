# Coding Conventions

## 1. General
Para nombres u otros elementos correspondientes a código (no texto que se mostrará al usuario) se debe aplicar la nomenclatura en inglés.  
Para html y css, los nombres de elementos, atributos, selectores CSS, propiedades y valores de las propiedades deben estar en minúsculas, a exepción de los strings.  
| Tipo | Ejemplos |
| -- | -- |
| Elemento | `<p>`, `<div>`, `<table>` |
| Atributo | class, id, href |
| Selector CSS | p, h1, body |
| Propiedades | color, width, text-align |
| Valores de las propiedades | #e5e5e5, 320px, center |  

La sangría a utilizar será solo de dos espacios con la tecla espaciadora.
Asímismo, un documento html debe contar con las declaraciones `<!doctype html>` al comienzo del documento, y `<meta charset="utf-8" />`, dentro del elemento `<head>`.

Para JavaScript, los nombres de variables y funciones deben estar en minúsculas y las palabras separadas por guion bajo.

| Ejemplo | Valor |
| -- | -- |
| Varibales | variable_name |
| Funciones | function_name |  

Además, en un documento html solo se tendrá la estructura así como contenido general(textos, imagenes, tablas, etc), en un archivo CSS se tendrá el aspecto del documento html(colores, fuentes, tamaños de fuentes, etc) y en un archivo JavaScript se tendrá las funciones para las acciones one click o de algún otro tipo. 

## 2. Elementos
Para html, los elementos vacíos asi como los no vacíos deben ser cerrados.
| Tipo | Ejemplo |
| -- | -- |
| Vacío | `<br />` |
| No vacío | `<p></p>` |

## 3. Elementos Indispensables
Un documento html debe contar con los siguientes elementos.
| Elemento |
|---|
| `<html>` |
| `<body>` |
| `<head>` |
| `<title>` |
| `<meta>` |

## 4. Atributos y valores
Los valores de los atributos de un elemento html deben estar entre comillas, en mínusculas y las palabras se separarán por guiones. Además, no debe existir algún espacion antes o después del `=`

| Ejemplo |  |
| -- | -- |
| class | `<p class="example-class"></p>` |
| id | `<div id="example"></div>` |

## 5. Atributos Obligatorios
Los siguientes elementos html siempre deben tener especificados algunos atributos.
| Elemento | Atributos |
| -- | -- |
| `<html>` | lang |
| `<img>` | alt, width, height  |
| `<link>` | rel |

## 6. Enlaces externos
Para html, los enlaces externos que puedan ser valor de algún atributo, sea  `scr` o `href`, deben contar con el protocolo `https` cuando sea posible.
| Ejemplo | Valor |
| -- | -- |
| `src` | `https://ajax.googleapis.com/ajax/libs/jquery/3.4.0/jquery.min.js` |

## 7. Extensiones de archivos
Las extensiones de archivos que se usará deben ser la estandar para cada tipo.
| Archivo | Extensión |
| -- | -- |
| html | .html |
| CSS | .css |
| JavaScript | .js |

