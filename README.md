<h1 align="center">DapFlix</h1>

## 💻 Descripción del proyecto

Este proyecto se basa en usar el **Modelo Vista Controlador** para poder crear un sistema de visualización de información sobre cines y plataformas de Streaming. Este sistema es de gran utilidad para poder tener una visión completa del mundo cinematográfico tanto dentro como fuera de España. 
Además se ha hecho uso de otros patrones como **Factory Method** y **Singleton** para apoyar el desarrollo del mismo. 

## 👨‍💻 Miembros del equipo

- Javier González de la Barreda Arimany - alu0101349077@ull.edu.es

- Daniel del Rosario Pimienta - alu0101315577@ull.edu.es

- María Ferrándiz Díaz - alu0101475899@ull.edu.es

## 📈 Descripción general del proyecto

El sistema desarrollado, DAPFlix, permite gestionar información de plataformas de streaming y carteleras de cines en tiempo real, implementando patrones de diseño como Singleton, Factory Method y MVC. Entre sus funcionalidades principales se incluyen la obtención de películas desde plataformas como Netflix, Disney+ y Max utilizando la API de TMDB, y el scraping de información de cines locales como Yelmo Cines y Multicines Tenerife. Además, el sistema proporciona visualización de datos mediante gráficas personalizadas, adaptadas tanto a los cines como a las plataformas de streaming. Estas gráficas incluyen barras para mostrar la cantidad de películas disponibles por plataforma, un ranking de éxito de películas actualizadas en tiempo real y gráfico de sectores para analizar el impacto del cine español. 

## 💡 Características

- Interfaz gráfica para visualizar datos de cines
- Interfaz gráfica para visualizar datos de plataformas de streaming
- Patrón MVC
- Patrón Singleton
- Patrón Factory Method

## ⚙️ Instrucciones para la ejecución

### Añadir las librerías

Las librerías utilizadas para el proyecto son:

- Selenium - WebScraping de la cartelera Yelmo
- Gson - Consumo de JSON para la api TMDB

Ambas se encuentran disponibles en la carpeta de recursos y deben ser importadas al ide local en el que se utilice. En caso de hacer uso de IntelliJ, se deberá incluir en el apartado *"File > Project Structure... > Libraries"*.

El uso de la librería Selenium implica la necesidad de utilizar drivers de navegador, por ello hemos utilizado Chrome como referencia. Para utilizarlo se deberá localizar el driver en la carpeta resources para la arquitectura de tu dispositivo y situar la ruta en la *src/Data/WebScraping/MoviesDataApi.java* y modificar el valor de **final String driver** a la ruta específica que haya tenido en la descarga. 

- chromedriver-mac-arm64
- chromedriver-mac-x86
- chromedriver-win64
- chromeDriver-linux64

Enlace a los drivers [ChromeDriver](https://github.com/dreamshao/chromedriver/tree/main)

### Cambios en el código

Una vez incluidas las librerías en la estructura del proyecto y tras cambiar la ruta específica para el driver, se ejecutará con normalidad el código que se encuentra en **Server.java** y posteriormente, se ejecutará el html que contiene toda la parte visual para el usuario, este fichero se encuentra en *DapflixWeb/index.html*, tras esto se abrirá una página en chrome con toda la aplicación funcional. 

## 🌐 Referencias
1. [Presentación](https://drive.google.com/file/d/1-4N7aGEkwoohbXQrvM1uBypJXpaYpIig/view?usp=drive_link)

2. [Taquilla España](https://www.taquillaespana.es/})

3. [The Movie DataBase](https://developers.themoviedb.org/3)

4. [Selenium](https://www.selenium.dev/documentation/)
