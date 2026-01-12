📊 Análisis de Comportamiento y Perfilado de Usuarios: ConnectaTel
🎯 Objetivo del Proyecto

El objetivo principal de este proyecto es transformar datos brutos de telecomunicaciones en conclusiones accionables de negocio.
Se enfoca en limpiar inconsistencias técnicas, diagnosticar patrones de datos faltantes y crear una segmentación de clientes que
permita a ConnectaTel optimizar sus planes comerciales y mejorar la retención de usuarios.
📂 Datasets Utilizados

El análisis se basa en dos fuentes de datos principales:

    users: Contiene información demográfica de los clientes (ID, edad, ciudad, fecha de registro y tipo de plan).

    usage: Registro detallado de la actividad de los usuarios, incluyendo el tipo de interacción (llamada o mensaje),
    la duración en minutos y la longitud del texto.

🛠️ Etapas del Análisis

El proyecto sigue un flujo de trabajo de Ciencia de Datos de extremo a extremo:

    Exploración y Diagnóstico: Identificación de nulos, tipos de datos y valores inconsistentes 
    (como edades negativas o fechas futuras).

    Limpieza de Datos (Data Cleaning): * Tratamiento de valores sentinel en la columna age.

        Corrección de anomalías temporales (registros del año 2026).

        Diagnóstico de datos faltantes como MNAR (Missing Not At Random).

    Ingeniería de Características (Feature Engineering): Creación de una tabla agregada por 
    usuario con métricas de consumo total.

    Análisis Estadístico y Outliers: Detección de valores extremos mediante el método IQR y
    visualización de distribuciones con Seaborn.

    Segmentación Estratégica: Clasificación de usuarios por Nivel de Uso (Bajo, Medio, Alto) 
    y Grupo Etario (Joven, Adulto, Adulto Mayor).

    Insights Ejecutivos: Traducción de hallazgos técnicos en recomendaciones de marketing y producto.
