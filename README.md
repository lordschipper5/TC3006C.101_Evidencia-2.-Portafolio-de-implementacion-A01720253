# TC3006C.101_Evidencia-2.-Portafolio-de-implementacion-A01720253

## Rodolfo Sandoval Schipper A01720253

## Estructura de este repositorio

Los reportes y la implementacion del analisis son las entregas que ya pasaron por el proceso de retroalimentacion y se ubican dentro de este repositorio.

En la raíz de este repositorio, encontrarás lo siguiente:

Todos los modelos en este repositorio son construidos con **random forest classifier**. 

**Data set utilizado**: [Titanic](https://www.kaggle.com/competitions/titanic/data?select=test.csv)

Descripcion de los datos:

Registros: 891

Numero de Caracteristicas: 6 --> Pclass, Age, Sex, Fam (Cantidad de familia), Fare, y Embarked.

Clases: 1 (Sobrevivio), 0 (No sobrevivio)

### Carpetas
- **Implementacion de una tecnica de aprendizaje maquina**: Aqui se encuentra la entrega para evaluar la competencia SMA0401. Donde se implementa el modelo de **random forest classifier** sin el uso de un framework. La descripcion de la implementacion, y el conjunto de datos se encuentran en el mismo archivo.
  - **randomForestClassifierTitanicA01720253SinFramework** codigo en python de la implementacion con sus respectivas metricas.
  -  **train_data.csv** siendo el archivo de entrenamiento.
  -  **split_survived.csv** siendo los datos reales (objetivo) para el entrenamiento.

  
- **Uso de framework o biblioteca de aprendizaje maquina para la implementacion**: es la carpeta de la implementacion del modelo de **random Forest classifier** con el uso de una biblioteca y framework. Competencias a evaluar SMA0401.
    - **randomForestClassifierConFrameworkA01720253** codigo en python de la implementacion, metricas, y 3 pruebas manuales.
    - **train_transformed.csv** siendo el archivo de entrenamiento con el atributo survived (el split se hace dentro del codigo).
    - **predicciones.csv** resultados del modelo. 

### Archivo
- **Variables seleccionadas en el modelo y su utilidad en el modelo Titanic ETL**: Es el archivo que selecciona las variables a utilizar para los modelos en las carpetas, Explicacada una de las variables seleccionadas en el modelo y su utilidad en el modelo. La explicacion del como funciona el modelo se expresa con comentarios en las implementaciones. Competencias a evaluar SMA0101.

    
Nota: La documentacion tecnica de las implementaciones se encuentran dentro de los archivos como comentarios o texto agregado. 
