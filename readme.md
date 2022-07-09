> Casos diarios de covid-19 en Bolivia por departamento 

La fuente de estos datos son reportes diarios de la Unidad de Análisis de Políticas Sociales y Económicas (UDAPE) del Ministerio de Planificación del Desarrollo.

Hasta el 29 de Junio de 2022 estos reportes eran [publicados en formato PDF](https://www.udape.gob.bo/index.php?option=com_content&view=article&id=220:reporte-covid-19&catid=41). Un [programa](https://github.com/sociedatos/covid19-bo-casos_por_departamento/blob/master/update/update_oldpdfs.py) consultaba actualizaciones, leía el PDF y extraía datos de tablas en él cada día. 

Desde el 30 de Junio UDAPE reporta datos mediante un tablero en [Google Datastudio](https://datastudio.google.com/reporting/92796894-acf3-4ab7-9395-20655de351f7/). La resolución de estos datos es diaria y departamental, y se distribuyen como valores diarios y cumulativos. Sin embargo, los valores cumulativos no son simplemente la suma cumulativa de los valores diarios. Mientras los valores diarios que reporta UDAPE reflejan reportes oficiales y diarios de covid-19, los valores cumulativos incuyen revisiones reportadas a veces meses después. Por eso, en este repositorio las actualizaciones a datos diarios sólo adjuntan nuevos días, mientras que las actualizaciones a datos cumulativos reflejan el estado actual de la base de datos de UDAPE desde el inicio de la pandemia.

## Datos diarios

- [Confirmados diarios](https://github.com/sociedatos/covid19-bo-casos_por_departamento/blob/master/confirmados_diarios.csv)
- [Decesos diarios](https://github.com/sociedatos/covid19-bo-casos_por_departamento/blob/master/decesos_diarios.csv)
- [Recuperados diarios](https://github.com/sociedatos/covid19-bo-casos_por_departamento/blob/master/recuperados_diarios.csv)

## Datos cumulativos

- [Confirmados acumulados](https://github.com/sociedatos/covid19-bo-casos_por_departamento/blob/master/confirmados_acumulados.csv)
- [Activos acumulados](https://github.com/sociedatos/covid19-bo-casos_por_departamento/blob/master/activos_acumulados.csv)
- [Decesos acumulados](https://github.com/sociedatos/covid19-bo-casos_por_departamento/blob/master/decesos_acumulados.csv)
- [Recuperados acumulados](https://github.com/sociedatos/covid19-bo-casos_por_departamento/blob/master/recuperados_acumulados.csv)

---

Este repositorio consulta actualizaciones a estos datos cada día a las 12:00 y 18:00 (GMT -4).
