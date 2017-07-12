# Platzom

Es un lenguaje inventado para el curso de fundamentos de JavaScript de [Platzi] (https:www.google.com)

##Descripcion del Idioma

- Si la palabra termina con "ar", se le quitan esas dos letras
- Si la palabra inicia con Z, se le añade "pe" al final
- Si la palabra traducida tiene 10 o más letras, se debe partir en dos por la mitad y unir con un guión medio
- Por último, si la palabra original es un palíndromo, ninguna regla anterior cuenta y se devuelve la misma palabra pero intercalando letras mayúsculas y minúsculas

## Instalacion

```
npm install platzom

```

##Uso

```
      import platzom for 'platzom'

      platzom("programar") //
      platzom("Programar") // Program
      platzom("Zorro") // Zorrope
      platzom("Zarpar") // Zarppe
      platzom("abecedario") // abece-dario
      platzom("sometemos") // SoMeTeMoS
```

##Creditos

- [Ignacio Briones] (https://www.linkedin.com/in/ignaciobrioness)

## Licencia

[MIT](https://opensource.org/licenses/MIT)
