# 🌍 R y Ciencia de Datos en Español

Proyecto colaborativo y de acceso libre para traducir los libros más importantes de R y Ciencia de Datos al español.
Nació como un esfuerzo personal de aprendizaje y ha crecido hasta convertirse en una iniciativa comunitaria para hacer los mejores recursos de R accesibles a estudiantes, educadores y profesionales hispanohablantes.

## 📚 Traducciones

| Libro                                                           | Autores                                                   | Traducción                                              | Fuente                                                                  |
| --------------------------------------------------------------- | --------------------------------------------------------- | ------------------------------------------------------- | ----------------------------------------------------------------------- |
| **Programación Práctica con R**                                 | Garrett Grolemund                                         | [hopr-es](https://davidrsch.github.io/hopr-es/)         | [rstudio-education/hopr](https://github.com/rstudio-education/hopr)     |
| **R para la Ciencia de Datos (2ª ed.)**                         | Hadley Wickham, Mine Çetinkaya-Rundel & Garrett Grolemund | [r4ds-es](https://davidrsch.github.io/r4ds-es/)         | [hadley/r4ds](https://github.com/hadley/r4ds)                           |
| **Git y GitHub con R**                                          | Jenny Bryan & colaboradores                               | [hggh4r-es](https://davidrsch.github.io/hggh4r-es/)     | [jennybc/happy-git-with-r](https://github.com/jennybc/happy-git-with-r) |
| **Modelado Ordenado con R**                                     | Max Kuhn & Julia Silge                                    | [tmwr-es](https://davidrsch.github.io/tmwr-es/)         | [tidymodels/TMwR](https://github.com/tidymodels/TMwR)                   |
| **R Avanzado**                                                  | Hadley Wickham                                            | [advr-es](https://davidrsch.github.io/advr-es/)         | [hadley/adv-r](https://github.com/hadley/adv-r)                         |
| **Paquetes de R**                                               | Hadley Wickham & Jenny Bryan                              | [rpkgs-es](https://davidrsch.github.io/rpkgs-es/)       | [hadley/r-pkgs](https://github.com/hadley/r-pkgs)                       |
| **ggplot2: Gráficos Elegantes para Análisis de Datos (3ª ed.)** | Hadley Wickham, Danielle Navarro & Thomas Lin Pedersen    | [ggplot2b-es](https://davidrsch.github.io/ggplot2b-es/) | [hadley/ggplot2-book](https://github.com/hadley/ggplot2-book)           |

## 🎯 Objetivos

- Poner materiales de aprendizaje de R de alta calidad a disposición en español.
- Promover las buenas prácticas en programación R e investigación reproducible.
- Fomentar la colaboración y el intercambio de conocimiento en la comunidad global de R.

## ⚙️ Automatización

Cada repositorio de traducción incluye un flujo de trabajo de **revisión mensual automática** (GitHub Actions) que:

1. Se ejecuta el 1.º de cada mes.
2. Obtiene la lista de archivos fuente del repositorio original upstream.
3. Compara la estructura de capítulos con la traducción.
4. Usa un **agente IA** (GitHub Models / `gpt-4o-mini`) para analizar diferencias y generar un resumen accionable en español.
5. Abre automáticamente un **Pull Request** con el informe si se detectan cambios estructurales.

Los informes históricos se guardan en `.github/upstream-checks/` dentro de cada repo.

## 🤝 Contribuir

¡Este es un proyecto abierto; las contribuciones son bienvenidas! Ayuda a traducir, revisar o mejorar los materiales para fortalecer el ecosistema de R en español.

Consulta el archivo `CONTRIBUTING.md` del repositorio de traducción correspondiente para más detalles.
