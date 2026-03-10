<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a id="readme-top"></a>

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/psychedelic-art/alura-store-latam">
    <img src="https://img.shields.io/badge/Alura%20Store%20Latam-Data%20Analysis-6f42c1?style=for-the-badge" alt="Alura Store Latam">
  </a>

  <h3 align="center">Alura Store Latam — Análisis Comparativo de Tiendas</h3>

  <p align="center">
    Proyecto de análisis de datos para comparar el desempeño de cuatro tiendas y recomendar cuál debería vender el Sr. Juan.
    <br />
    <a href="https://github.com/psychedelic-art/alura-store-latam"><strong>Explorar documentación »</strong></a>
    <br />
    <br />
    <a href="https://github.com/psychedelic-art/alura-store-latam">Ver repositorio</a>
    &middot;
    <a href="https://github.com/psychedelic-art/alura-store-latam/issues">Reportar problema</a>
    &middot;
    <a href="https://github.com/psychedelic-art/alura-store-latam/issues">Sugerir mejora</a>
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Tabla de contenido</summary>
  <ol>
    <li>
      <a href="#about-the-project">Acerca del proyecto</a>
      <ul>
        <li><a href="#built-with">Tecnologías utilizadas</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Primeros pasos</a>
      <ul>
        <li><a href="#prerequisites">Prerrequisitos</a></li>
        <li><a href="#installation">Instalación</a></li>
      </ul>
    </li>
    <li><a href="#usage">Uso</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contribuciones</a></li>
    <li><a href="#license">Licencia</a></li>
    <li><a href="#contact">Contacto</a></li>
    <li><a href="#acknowledgments">Agradecimientos</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## About The Project

Este proyecto desarrolla un análisis comparativo de las cuatro tiendas del Sr. Juan a partir de datos de ventas, satisfacción del cliente y costos logísticos. El objetivo principal es identificar, con base en evidencia cuantitativa, cuál tienda presenta el desempeño menos competitivo y, por lo tanto, sería la mejor candidata para ser vendida.

El análisis fue realizado en Google Colab utilizando Python, Pandas y Matplotlib, y se organiza en cinco bloques principales:

* **Análisis de facturación**
* **Ventas por categoría**
* **Calificación promedio por tienda**
* **Productos más y menos vendidos**
* **Costo de envío promedio por tienda**

A partir de estos análisis, se construyó un informe final con una recomendación sustentada en gráficos y métricas comparativas.

**Hallazgo principal:** la **Tienda 4** presenta el menor aporte en ingresos totales y un desempeño general menos competitivo frente a las demás, por lo que se recomienda considerar su venta.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Built With

Estas son las principales herramientas utilizadas en el desarrollo del proyecto:

