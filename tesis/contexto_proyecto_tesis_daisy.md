# Contexto del proyecto de tesis de Daisy Quelca Velasquez

Documento de traspaso. Contiene el estado del trabajo, las decisiones tomadas, lo que falta y las reglas de formato, para retomarlo en otra sesión sin repetir lo ya resuelto.

---

## 1. Qué es

Proyecto de tesis de maestría para registrar en la plataforma PILAR de la Escuela de Posgrado de la Universidad Nacional del Altiplano de Puno.

| Dato | Valor |
|---|---|
| Autora | Daisy Crishyely Quelca Velasquez |
| Programa | Maestría en Informática con mención en Gerencia de Tecnologías de Información y Comunicaciones |
| Línea | Sistemas, Computación e Informática |
| Sublínea | Ingeniería de Software e Inteligencia Artificial |
| Asesor probable | Dr. Renzo Apaza Cutipa |
| Plazo | Sustentación entre 6 y 12 meses |

**Título.** Adaptación eficiente de parámetros con DoRA para la predicción del riesgo académico a partir de variables de vulnerabilidad socioeconómica en estudiantes de la Universidad Nacional del Altiplano de Puno.

---

## 2. Contenido del proyecto

**Problema.** La universidad asigna beneficios de bienestar con criterios discrecionales, sin integrar las condiciones del hogar con la trayectoria académica.

**Método.** Dos etapas. Primero agrupamiento no supervisado sobre las variables del hogar para obtener perfiles de vulnerabilidad. Después clasificación supervisada donde ese perfil entra como variable predictora del riesgo académico, comparando nueve condiciones: regresión logística, Random Forest, XGBoost, LightGBM, CatBoost, modelo preentrenado para datos tabulares en modalidad directa, con ajuste fino completo, con adaptación de rango bajo y con DoRA. Explicabilidad con valores de Shapley y matriz de priorización de cuatro cuadrantes que cruza vulnerabilidad con riesgo.

**Hipótesis general.** Formulada como no inferioridad, de modo que la tesis concluye con sentido gane el método que gane.

**Estructura.** Cinco problemas específicos, cinco objetivos específicos y cinco hipótesis, en correspondencia uno a uno y en el mismo orden: perfilamiento, desempeño predictivo, costo computacional, contribución de variables y priorización.

**Datos.** Tres fuentes, todas por solicitar al Vicerrectorado Académico: el registro socioeconómico institucional, el historial académico y el registro de beneficios otorgados. Enlace por código de matrícula seudonimizado.

**Población y muestra.** N igual a 17 000 matriculados aproximadamente. Muestra no probabilística por disponibilidad, con tamaño previsto de n igual a 1 796, cerca del 10.6 por ciento. Fórmula para poblaciones finitas incluida: mínimo requerido de 376 con 95 por ciento de confianza y 5 por ciento de error, margen de error real de 2.19 por ciento.

---

## 3. Reglas de formato que hay que respetar

El documento está construido sobre la plantilla oficial Anexopy1 de la Escuela de Posgrado y hereda sus estilos. No rehacerlo desde cero.

| Aspecto | Regla |
|---|---|
| Página | A4, márgenes de 2 cm, izquierdo 2.5 cm |
| Texto | Times New Roman 11, justificado, interlineado 1.15, sangría de primera línea 1.27 cm |
| Títulos | Estilos Título 1, 2 y 3 con numeración automática: romanos en el primer nivel, decimal en los demás. No escribir los números a mano |
| Numeración de líneas | Activada y continua. No desactivar: el dictamen señala observaciones por número de línea |
| Tablas | Formato APA 7, sin líneas verticales, solo tres horizontales, sin sombreado. Leyenda en dos líneas: número en negrita, título en cursiva debajo |
| Figuras | Mismo criterio de leyenda que las tablas |
| Extensión | Máximo 20 páginas según reglamento. Actualmente 21 |
| Resumen | Máximo 250 palabras. Actualmente 238. El abstract dice lo mismo, 214 palabras |
| Palabras clave | De 5 a 8, en minúsculas y orden alfabético. Son las dimensiones de las variables |
| Referencias | Mínimo 40 autores. Actualmente 50, todas citadas |
| Citas | Criterio adoptado: solo el primer apellido cuando no hay guion, por ejemplo Quintana (2023). Los apellidos con guion se conservan completos |
| Antiplagio | Máximo 20 por ciento de similitud |

**Preliminares.** Siguen el formato de un proyecto ya aprobado: TÍTULO DEL PROYECTO en negrita, AUTOR con nombre y correo, LÍNEA y SUB-LÍNEA con etiqueta en negrita y valor en la misma línea, RESUMEN y ABSTRACT como etiquetas, no como secciones numeradas.

