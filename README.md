# Proyecto Audio Player

Aplicación Java que modela un reproductor de audio con canciones y podcasts, utilizando principios de programación orientada a objetos.  Este proyecto demuestra la creación y gestión de objetos, herencia y encapsulación.

## Funcionalidades

* **Conteo de "Me gusta":**  Registra la cantidad de "me gusta" para cada elemento de audio (canciones y podcasts).  Este contador se incrementa cada vez que se llama al método `me gusta`.
* **Registro de reproducciones:**  Lleva un conteo preciso de las reproducciones de cada elemento de audio.  Similar al contador de "me gusta", se incrementa con cada llamada al método `reproduce`.
* **Gestión de información de canciones:**  Permite almacenar y gestionar información detallada de las canciones, incluyendo:
    * Título
    * Álbum
    * Artista
    * Género
* **Gestión de información de podcasts:**  Permite almacenar y gestionar información detallada de los podcasts, incluyendo:
    * Título
    * Presentador
    * Descripción
* **Herencia:**  Utiliza la herencia para modelar la relación entre la clase base `Audio` y las clases derivadas `Canción` y `Podcast`, promoviendo la reutilización de código y una estructura limpia.


## Arquitectura

El proyecto se basa en una arquitectura orientada a objetos, con las siguientes clases principales:

* `Audio`: Clase base que define atributos y métodos comunes a canciones y podcasts.
* `Canción`: Clase derivada de `Audio`, que extiende su funcionalidad con atributos específicos de las canciones.
* `Podcast`: Clase derivada de `Audio`, que extiende su funcionalidad con atributos específicos de los podcasts.


## Uso

Para ejecutar este proyecto, asegúrate de tener instalado un JDK (Java Development Kit) compatible.  Luego, puedes compilar el código fuente utilizando un compilador Java (como el que viene con el JDK) y ejecutar la clase principal.


## Contribuciones

Las contribuciones son bienvenidas y se agradecen.  Si deseas contribuir, por favor, sigue estos pasos:

1. Crea un *fork* del repositorio.
2. Crea una rama para tu nueva funcionalidad o corrección de errores.
3. Realiza los cambios necesarios.
4. Realiza pruebas exhaustivas para asegurar la calidad del código.
5. Envía una *pull request* describiendo claramente los cambios realizados.


## Licencia

MIT License

Copyright (c) 2024 Cristian Cortés B.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.


## Autor

Cristian Cortés