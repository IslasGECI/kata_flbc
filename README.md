# Examen de selección

## Introducción a la kata

Por favor lee la siguiente nota:
- [Códigos de cuatro letras para las aves](https://islasgeci.github.io/2020/08/06/kata)

## Instrucciones

Debes crear una aplicación de cualquier tipo que reciba el nombre común de un ave y devuelva el
código de cuatro letras correspondiente.

1. Crea un _fork_ del repositorio `https://github.com/IslasGECI/kata_flbc_<TU NOMBRE>`
1. Haz pasar GitHub Actions (necesitarás agregar un `Makefile`)
1. Cubre tu código con pruebas
1. Haz _pull request_
1. Usa GitHub (_issues_, _pull requests_ y _team discussions_) como el único medio de comunicación

## Ejecución de la aplicación

Para revisar la versión final de la aplicación, ejecutaremos lo siguiente:

```
git clone https://github.com/IslasGECI/kata_flbc_${TU_NOMBRE}.git
cd kata_flbc_${TU_NOMBRE}
docker build --tag islasgeci .
docker run islasgeci make run
```

## Rúbrica

Evaluaremos los siguientes rubros:

- **Capacidad para el trabajo remoto y colaborativo**: Uso de Git; habilidades de comunicación
  mediante GitHub (_issues_, _pull requests_ y _team discussions_); solicitud de revisiones;
  asimilación de retroalimentación
- **Buenas prácticas en programación**: Refactorización; principios de diseño de software; pruebas
  unitarias
- **Automatización y reproducibilidad**: Uso de GitHub Actions, Docker y Make; principios ágiles y
  de DevOps

## Sugerencias

- Crea _pull request_ pequeños; un _pull request_ de 100 líneas podría ser demasiado grande.
- Se amable, explica el porqué de las cosas, respeta nuestro [código de
  conducta](https://islasgeci.github.io/2019/11/06/code-of-conduct), usa lenguaje simple y claro.
- Comunícate mucho y hazlo mediante GitHub.
