## BigData-ProyectoFinal

### linkedService

#### Servicios de vinculación para conectar los diferentes servicios de Azure(DataFactory, Databricks, etc)

### pipeline

#### ingesta_input_capa_bronce: Ingesta de archivos de la carpeta input hacia la carpeta bronce.
#### ingesta_capa_bronce_plata: Ingesta de archivos de la carpeta bronce hacia la carpeta plata.
#### ingesta_capa_plata_oro: Ingesta de archivos de la carpeta plata hacia la carpeta oro.
#### execute_pipeline: Pipeline que realiza la ejecución de los 3 pipelines anteriores.

### trigger

#### Trigger_execute: Disparador que realiza la ejecución diaria del execute_pipeline.
