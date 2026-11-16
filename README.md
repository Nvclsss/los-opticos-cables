# Fusión de fibra
En este repositorio se documenta el procedimiento técnico de conectorización y empalme por termofusión de fibra óptica, logrando la unión permanente y de baja pérdida de los hilos de vidrio para la habilitación del enlace de red.
# Manual Técnico: Empalme por Termofusión de Fibra Óptica y Presupuesto Óptico

**Asignatura:** Infraestructura de Redes (TCB304)  
**Sede:** INACAP La Serena  
**Unidad:** Unidad 2 - Infraestructura de redes de fibra óptica  
**Nombre:** Nicolas Torres Parra

## Objetivo General del Proyecto

Diseñar, documentar e implementar de forma rigurosa un repositorio técnico en Git y manual en formato Markdown que evidencie el proceso completo de conectorización, preparación, limpieza de precisión, corte mecánico (cleaving) y termofusión por arco eléctrico en redes de fibra óptica monomodo; aplicando estrictamente los protocolos de seguridad industrial, el uso de elementos de protección personal (EPP) y la disposición adecuada de residuos de vidrio.

## 1. Glosario Técnico 

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
**Elementos de Protección Personal (EPP):** guantes de seguridad, bototos de seguridad y chaquetilla para la prevención de impactos e ingreso de astillas de vidrio y también lentes de seguridad para cubrir de los pelos de fibra óptica y no dañar los ojos.
 **Pinza Peladora de Precisión (*Stripper*):** Herramienta de pelado de 3 posiciones para remover las cubiertas protectoras hasta exponer el hilo de vidrio de **125 micras** sin mellar la fibra.
**Alcohol Isopropílico (99.9% de pureza):** Solvente para la eliminación de grasas, recubrimientos y residuos sobre el hilo de vidrio desnudo.
 **Paños Libres de Pelusa (*Kimwipes*):** Toallitas de precisión utilizadas en conjunto con el alcohol isopropílico para una limpieza profunda de la fibra.
**Cortadora de Precisión (*Cleaver*):** Herramienta mecánica con cuchilla circular para realizar cortes perpendiculares en el vidrio con un ángulo próximo a los **90 grados**.
 **Fusionadora de Fibra Óptica:** Equipo automatizado de alineación por núcleos/cladding que ejecuta la descarga de **arco eléctrico** para fundir e integrar los hilos de fibra.
**Manguitos Termo-contraíbles (*Heat Shrink*):** Tubos de protección mecánica con alma de acero que se contraen mediante calor en el horno integrado de la fusionadora para proteger el punto de empalme.



## 3. Preparación del Área de Trabajo y Seguridad

La preparación adecuada del banco de trabajo y el cumplimiento de las normativas de seguridad son fundamentales para evitar contaminación en los hilos de fibra óptica y prevenir riesgos laborales.

**Procedimiento de Preparación:**
1. **Identificación:** Identificar el tipo de fibra y los materiales disponibles en el puesto.
2. **Inspección de Instrumental:** Verificar el estado operativo y limpieza de las herramientas.
3. **Orden del Banco:** Organizar los materiales e insumos sobre una superficie limpia y libre de polvo.
4. **Gestión de Residuos:** Ubicar el contenedor rígido de residuos de fibra cerca del área de trabajo para el desecho inmediato de astillas[cite: 1].
5. **Asignación de Roles:** Distribuir las funciones de forma individual o en equipo.

> ⚠️ **ADVERTENCIA DE SEGURIDAD CRÍTICA:** Los restos de fibra de vidrio cortada son extremadamente peligrosos y pueden penetrar la piel o causar daños oculares. Utilice siempre EPP (lentes de seguridad) y deseche los residuos en contenedores rígidos.






## 5. Guía Paso a Paso: Proceso de Conectorización y Termofusión

1. **Inserción del Protector Termo-contraíble:**
   🚫 ERROR COMÚN N° 1: Olvidar insertar el manguito termo-contraíble antes de realizar el corte y la fusión.

   * Deslizar el manguito termo-contraíble (*heat shrink*) en uno de los extremos de la fibra **antes** de pelar e insertar en la fusionadora.

2. **Stripping (Pelado de la Fibra):**
   🚫 ERROR COMÚN N° 2: Mellar o rayar el hilo de vidrio de 125 µm durante el uso de la pinza peladora.
   * Con la pinza peladora de precisión (*stripper*), remover la chaqueta exterior y el recubrimiento primario (250 µm / 900 µm) hasta exponer el vidrio desnudo de **125 micras** en una longitud aproximada de 30 a 40 mm, sin mellar el hilo de vidrio.
   
<img width="1200" height="1600" alt="image" src="https://github.com/user-attachments/assets/07c6d35d-1a8f-4f07-ae12-a4d23784a229" />


3. **Limpieza de Precisión:**
   🚫 ERROR COMÚN N° 3: Tocar el hilo de vidrio limpio con los dedos o reutilizar un paño sucio.
   *  Utilizar paños secos libres de pelusa (*Kimwipes*) humedecidos con **alcohol isopropílico de 99.9% de pureza**. Limpiar el hilo de vidrio desnudo con firmeza hasta escuchar el chirrido característico (*squeak*).
   
  <img width="1200" height="1600" alt="image" src="https://github.com/user-attachments/assets/b804067a-b9dd-4314-b9d2-2ffdee1848d8" />


  
