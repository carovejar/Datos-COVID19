# DP63 - Número de personas notificadas con exámenes por Comuna: Descripción
Archivo que da cuenta del número de personas notificadas con exámenes RT-PCR positivos.
Estos valores son levantados y reportados de manera semanal por el Laboratorio de Biología Computacional de la Fundación Ciencia & Vida 
acorde al informe de Indicadores de Testeo y Trazabilidad publicado semanalmente por el departamento de Epidemiología.

# Columnas y valores

El archivo 'NNotificacionPorComuna.csv' tiene las columnas 'Región', 'Código región', 'Comuna', 'Código comuna', 'Población', y una serie de columnas '[Fecha]', donde en cada una están el 'Numero notificaciones' reportados en cada publicación de Epidemiología, por cada comuna, en cada fecha reportada. El archivo NNotificacionPorComuna_T.csv es la versión traspuesta (serie de tiempo) del primer archivo y NNotificacionPorComuna_std.csv contiene la información en formato estándar. Todos estos valores están separados entre sí por comas (csv).

# Fuente
* Informe de Indicadores de Testeo y Trazabilidad, departamento de Epidemiología, Ministerio de Salud
* Preprocesamiento y manejo de datos: Fundación Ciencia y Vida

# Frecuencia de actualización
Semanal

# Notas aclaratorias

**Nota aclaratoria 1:** Los informes emanados del departamento de epidemiología del Ministerio de Salud informan del último día contabilizado para efectos de la elaboración de cada uno de ellos, habitualmente con corte a las 6 hrs.

**Nota aclaratoria 2:** Los informes de Indicadores de Testeo y Trazabilidad se han publicado a partir del 24 de Agosto 2020.

**Nota aclaratoria 3:** Los datos de población provienen de las proyecciones estadísticas del INE, con base en el CENSO 2017 (para más detalles revisar https://www.ine.cl/estadisticas/sociales/demografia-y-vitales/proyecciones-de-poblacion).