**Antecedentes.** Cada uno debe contener objetivo, metodología con la muestra, resultados con cifras y conclusión. Organizados en tres subsecciones: internacionales, nacionales y locales. Solo tesis de maestría o doctorado, no de pregrado.

---

## 4. Lo que falta, en orden de urgencia

1. **Verificar los antecedentes contra sus fuentes.** Es lo más importante y está a medio hacer. Ver la sección 5.
2. **Completar la cifra de matriculados.** Queda un corchete en la sección de población que dice completar la cifra exacta y la fuente oficial. Es lo único entre corchetes del documento y bloquea el envío.
3. **Rehacer el presupuesto.** Las partidas actuales suman 3 500 soles y son tentativas. Faltan los costos administrativos de la escuela: trámite del proyecto, dictamen, designación de jurados, sustentación, derechos de grado y reporte de similitud. Un total realista está entre seis mil y nueve mil soles, pero requiere el tarifario vigente.
4. **Consultar si el límite de 20 páginas incluye bibliografía y anexo.** El cuerpo solo llega a 17. Si cuenta todo, hay que recortar una página.
5. **Confirmar el correo.** Figura uno personal. Verificar si la escuela exige el institucional.
6. **Revisión del asesor.** Paso obligatorio del flujo en PILAR antes del dictamen.

---

## 5. Problema abierto con los antecedentes

Los antecedentes se redactaron a partir de una matriz bibliográfica generada por otra herramienta, que contenía cifras plausibles pero no verificadas contra las fuentes originales. Al comprobar tres casos, los tres tenían datos inventados.

| Autor | Estado | Hallazgo |
|---|---|---|
| Quintana (2023) | Corregido | Se atribuía una reducción de cuarenta a doce variables y 80 por ciento de precisión. La tesis reporta 76 por ciento con árbol de decisión y no menciona esa reducción |
| Calatayud (2025) | Corregido | El 80.97 por ciento es correcto. El 91.49 por ciento de exhaustividad y los 599 estudiantes no aparecen en la fuente. La universidad estudiada es la Micaela Bastidas de Apurímac |
| Anahua (2024) | Corregido | Los 400 registros, el periodo y la metodología son correctos. El 99 por ciento de exactitud, el 98 de exhaustividad y la lista de variables influyentes no están en la fuente |

**Pendientes de verificar, por orden de riesgo.**

Primero los peruanos con cifras precisas: Mendoza (440 estudiantes, 72 por ciento, 45.8 por ciento), Mayta (92.11 por ciento), Navarrete (2 979 estudiantes), Polo (500 registros), Caselli (98.97 por ciento), Mestas (257 estudiantes, 58.36 por ciento, 3.5 por ciento), Huerta y Jordan.

Después los internacionales con porcentajes: Matz (50 095 estudiantes, 78 y 88 por ciento), Woodruff (2 031 registros, 80.8 y 68 por ciento), Flores (4 365 registros, 96.78 por ciento) y Gutierrez-Pachas.

Al final los que no declaran cifras: Valente, Le Quy, Setiawan, Vaarma y Li, Barzola, Salas y Caldas.

**Procedimiento de verificación.** Abrir el enlace de la referencia, leer el resumen oficial y reescribir el antecedente usando solo lo que la fuente confirma. Si el resumen no da alguno de los cuatro elementos, es preferible omitirlo a inventarlo.

---

## 6. Archivos del proyecto

| Archivo | Qué es |
|---|---|
| Proyecto_tesis_Daisy_DoRA.docx | El proyecto. Es el archivo de trabajo |
| Referencias_tesis_Daisy.ris | Las 50 referencias para importar a Mendeley |
| Referencias_tesis_Daisy.bib | Las mismas en BibTeX |
| formato_epg_unap.md | Especificación del formato oficial extraída del XML de la plantilla |
| guia_busqueda_bibliografica.md | Guía de búsqueda con cadenas para Scopus, ALICIA y RENATI |
| revision_bibliografia.md | Revisión crítica de la matriz bibliográfica original |

---

## 7. Reglas de redacción de la autora

1. Nunca usar la barra como separador en prosa. Usar conectores.
2. Nunca usar el guion largo como separador.
3. Nunca usar el guion como carácter de lista.
4. Ortografía española correcta, con tildes y eñes.
5. Documentos de Word en negro sobre blanco, sin colores.
6. El proyecto describe lo que se hará. Verbos en futuro, no en presente ni en pasado.