4. **Corte de Precisión (Cleaving):**
   🚫 ERROR COMÚN N° 4: Realizar un corte con ángulo superior a 1° o con imperfecciones en el borde.
   * Colocar la fibra en la cortadora de precisión (*cleaver*) alineando la cubierta con la regla de medida (10 a 16 mm según especificación de la fusionadora). Realizar el corte logrando un ángulo perpendicular inferior a 1°.
  <img width="2853" height="2081" alt="IMG_20261112_151005" src="https://github.com/user-attachments/assets/3889e4d6-356b-41a4-88e4-674b60843d60" />



5. **Proceso de Termofusión por Arco Eléctrico:**
   🚫 ERROR COMÚN N° 5: Apoyar el hilo de vidrio directamente sobre los electrodos o tener los V-grooves sucios.
   * Encender la fusionadora y seleccionar el programa de alineación (Monomodo SM).
   * Colocar los dos extremos de fibra sobre las guías en V (*V-grooves*) sin tocar los electrodos.
   * Cerrar la cubierta para iniciar el proceso automático de alineación de núcleos/cladding, descarga de arco de limpieza y descarga de fusión eléctrica.
   
   <img width="1200" height="1600" alt="image" src="https://github.com/user-attachments/assets/4ccb134f-2559-4ea2-88a9-fb4c239480ec" />


6. **Protección del Empalme:**
   🚫 ERROR COMÚN N° 6: Tensionar o doblar la fibra desprotegida mientras se desliza el manguito hacia la fusión.

   * Deslizar el manguito termo-contraíble cubriendo el punto exacto de la fusión y ubicarlo en el horno integrado de la maquina para su contracción por calor.
   
 <img width="1200" height="1600" alt="image" src="https://github.com/user-attachments/assets/66629f8e-14ee-46d2-b779-5267d62d345a" />



### 6.Medición y Verificación de la Fusión (Criterio 2.1.5)

| Parámetro Evaluado | Valor Registrado / Estándar | Estado / Diagnóstico Técnico |
| :--- | :---: | :--- |
| **Tipo de Fibra** | Monomodo (SM) | Identificada correctamente en el perfil de la fusionadora. |
| **Alineación de Núcleos** | Óptima (Ejes X / Y) | Sin desplazamiento lateral ni burbujas de aire en la unión. |
| **Pérdida Estimada (Empalme)** | **0.02 dB** | **Aprobado / Excelente** (Muy inferior al límite máximo de 0.10 dB). |
| **Calidad Física del Enlace** | Óptima | Continuidad verificada y baja atenuación garantizada. |

> 📊 **Análisis Técnico de Verificación:** El equipo de termofusión registró una pérdida estimada de **0.02 dB** tras ejecutar la descarga de arco eléctrico. Dado que el estándar de la industria exige pérdidas iguales o inferiores para empalmes por fusión, se determina que el corte con el *cleaver* y la alineación de los núcleos fueron exitosos, asegurando la calidad y estabilidad del enlace óptico.









## 10. 📊 Presupuesto Óptico del Enlace (Backbone de Campus)

### 10.1. Fórmula y Parámetros
La pérdida óptica total se determina mediante la siguiente expresión:

Pérdida Total = (Longitud × Atenuación de Fibra)
              + (N.º Empalmes × Pérdida por Empalme)
              + (N.º Conectores × Pérdida por Conector)
              + Margen de Seguridad

| Elemento | Especificación / Valor de Referencia |
| :--- | :--- |
| **Fibra Óptica** | Monomodo OS2 (1310 nm) — $0,35\text{ dB/km}$ |
| **Empalmes** | Fusión por arco — $0,02 dB$ *(Medición real)* |
| **Conectores** | LC/APC — $0,40 dB $ |
| **Margen de Seguridad** | Reserva operacional — $3,00 dB $ |
| **Transceptor** | SFP 1G LX — Presupuesto disponible de $20,00 dB $ |

---

### 10.2. Tabla de Cálculo (Enlace de 2,5 km)

| Componente | Cantidad / Magnitud | Pérdida Unitaria | Pérdida Total |
| :--- | :---: | :---: | :---: |
| **Fibra monomodo OS2** | $2,5 km}$ | $0,35 dB/km | $0,875  dB$ |
| **Empalmes por fusión** | $2$ | $0,02 dB $ | $0,040 $ |
| **Conectores LC/APC** | $4$ | $0,40 dB | $1,600  dB $ |
| **Margen de seguridad** | — | — | $3,000 dB$ |
| **PÉRDIDA TOTAL ESTIMADA** | — | — | **$5,515  dB $** |

---

### 10.3. Análisis de Viabilidad y Holgura

* **Presupuesto disponible (SFP 1G LX):** $20,000 dB$
* **Pérdida total calculada:** $5,515 dB$
* **Holgura óptica restante:** $20,000 - 5,515 = 14,485 dB$

> ✅ **Conclusión:** El enlace presenta una holgura favorable de **$14,485 dB **, lo que confirma que las pérdidas se encuentran muy por debajo del límite del transceptor, garantizando su **viabilidad técnica**.
