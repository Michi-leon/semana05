# Aprendiendo Markdown
El dia de hoy vamos a *aprender* a usar el Markdown aqui en TECSUP.

## Subtitulo 01
Esto es un simple subtitulo en el cual coloco un **texto**.

### Subtitulo 02
Aprendiendo a crear subtitutlos en ~~Markdown en TECSUP con los chicos de teoria.~~

## Instalación
1. Creamos la carpeta
2. Iniciamos Git Hub
3. Ubicamos los archivos.

## Vinculos
[Visita TECSUP](https://www.tecsup.edu.pe)

## para codigos
```html
    <h1>Esto es un codigo</h1>
```

```css
    body{
        background: darkblue;
    }
```

```java
    public class Main{
        public static void main(string[] args){
            System.out.print("Aprendiendo hoy");
        }
    }
```

## Colocando Imagenes
![Pantalla Principal](img01.avif)

## Diseño de Botones
![Java](https://img.shields.io/badge/Java-17-blue)

![Java](https://img.shields.io/badge/Java-1.0-red)

## Funciones
- [x] Registro de Alumno
- [x] Matricula Procesada
- [ ] Reporte Generado

## Creando tablas
| Lenguajes de Programación | Creador |
|---------------------------|---------|
| Java | James Gosling |
| PHP  | Rasmus Lerdorf |

| Programas | Año de Creación |
|---------------------------|---------|
| Visual Studio CODE | 2004 |
| Virtual BOX  | 2006 |

## Aprendiendo mermaid
` ` `mermaid
flowchart TD
A[Usuario] --> B[Iniciar Sesión]
B --> C(Colocar Credenciales)
C --> |Si| D[Acceder al Sistema]
C --> |No| E[No ingresa]