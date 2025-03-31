# Un meta-análisis histórico sobre la relación entre la ciencia y los videojuegos

Jonnatan Pereira - Jose Alejandro Portela

Se realiza un estudio sobre los campos de texto `titulo`, `resumen`, `introduccion`, `conclusiones` y `referencias` de varias decenas de articulos relacionados con la búsqueda "Ciencia y videojuegos", utilizando *Procesamiento de lenguaje natural* (NLP) con Python

- [Documento del proyecto](https://github.com/jjpereirab/seminario_2024_1/blob/main/2024_proyecto_seminario.pdf)
  
## Uso con Conda

Clonar el repositorio y crear un entorno de Conda haciendo uso del archivo yml incluido

    git clone git@github.com:jjpereirab/ciencia_videojuegos_nlp.git
    cd ciencia_videojuegos_nlp
    conda env create --name <env_name> --file environment.yml

Ahora se pueden ejecutar todas las partes del código desde un notebook de Jupyter sin requerimientos adicionales

    conda activate <env_name>
    jupyter notebook

- [Codigo del análisis](https://github.com/jjpereirab/seminario_2024_1/blob/main/text_analysis.ipynb)
