# Introducción a Go

Apuntes ejecutables de los fundamentos de **Go**: un menú de consola donde cada opción corre el ejemplo de un tema.

## Temas

| Bloque | Temas |
|---|---|
| Variables, funciones y documentación | Declaración de variables, operadores aritméticos, tipos primitivos, paquete `fmt`, funciones |
| Control de flujo | Ciclos, `if`, `switch` y palabras clave (`defer`, `break`, `continue`) |
| Estructuras de datos | Arrays y slices, recorrido con `range`, maps, structs y modificadores de acceso |
| Métodos e interfaces | Structs y punteros, Stringers, interfaces y listas de interfaces |
| Concurrencia | Goroutines, channels, y `range`, `close` y `select` sobre channels |

El menú y los ejemplos están en [`src/main.go`](src/main.go); el paquete [`src/pkstructs`](src/pkstructs) se usa para mostrar structs exportados y privados.

## Cómo ejecutar

Requiere Go 1.23 o superior.

```bash
go run ./src
```

Se muestra el menú; escribe el número de la opción y pulsa Enter. La opción 21 termina el programa.
