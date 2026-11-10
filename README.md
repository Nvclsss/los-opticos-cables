# Fusión de fibra
En este repositorio se documenta el procedimiento técnico de conectorización y empalme por termofusión de fibra óptica, logrando la unión permanente y de baja pérdida de los hilos de vidrio para la habilitación del enlace de red.
# Manual Técnico: Empalme por Termofusión de Fibra Óptica y Presupuesto Óptico

**Asignatura:** Infraestructura de Redes (TCB304)  
**Sede:** INACAP La Serena  
**Unidad:** Unidad 2 - Infraestructura de redes de fibra óptica  
**Nombre:** Nicolas Torres Parra
---

## 1. Glosario Técnico Exprés

### 1. Conceptos Fundamentales
* **Núcleo:** Centro dieléctrico de la fibra de alto índice de refracción (típicamente 9 µm en monomodo) por donde se propaga la luz.
* **Cladding (Revestimiento):** Capa de vidrio de 125 µm de menor índice de refracción que rodea al núcleo para confinar la luz mediante reflexión interna total.
* **Atenuación:** Pérdida gradual de potencia de la señal óptica expresada en decibeles (), causada por absorción, dispersión y curvaturas en el enlace.
* **Longitud de Onda:** Distancia entre crestas de la onda de luz expresada en nanómetros (), siendo y  las estándar en telecomunicaciones.

### 2. Preparación y Herramientas
* **Stripping:** Proceso mecánico de remoción graduada de la cubierta primaria y buffer con la pinza peladora para exponer el vidrio desnudo de 125 micras.
* **Cleaving:** Corte mecánico de alta precisión del hilo de vidrio con el *cleaver*, logrando un plano perpendicular con un ángulo inferior a 1°.
* **Paños Kimwipes:** Toallitas sintéticas libres de pelusa utilizadas con alcohol isopropílico al 99.9% para la desinfección y limpieza profunda del vidrio.
* **Manguito Termocontraíble (Heat Shrink):** Tubo protector con alma de acero que se contrae por calor para blindar mecánicamente la zona de la fusión.

### 3. Fusión y Mediciones
* **Arco Eléctrico:** Descarga de alto voltaje generada entre dos electrodos de tungsteno para calentar y fundir los extremos de las fibras alineadas.
* **V-Grooves (Guías en V):** Canales mecánicos de alta precisión donde se asientan las fibras para garantizar su alineación axial previo al arco.
* **Presupuesto Óptico:** Cálculo teórico de la suma total de pérdidas (fibra, empalmes, conectores y margen) para verificar la factibilidad del enlace.
* **Power Meter:** Instrumental de medición óptica que registra la potencia absoluta ($$) o relativa ($) transmitida a lo largo de la red.
---

## 2. Seguridad y Manejo de Materiales

> ⚠️ **ADVERTENCIA DE SEGURIDAD CRÍTICA**  
> Los restos de fibra de vidrio cortada (astillas) son extremadamente peligrosos. Pueden penetrar la piel o ingresar al torrente sanguíneo si se ingieren o se introducen en los ojos.

## Herramientas e Instrumentos Utilizados
**Elementos de Protección Personal (EPP):** guantes de seguridad, bototos de seguridad y chaquetilla para la prevención de impactos e ingreso de astillas de vidrio.
 **Pinza Peladora de Precisión (*Stripper*):** Herramienta de pelado de 3 posiciones para remover las cubiertas protectoras hasta exponer el hilo de vidrio de **125 micras** sin mellar la fibra.
**Alcohol Isopropílico (99.9% de pureza):** Solvente para la eliminación de grasas, recubrimientos y residuos sobre el hilo de vidrio desnudo.
 **Paños Libres de Pelusa (*Kimwipes*):** Toallitas de precisión utilizadas en conjunto con el alcohol isopropílico para una limpieza profunda de la fibra.
**Cortadora de Precisión (*Cleaver*):** Herramienta mecánica con cuchilla circular para realizar cortes perpendiculares en el vidrio con un ángulo próximo a los **90 grados**.
 **Fusionadora de Fibra Óptica:** Equipo automatizado de alineación por núcleos/cladding que ejecuta la descarga de **arco eléctrico** para fundir e integrar los hilos de fibra.