* [![Python][Python-shield]][Python-url]
* [![Pandas][Pandas-shield]][Pandas-url]
* [![Matplotlib][Matplotlib-shield]][Matplotlib-url]
* [![Jupyter][Jupyter-shield]][Jupyter-url]
* [![Google Colab][Colab-shield]][Colab-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Getting Started

Estas instrucciones permiten ejecutar el análisis localmente o adaptarlo en Google Colab.

### Prerequisites

Asegúrate de contar con lo siguiente:

* Python 3.10 o superior
* pip
* Jupyter Notebook o acceso a Google Colab

Instalación opcional de Jupyter:

    pip install notebook

### Installation

1. Clona el repositorio

       git clone https://github.com/psychedelic-art/alura-store-latam.git

2. Entra en la carpeta del proyecto

       cd alura-store-latam

3. Instala las dependencias

       pip install pandas matplotlib notebook

4. Abre el notebook

       jupyter notebook

5. Ejecuta el archivo `.ipynb` en tu entorno local o súbelo a Google Colab.

> El notebook consume directamente archivos CSV públicos con los datos de cada tienda, por lo que no es necesario descargar manualmente la base de datos si se mantiene la conexión a internet.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- USAGE EXAMPLES -->
## Usage

Este proyecto puede utilizarse para:

* Comparar el rendimiento de múltiples sucursales o tiendas.
* Identificar tiendas con menor participación en ingresos.
* Evaluar categorías de productos con mejor y peor desempeño.
* Analizar el comportamiento de los clientes mediante calificaciones promedio.
* Revisar la eficiencia logística a través del costo promedio de envío.
* Construir una recomendación ejecutiva basada en datos.

### Estructura del análisis

1. **Análisis de facturación**  
   Se calcula el ingreso total de cada tienda y se representa su participación relativa mediante un gráfico circular.

2. **Ventas por categoría**  
   Se estudia el volumen de ventas por categoría de producto para cada tienda, identificando patrones de mayor y menor rotación.

3. **Calificación promedio por tienda**  
   Se compara la percepción del cliente usando el promedio de calificaciones por sucursal.

4. **Productos más y menos vendidos**  
   Se visualizan los productos con mayor y menor volumen de ventas en cada tienda.

5. **Costo de envío promedio por tienda**  
   Se examina el costo logístico promedio, útil para evaluar eficiencia operativa.

### Resultado esperado

El informe final concluye que la **Tienda 4** es la opción más adecuada para vender, debido a que:

* Presenta la menor participación en ingresos totales.
* No destaca en las categorías más estratégicas.
* Su ventaja en costo de envío no compensa su menor desempeño global.
* Otras tiendas muestran mejores combinaciones de ingresos, satisfacción del cliente y fuerza comercial.

_Para más detalles, revisa directamente el notebook y las visualizaciones generadas._

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ROADMAP -->
## Roadmap

- [x] Cargar y consolidar datos de las cuatro tiendas
- [x] Analizar ingresos totales por tienda
- [x] Visualizar ventas por categoría
- [x] Comparar calificaciones promedio
- [x] Identificar productos más y menos vendidos
- [x] Evaluar costo promedio de envío
- [x] Redactar informe final con recomendación

Consulta los [issues abiertos](https://github.com/psychedelic-art/alura-store-latam/issues) para ver mejoras propuestas y tareas futuras.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTING -->
## Contributing

Las contribuciones ayudan a mejorar la calidad del análisis y la presentación del proyecto.

Si deseas aportar:

1. Haz un fork del proyecto
2. Crea una rama para tu mejora

       git checkout -b feature/mejora-analisis

3. Realiza tus cambios y haz commit

       git commit -m "Agrega mejora al análisis comparativo"

4. Sube tus cambios

       git push origin feature/mejora-analisis

5. Abre un Pull Request

### Top contributors:

<a href="https://github.com/psychedelic-art/alura-store-latam/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=psychedelic-art/alura-store-latam" alt="contrib.rocks image" />
</a>

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE -->
## License

Distribuido bajo la licencia MIT. Consulta el archivo `LICENSE` para más información.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTACT -->
## Contact

Andrés Fernando Muñoz Matallana

Project Link: [https://github.com/psychedelic-art/alura-store-latam](https://github.com/psychedelic-art/alura-store-latam)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

Recursos y herramientas útiles para este proyecto:

* [Google Colab](https://colab.research.google.com/)
* [Pandas Documentation](https://pandas.pydata.org/docs/)
* [Matplotlib Documentation](https://matplotlib.org/stable/)
* [Jupyter Documentation](https://jupyter.org/)
* [Markdown Guide](https://www.markdownguide.org/)
* [Shields.io](https://shields.io/)
* [Alura Latam](https://www.aluracursos.com/)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
[contributors-shield]: https://img.shields.io/github/contributors/psychedelic-art/alura-store-latam.svg?style=for-the-badge
[contributors-url]: https://github.com/psychedelic-art/alura-store-latam/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/psychedelic-art/alura-store-latam.svg?style=for-the-badge
[forks-url]: https://github.com/psychedelic-art/alura-store-latam/network/members
[stars-shield]: https://img.shields.io/github/stars/psychedelic-art/alura-store-latam.svg?style=for-the-badge
[stars-url]: https://github.com/psychedelic-art/alura-store-latam/stargazers
[issues-shield]: https://img.shields.io/github/issues/psychedelic-art/alura-store-latam.svg?style=for-the-badge
[issues-url]: https://github.com/psychedelic-art/alura-store-latam/issues
[license-shield]: https://img.shields.io/github/license/psychedelic-art/alura-store-latam.svg?style=for-the-badge
[license-url]: https://github.com/psychedelic-art/alura-store-latam/blob/main/LICENSE
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com
[Python-shield]: https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white
[Python-url]: https://www.python.org/
[Pandas-shield]: https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white
[Pandas-url]: https://pandas.pydata.org/
[Matplotlib-shield]: https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge
[Matplotlib-url]: https://matplotlib.org/
[Jupyter-shield]: https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white
[Jupyter-url]: https://jupyter.org/
[Colab-shield]: https://img.shields.io/badge/Google%20Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=black
[Colab-url]: https://colab.research.google.com/
