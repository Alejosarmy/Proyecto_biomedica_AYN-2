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
