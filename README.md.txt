Base de Datos Biomédica 🧬

Este proyecto contiene bases de datos utilizadas en el curso de **Ingeniería Biomédica**, para análisis y gestión de información médica.
👩‍💻 Integrantes del equipo
- Valentina Osorio  
- Aylin [Apellido]

📂 Archivos incluidos
Base de datos Valentina
- **appointments.csv** Esta base de datos recopila información relacionada con las citas médicas programadas por los pacientes en una clínica.
Cada registro representa una cita única, donde se detallan los datos del paciente, el médico, la fecha y el estado de la atención.

Los campos principales son:
appointment_id: Identificador único de la cita.
patient_id: Código del paciente que solicita la cita.
doctor_id: Código del médico asignado.
appointment_date: Fecha programada para la cita.
appointment_time: Hora correspondiente a la cita.
reason_for_visit: Motivo de la consulta (consulta general, terapia, emergencia, etc.).
status: Estado actual de la cita (programada, completada, cancelada o no asistida).
- **heart.csv** La base heart.csv contiene información clínica y biomédica de pacientes utilizada para el análisis de enfermedades cardíacas.
Reúne variables fisiológicas, resultados de pruebas médicas y antecedentes de los pacientes, con el objetivo de estudiar los factores que influyen en la aparición de patologías del corazón.

Los campos principales son:
age: Edad del paciente.
sex: Sexo biológico (1 = masculino, 0 = femenino).
cp: Tipo de dolor torácico.
trestbps: Presión arterial en reposo (mm Hg).
chol: Nivel de colesterol sérico (mg/dl).
fbs: Glucosa en ayunas (1 si > 120 mg/dl).
restecg: Resultado del electrocardiograma en reposo.
thalach: Frecuencia cardíaca máxima alcanzada.
exang: Angina inducida por ejercicio (1 = sí, 0 = no).
oldpeak: Depresión del segmento ST inducida por el ejercicio.
slope: Pendiente del segmento ST.
ca: Número de vasos principales coloreados por fluoroscopia.
thal: Resultado del test de talio.
target: Diagnóstico final (1 = presenta enfermedad cardíaca, 0 = sin enfermedad).

Base de datos Aylin
**Patients Data ( Used for Heart Disease Prediction )** Esta base de datos recopila información sobre pacientes con el objetivo de predecir o analizar el riesgo de enfermedades cardíacas.
Contiene variables relacionadas con salud general, condiciones médicas, hábitos de vida y antecedentes clínicos, lo que permite construir modelos de predicción o estudios epidemiológicos sobre factores de riesgo cardiovascular.
Estructura de los datos
Cada fila representa un paciente, identificado por un PatientID.
Las columnas principales incluyen:
Datos personales y físicos
State: Estado o región del paciente.
Sex: Sexo biológico del paciente.
AgeCategory: Rango de edad (por ejemplo, “Age 65 to 69”).
HeightInMeters / WeightInKilograms / BMI: Altura, peso e índice de masa corporal.
Antecedentes y enfermedades
HadHeartAttack: Indica si el paciente ha tenido un infarto.
HadAngina: Si ha presentado angina (dolor torácico).
HadStroke: Si ha sufrido un accidente cerebrovascular.
HadAsthma, HadSkinCancer, HadCOPD, HadDepressiveDisorder, HadKidneyDisease, HadArthritis, HadDiabetes: Otras condiciones médicas relevantes.
Discapacidades o dificultades
DeafOrHardOfHearing, BlindOrVisionDifficulty, DifficultyConcentrating, DifficultyWalking, DifficultyDressingBathing, DifficultyErrands: Dificultades físicas o cognitivas reportadas.
Hábitos y factores de riesgo
SmokerStatus: Estado como fumador (actual, exfumador, nunca fumó).
ECigaretteUsage: Uso de cigarrillos electrónicos.
AlcoholDrinkers: Si consume alcohol.
Pruebas y vacunas
ChestScan: Si se ha realizado una tomografía o examen de tórax.
HIVTesting, FluVaxLast12, PneumoVaxEver, TetanusLast10Tdap: Pruebas de salud y vacunaciones recientes.
Factores recientes
HighRiskLastYear: Si fue considerado de alto riesgo en el último año.
CovidPos: Resultado de prueba positiva para COVID-19.
**healthcare_dataset** La base de datos contiene 55.500 registros de pacientes y 15 columnas. Representa información hospitalaria completa: datos personales, clínicos, administrativos y financieros.
Columnas y su significado
1. Name
Tipo: Texto
Nombre del paciente.
2. Age
Tipo: Entero
Edad del paciente.
3. Gender
Tipo: Texto
Género del paciente (masculino, femenino, otro).
4. Blood Type
Tipo: Texto
Tipo de sangre (A+, B-, O+, etc.).
5. Medical Condition
Tipo: Texto
Condición médica principal (ej.: Cáncer, Diabetes, Fracturas, etc.).
6. Date of Admission
Tipo: Texto (formato fecha)
Fecha en que el paciente fue admitido.
7. Doctor
Tipo: Texto
Médico tratante asignado al caso.
8. Hospital
Tipo: Texto
Institución hospitalaria donde se atendió el paciente.
9. Insurance Provider
Tipo: Texto
Aseguradora médica del paciente.
10. Billing Amount
Tipo: Número decimal
Monto facturado por los servicios hospitalarios.
11. Room Number
Tipo: Entero
Número de habitación asignada.
12. Admission Type
Tipo: Texto
Tipo de admisión:
Emergency (Emergencia)
Elective (Programada)
Urgent (Urgente)
13. Discharge Date
Tipo: Texto (formato fecha)
Fecha de alta médica.
14. Medication
Tipo: Texto
Medicación principal administrada.
15. Test Results
Tipo: Texto
Resultado de pruebas médicas:
Normal
Abnormal
Inconclusive

⚙️ Descripción del proyecto
El objetivo del proyecto es centralizar datos clínicos en un repositorio colaborativo, utilizando **Git y GitHub** para control de versiones.  
Cada integrante trabaja en una rama independiente (`valentina` y `aylin`) y luego se integran los cambios en la rama principal (`main`).

## 🧠 Cómo usarlo
1. Clona el repositorio:
   ```bash
   git clone https://github.com/valeosorio28voo-design/Base_de_datos_biomedica1.git
