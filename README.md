<h1 align="center">DapFlix</h1>

## 💻 Descripción del proyecto

Este proyecto se basa en usar el **Modelo Vista Controlador** para poder crear un sistema de visualización de información sobre cines y plataformas de Streaming. Este sistema es de gran utilidad para poder tener una visión completa del mundo cinematográfico tanto dentro como fuera de España. 
Además se ha hecho uso de otros patrones como **Factory Method** y **Singleton** para apoyar el desarrollo del mismo. 

## 👨‍💻 Miembros del equipo

- Javier González de la Barreda Arimany - alu0101349077@ull.edu.es

- Daniel del Rosario Pimienta - alu0101315577@ull.edu.es

- María Ferrándiz Díaz - alu0101475899@ull.edu.es

## 📈 Desarrollo del proyecto

Cambiar

## 💡 Características

- Interfaz gráfica para una experiencia interactiva de suscripción con las ofertas de las plataformas.
- Interfaz gráfica para visualizar a modo de suscripción películas de cartelera.
- Patrón Observador: Las plataformas notifican de si hay actualización.

## Ejecución

### Librerías

Las librerías utilizadas para el proyecto son:

- Selenium - WebScraping de la cartelera Yelmo
- Gson - Consumo de JSON para la api TMDB

Ambas se encuentran disponibles en la carpeta de recursos y deben ser importadas al ide local en el que se utilice.

El uso de la librería Selenium implica la necesidad de utilizar drivers de navegador, por ello hemos utilizado Chrome como referencia. Para utilizarlo deberás localizar el driver en la carpeta resources para la arquitectura de tu dispositivo y situar la ruta en la clase YelmoCines - DriverPath.

- chromedriver-mac-arm64
- chromedriver-mac-x86
- chromedriver-win64
- chromeDriver-linux64

Enlace a los drivers [ChromeDriver](https://github.com/dreamshao/chromedriver/tree/main)

## 🌐 Referencias
[Presentación](https://drive.google.com/file/d/1-4N7aGEkwoohbXQrvM1uBypJXpaYpIig/view?usp=drive_link)

[Taquilla España](https://www.taquillaespana.es/})

[The Movie DataBase](https://developers.themoviedb.org/3)

[Selenium](https://www.selenium.dev/documentation/)
