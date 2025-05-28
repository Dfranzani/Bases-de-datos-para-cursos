1. **Belgian Electricity Prices.csv**

​La transparencia ha mejorado notablemente en Europa en los últimos años, culminando con el Reglamento (UE) nº 5 43/2013, de 14 de junio de 2013, sobre presentación y publicación de datos en los mercados eléctricos. A través de este Reglamento, ahora es obligatorio para los proveedores y propietarios de datos de los Estados miembros europeos presentar información fundamental relacionada con la generación, carga, transmisión y balanceo de electricidad para su publicación a través de la Plataforma de Transparencia ENTSO-E.

La transparencia es esencial para la implementación del Mercado Interior Eléctrico (MEI) y para la creación de mercados mayoristas eficientes, líquidos y competitivos. También es fundamental para crear igualdad de condiciones entre los participantes del mercado y evitar que se abuse del poder de mercado (si existe). Esta plataforma permite proporcionar la información necesaria sobre el mercado de la electricidad para el futuro y facilita aún más el desarrollo de sistemas eficientes. y mercados energéticos competitivos en toda Europa. Estos acontecimientos respaldan la evolución constante de los mercados eléctricos en toda Europa en términos de integración, competencia.

[Link de la base de datos](https://www.entsoe.eu/data/transparency-platform/)

Columnas de la base de datos:

- MTU: Hora de inicio del coste de la electricidad.
- [EUR / MWh]: Precio por hora

2. **Estadística Macro, Mercado laboral.csv**: base de datos extraída del Banco central.

Cifras preliminares correspondientes a la Nueva Encuesta Nacional del Empleo (NENE), la que desde abril del 2010 reemplazó a la antigua Encuesta Nacional del Empleo (ENE), vigente desde 1966.

Variaciones calculadas comparando igual trimestre móvil de dos años consecutivos.

Las columnas de la base de datos son las siguientes:

- Periodo: Año, Mes y Día (yyyy-mm-dd) de medición.
- Trabajo: Fuerza de trabajo, promedio móvil trimestral (miles de personas).
- Empleo: Cantidad de empleos disponibles, Promedio móvil trimestral (miles de personas).
- Desempleo: Tasa de desempleo (porcentaje).

3. **Estadística Macro, tipo de cambio Dólar.csv**: base de datos extraída del Banco central.

El tipo de cambio nominal ($/USD) es el promedio de los tipos de cambio del dólar observado

El dólar observado corresponde al precio promedio ponderado de las operaciones de cambio peso dólar spot o al contado, realizadas en el Mercado Cambiario Formal (MCF) en el día hábil bancario inmediatamente anterior y que hayan sido informadas por las empresas bancarias y entidades del MCF, según se indica en la Carta Circular N° 430 del 26 de febrero de 2002.

El índice de tipo de cambio multilateral (TCM), representa una medida del valor nominal del peso con respecto a una canasta amplia de monedas extranjeras.

La canasta del TCM incluye ordenados por su ponderación para el 2010: Estados Unidos, China, Brasil, Argentina, Japón, México, Corea del Sur, Alemania, Perú, España, Canadá, Colombia, Países Bajos, Italia, Francia, Reino Unido, Venezuela, Ecuador, Bélgica y Suiza.

El cálculo de las ponderaciones del TCM se realiza a través de la importancia relativa de las importaciones y exportaciones -excluyendo importaciones de petróleo y exportaciones de cobre- que Chile realiza con ellos.

El índice del tipo de cambio real observado (TCR) se define como el tipo de cambio nominal observado, multiplicado por el cociente entre la inflación externa relevante y el IPC.

La inflación externa en el TCR se calcula con los IPM, expresados en dólares (o IPC en caso de no estar disponible el IPM), de los principales socios comerciales, ponderándolos por la importancia relativa de las importaciones y exportaciones -excluyendo petróleo y cobre- que Chile realiza con ellos.

Para el dólar observado de los días 10, 11, 14, 15 y 30 de septiembre de 2020, las operaciones de Banco Estado consideradas en el cálculo fueron solo las interbancarias.

El último periodo publicado entre el día 23 del mes corriente y el 6 del mes siguiente,corresponde al promedio a la primera quincena del mes.

NC: No corresponde cálculo dado que uno de los valores para la determinación de la variación, es negativa.

Las columnas de la base de datos son las siguientes: base de datos extraída de Banco central.

- Periodo: Año, Mes y Día (yyyy-mm-dd) de medición.
- Cambio: Tipo de cambio nominal (dólar observado $CLP/USD).
- Multilateral: Tipo de cambio nominal multilateral (TCM).
- Real: Tipo de cambio real (índice 1986 = 100).

4. **Depósitos a plazo.csv**: base de datos extraída del Banco central.

Montos de ahorro y número de depósitos a plazo en instituciones financieras fiscalizadas por la CMF, por género

Depósitos a plazo: instrumento financiero de ahorro que consiste en un depósito de dinero cuyo plazo de retiro varía, dependiendo de la preferencia por liquidez del cliente, pero siempre por periodos de tiempo fijos (desde 7 días hasta más de 1 año). Estos depósitos se realizan en instituciones financieras fiscalizadas por la CMF, y su propósito es generar intereses en el periodo de tiempo estipulado de inversión. Dichos resultados son desagregados por género. El cálculo de montos de depósitos a plazo (número de depósitos a plazo) total es la suma de montos de depósitos a plazo (numero de depósitos a plazo) entre mujeres y hombres. El monto de depósitos a plazo se mide en millones de pesos chilenos. El número de depósitos a plazo se mide en número de depósitos. Fuente: CMF BEST

El cálculo de montos de depósitos a plazo (número de depósitos a plazo) total es la suma de montos de depósitos a plazo (numero de depósitos a plazo) entre mujeres y hombres.

El monto de depósitos a plazo se mide en millones de pesos chilenos. El número de depósitos a plazo se mide en número de depósitos.

Las columna de la base de datos son las siguientes.

- Periodo: Año, Mes y Día (yyyy-mm-dd) de medición.
- MontoTotal: Monto de depósitos a plazo, total (millones de pesos).
- MontoM: Monto de depósitos a plazo, mujeres (millones de pesos).
- MontoH: Monto de depósitos a plazo, hombres (millones de pesos).
- NumeroTotal: Número de depósitos a plazo, total.
- NumeroM: Número de depósitos a plazo, mujeres.
- NumeroH: Número de depósitos a plazo, hombres.

5. **Esperanza de vida al nace.csv**: base de datos extraída del Banco central.

Esperanza de vida al nacer por sexo y región, Región de Biobío, Magallanes y la Antártica Chilena (años).

- Periodo: Año, Mes y Día (yyyy-mm-dd) de medición.
- AmbosSexos: Esperanza de vida al nacer de hombres y mujeres.
- Mujeres: Esperanza de vida al nacer de las mujeres.
- Hombres: Esperanza de vida al nacer de los hombres.
- Region: Región de Chile al cual corresponde el cálculo.

6. **Empleo, fuerza de trabajo nacional.csv**: base de datos extraída del Banco central.

La Encuesta Nacional de Empleo (ENE), vigente desde el trimestre enero-marzo de 2010, es una encuesta a hogares que se aplica en viviendas particulares ocupadas, con representatividad a nivel nacional y regional. Las columnas de la base de datos son las siguientes:

- Periodo: Año, Mes y Día (yyyy-mm-dd) de medición.
- Poblacion: Población de 15 años y más.
- FuerzaTotal: Constituye toda la población de 15 años y más que durante la semana de referencia de la encuesta, se encuentra en la situación de ocupados o desocupados.
- Ocupados: Son todas las personas en edad de trabajar, que durante la semana de referencia, dedicaron al menos una hora a alguna actividad para producir bienes o servicios a cambio de una remuneración o beneficios.
- Desocupados: Corresponden a todas las personas en edad de trabajar que no estaban ocupadas en la semana de referencia, que buscaron trabajo durante dicha semana y las tres semanas previas y que estaban disponibles para trabajar en las próximas dos semanas posteriores a la de referencia.
- Cesantes: Personas desocupadas que ya tuvieron su primer trabajo.
- PrimeraVez: Personas desocupadas que no han conseguido su primer trabajo.
- Inactivos: Personas que no están Ocupadas ni Descocupadas. 

7. **Compraventa de viviendas.csv**: base de datos extraída del Banco central.

Ventas: promesas de compraventa firmadas en cada momento del tiempo. Indicadores de venta de vivienda (promesas de compraventa), CChC.

Las columnas de la base de datos son la ssiguientes.

- Periodo: Año, Mes y Día (yyyy-mm-dd) de medición.
- Nacional: Cantidad de ventas de viviendas nuevas a nivel nacional, CChC (unidades).
- GranSantiago: GranSantiago: Cantidad de ventas de viviendas nuevas en Gran Santiago, CChC (unidades).

8. **Indicadores sectoriales de energía.csv**: base de datos extraída del Banco central.

Indicadores de producción de electricidad, gas y agua

Generación eléctrica: Corresponde a la medición mensual de la generación real de las centrales generadoras del sistema eléctrico nacional.

La Producción de Electricidad, Gas y Agua (IPEGA) corresponde a un índice coyuntural cuyo objetivo es estimar, en términos de volumen, la evolución mensual de la actividad productiva de este sector. Por su parte, la estructura de la Electricidad, Gas y Agua es observada mediante las encuestas nacionales Anuales de Empresas de Generación, Distribución y Transmisión de Electricidad (ENADE, ENADD y ENADT), Encuesta Nacional Anual de Empresas de Gas (ENADG) y Encuesta Nacional Anual de Empresas Sanitarias Agua Potable (ENAES), instrumento estadístico censal de frecuencia anual, que entrega información sobre producción, ventas, ingresos por actividad económica, compra de insumos y materias primas, empleo y remuneraciones, entre otros.

Las columnas de la base de datos son las siguientes:

- Periodo: Año, Mes y Día (yyyy-mm-dd) de medición.
- Generacion: Generación de energía eléctrica, CDEC (GWh).
- Indice: Índice de Producción de Electricidad, Gas y Agua, INE (2018=100).
- Electricidad: Índice de Producción de Electricidad.
- Gas: Índice de Producción de Gas.
- Agua: Índice de Producción de Agua.
- IndiceDesestacionalizado: Índice de Producción de Electricidad, Gas y Agua, desestacionalizado, INE (2018=100).


9. **Imacec histórico rezago1 mes.csv**: la base de datos fue extraída del Banco central.

Expectativas PIB, IMACEC (variaciones 12 meses)

La Encuesta de Expectativas Económicas es una encuesta mensual que se realiza a un grupo de académicos, consultores y ejecutivos o asesores de instituciones financieras, la cual entrega información de expectativas de distintas variables macroeconómicas. El dato publicado corresponde a la mediana de las respuestas recibidas.

Las columnas de la base de datos son la siguientes.

- Periodo: Año, Mes y Día (yyyy-mm-dd) de medición.
- IMACEC: IMACEC un mes atrás.

10. **FondosDeCesantia.csv**: los datos fueron extraídos de la Superintendecia de Pensiones.

Valores de Cuota y del Patrimonio de los Fondos de Cesantía. A partir del 1 de noviembre de 2009 se presentan separados los valores de cuota de los Fondos de Cesantía, debido a la entrada en vigencia del Régimen de Inversión de los Fondos de Cesantía, el cual establece carteras de inversión diferenciadas para dichos Fondos.

Las columnas de la base de datos son las siguientes.

- Fecha: Año, Mes y Día (yyyy-mm-dd) de medición.
- VC_CIC: Valor cuota, Fondo de la Cuenta Individual de Cesantía (clp).
- VP_CIC: Valor del patrimonio, Fondo de la Cuenta Individual de Cesantía (clp).
- VC_FCS: Valor cuota, Fondo de Cesantía Solidario (clp).
- VP_FCS: Valor del patrimonio, Fondo de Cesantía Solidario (clp).









