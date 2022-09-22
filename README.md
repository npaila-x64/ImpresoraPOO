## Evidencia05: Caso del automóvil y la POO

i. Identifique las principales características de los objetos identificados.

| Nombre    |
|-----------|
| Impresora |

| Características        | Funcionalidades    |
|------------------------|--------------------|
| Marca                  | Imprimir           |
| Modelo                 | Fotocopiar         |
| Color                  | Escanear           |
| Tamaño                 | Cargar Papel       |
| Peso                   | Cargar Tinta Negra |
| Velocidad de Impresión | Encender           |
| Carga de Papel         | Apagar             |
| Carga de Tinta Negra   | Quedar Obsoleta    |
| Vida Útil              |                    |

ii. A partir de los objetos identificados, diseñe una clase que los represente a todos.

| Clase     |
|-----------|
| Impresora |

| Atributos            | Métodos                       |
|----------------------|-------------------------------|
| marca                | imprimir()                    |
| modelo               | fotocopiar()                  |
| color                | escanear()                    |
| velocidadDeImpresión | cargarPapel()                 |
| cargaDePapel         | cargarTintaNegra()            |
| cargaDeTintaNegra    | encender()                    |
| estaEncendida        | apagar()                      |
| vidaUtil             | quedarObsoleta()              |
| estaObsoleta         | obtenerVelocidadDeImpresion() |

* Si la impresora queda obsoleta no se puede volver a  encender
* La vida útil es la cantidad total de papel que puede imprimir la impresora

iii. Construya una 1ra aprox. en código fuente de Java para la clase diseñada.