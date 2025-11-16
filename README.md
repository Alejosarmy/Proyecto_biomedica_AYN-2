<<<<<<< HEAD
# Proyecto_biomedica_AYN-2

base datos #1 Parkinson's UPDRS (Análisis Predictivo de Voz) (Parkinsons_updrs.data_LIMPIO.csv)
Numero de filas: 5,875 (No se eliminaron filas, ya venía sin nulos).
Numero de columnas: 23 (Todas las columnas se conservaron).
objetivo: Analizar la progresión y severidad de los síntomas del Parkinson.
Significado de cada columna:
- motor_UPDRS : Severidad Motora. Puntuación principal para el análisis.
- total_UPDRS : Severidad Total de la enfermedad.
- age / sex : variables de edad y sexo (se marca con 0 y 1 )
- Jitter (todos) : Medidas de Temblor de Tono. Mide la inestabilidad de la frecuencia vocal.
- Shimmer (todos) : Medidas de Temblor de Amplitud. Mide la inestabilidad del volumen vocal.
- HNR : Relación Ruido-a-Armónico (mide la claridad de la voz).


base de datos #2 Observations (Análisis de Salud Clínica) (observations_LIMPIO.csv)
Numero de filas: 78,444 (Se eliminaron 1,230 aprox. entradas de texto inválido y nulos).
Numero de columnas: 5 (Se eliminaron CODE y ENCOUNTER).
objetivo: Analizar valores de laboratorio y mediciones de salud (IMC, presión arterial, glucosa).
Significado de cada columna:
- DATE / PATIENT: Fecha de la observación y código del paciente.
- DESCRIPTION: Tipo de Medición (Ej: Body Height, Body Weight, Glucosa, Colesterol).
- VALUE: Resultado Numérico de la medición
- UNITS: Unidad de medida (cm, kg, mg/dL, etc.).
=======
# Proyecto\_biomedica\_AYN-2



##### **Base de datos 1:** Medicaldataset



*Descripción de la base de datos:* Esta base contiene datos médicos de pacientes, como lo son: signos vitales y algunos marcadores cardíacos



*Número de filas:* Tiene 1320 filas

*Número de columnas:* Tiene 9 columnas



*¿Qué significa cada columna?:*

Age: edad del paciente

Gender: género

Heart rate: frecuencia cardíaca

Systolic blood pressure: presión sistólica

Diastolic blood pressure: presión diastólica

Blood sugar: nivel de azúcar en la sangre

CK-MB: valor de la enzima CK-MB

Troponin: valor de troponina

Result: resultado final del diagnóstico







##### **Base de datos 2:** Medicaldataset\_clean



*Descripción de la base de datos:* Esta es la versión limpia de la base anterior. Se quitaron los valores faltantes o datos incorrectos



*Número de filas:* Tiene 1252 filas

*Número de columnas:* Tiene 9 columnas



*¿Qué significa cada columna?:*

Age: edad del paciente

Gender: género

Heart rate: frecuencia cardíaca

Systolic blood pressure: presión sistólica

Diastolic blood pressure: presión diastólica

Blood sugar: nivel de azúcar en la sangre

CK-MB: valor de la enzima CK-MB

Troponin: valor de troponina

Result: resultado final del diagnóstico







##### **Base de datos 3:** hospital\_beds\_USA



*Descripción de la base de datos:* Esta base proporciona datos sobre camas hospitalarias en condados de Estados Unidos, junto con información geográfica y de población



*Número de filas:* Tiene 5714 filas

*Número de columnas:* Tiene 12 columnas



*¿Qué significa cada columna?:*

Country: país

State: estado

County: condado

Lat: latitud

Ing: longitud

Type: tipo de dato

Meaure: tipo de dato

Beds: número de camas

Population: población

Year: año del dato

Source: fuente

Source\_url: enlace de la fuente







##### **Base de datos 4:** hospital\_beds\_USA\_clean



*Descripción de la base de datos:* Esta es la versión limpia de la base de datos anterior

*Número de filas:* Tiene 5714 filas

*Número de columnas:* Tiene 12 columnas



*¿Qué significa cada columna?:*

Country: país

State: estado

County: condado

Lat: latitud

Ing: longitud

Type: tipo de dato

Meaure: tipo de dato

Beds: número de camas

Population: población

Year: año del dato

Source: fuente

Source\_url: enlace de la fuente



Conclusión:

La versión clean tiene un orden diferente, una estructura más ordenada

>>>>>>> rama-nico