**Manguitos Termo-contraíbles (*Heat Shrink*):** Tubos de protección mecánica con alma de acero que se contraen mediante calor en el horno integrado de la fusionadora para proteger el punto de empalme.













## 3. Guía Paso a Paso: Proceso de Conectorización y Termofusión

1. **Inserción del Protector Termo-contraíble:**
   🚫 ERROR COMÚN N° 1: Olvidar insertar el manguito termo-contraíble antes de realizar el corte y la fusión.

   * Deslizar el manguito termo-contraíble (*heat shrink*) en uno de los extremos de la fibra **antes** de pelar e insertar en la fusionadora.

2. **Stripping (Pelado de la Fibra):**
   🚫 ERROR COMÚN N° 2: Mellar o rayar el hilo de vidrio de 125 µm durante el uso de la pinza peladora.
   * Con la pinza peladora de precisión (*stripper*), remover la chaqueta exterior y el recubrimiento primario (250 µm / 900 µm) hasta exponer el vidrio desnudo de **125 micras** en una longitud aproximada de 30 a 40 mm, sin mellar el hilo de vidrio.
   
  falta foto de el pelado de la fibra

3. **Limpieza de Precisión:**
   🚫 ERROR COMÚN N° 3: Tocar el hilo de vidrio limpio con los dedos o reutilizar un paño sucio.
   *  Utilizar paños secos libres de pelusa (*Kimwipes*) humedecidos con **alcohol isopropílico de 99.9% de pureza**. Limpiar el hilo de vidrio desnudo con firmeza hasta escuchar el chirrido característico (*squeak*).
   
  falta foto de la limpieza con alcohol

  
4. **Corte de Precisión (Cleaving):**
   🚫 ERROR COMÚN N° 4: Realizar un corte con ángulo superior a 1° o con imperfecciones en el borde.
   * Colocar la fibra en la cortadora de precisión (*cleaver*) alineando la cubierta con la regla de medida (10 a 16 mm según especificación de la fusionadora). Realizar el corte logrando un ángulo perpendicular inferior a 1°.
   
   falta foto del corte de 90 grado

5. **Proceso de Termofusión por Arco Eléctrico:**
   🚫 ERROR COMÚN N° 5: Apoyar el hilo de vidrio directamente sobre los electrodos o tener los V-grooves sucios.
   * Encender la fusionadora y seleccionar el programa de alineación (Monomodo SM).
   * Colocar los dos extremos de fibra sobre las guías en V (*V-grooves*) sin tocar los electrodos.
   * Cerrar la cubierta para iniciar el proceso automático de alineación de núcleos/cladding, descarga de arco de limpieza y descarga de fusión eléctrica.
   
   falta foto de aliniacion 

6. **Protección del Empalme:**
   🚫 ERROR COMÚN N° 6: Tensionar o doblar la fibra desprotegida mientras se desliza el manguito hacia la fusión.

   * Deslizar el manguito termo-contraíble cubriendo el punto exacto de la fusión y ubicarlo en el horno integrado de la maquina para su contracción por calor.
   
   !falta foto del termocontraible

---

## 4. Análisis de Resultados y Presupuesto Óptico

### Medición de Pérdidas y Verificación

* **Pérdida Estimada por Fusionadora:** falta todavia eso

foto de medicion

### Tabla de Presupuesto Óptico Teórico (Enlace GPON)

me falta medir 



| Elemento | Cantidad / Longitud | Pérdida Unitaria Standard | Pérdida Total Estimada |
| :--- | :---: | :---: | :---: |
| **Fibra Monomodo (SM)** |  | 0| 0 |
| **Conectores SC/APC** | 0 | 0 | 0 |
| **Empalmes por Fusión** | 0 | 0 | 0 |
| **Margen de Seguridad (GPON)** | 0 | 0| 0 |
| **Pérdida Total del Enlace** | — | — | *0|

