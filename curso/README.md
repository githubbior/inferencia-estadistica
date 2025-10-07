# **Filosofía y Práctica de la Inferencia: Un Marco Integral para el Análisis de Datos**

**Descripción del Curso:**  

Este curso no es un curso de estadística tradicional. Es una inmersión profunda en los fundamentos filosóficos que sustentan cada método estadístico, desde el diseño de un experimento hasta la comunicación de un resultado. Los estudiantes no aprenderán solo *cómo* aplicar una técnica, sino *por qué* funciona, *qué supuestos* hace sobre la realidad y *cuáles son sus consecuencias epistemológicas y éticas*. A través de un marco de clasificación riguroso, el curso desmitifica la inferencia frecuentista y bayesiana, el modelado paramétrico y no paramétrico, y la revolución causal, equipando a los estudiantes para que se conviertan en analistas no solo competentes, sino también conscientes y críticos.

**Público Objetivo:**  

Estudiantes avanzados de pregrado y posgrado en estadística, ciencias de datos, economía, ciencias sociales y cualquier campo cuantitativo. Profesionales que deseen pasar de aplicar recetas a entender el "porqué".

---

## **Estructura del Curso**

### **Módulo 0: Introducción \- El Mapa del Territorio**

* **Tema 1: ¿Qué es la Estadística? Más Allá de los Números.**  
  * La estadística como una forma de razonamiento bajo incertidumbre.  
  * Introducción a las herramientas filosóficas: Ontología (¿qué existe?), Epistemología (¿cómo lo sabemos?), Axiología (¿qué importa?).  

<br>

* **Tema 2: Las Raíces de la Inferencia: Lógica (Deductiva, Inductiva, Abductiva).**  
  * **Inferencia Deductiva:** De lo general a lo particular. La certeza de la conclusión (si las premisas son ciertas).  
    * **Conexión con la Estadística:** Es la lógica de la derivación matemática. Si asumimos un modelo (ej. los datos son normales), podemos *deducir* las propiedades exactas de un estimador. Es la lógica del "mundo del modelo".  
  * **Inferencia Inductiva:** De lo particular a lo general. La probabilidad de la conclusión.  
    * Conexión con la Estadística: Es la definición misma de la inferencia estadística clásica. Observamos una muestra (particular) y generalizamos a una población (general). Es la lógica del **paradigma frecuentista**.  
  * **Inferencia Abductiva:** De una observación a la mejor explicación. La plausibilidad de la conclusión.  
    * **Conexión con la Estadística:** Es la lógica de la formulación de hipótesis y el análisis exploratorio. Vemos un patrón en los datos y *abducimos* un modelo o una causa que lo explicaría mejor. Es la lógica del descubrimiento científico y central en el razonamiento bayesiano (actualizar la creencia en la mejor explicación).  

<br>

* **Tema 3: El Marco de Clasificación de la Inferencia.**  
  * Presentación de los ejes fundamentales:  
    * Fuente de Aleatoriedad: Diseño vs. Modelo.  
    * Interpretación de la Probabilidad: Frecuentista vs. Bayesiana.  
    * Supuestos Distributivos: Paramétrico vs. No Paramétrico.  
    * Objetivo Principal: Estimación vs. Contraste vs. Predicción.  

<br>

* **Tema 4: Los Tres Puntos Ciegos de la Estadística Moderna.**  
  * El contexto social y político (Teoría Crítica/CTS).  
  * La epistemología de la "caja negra" (Inteligencia Artificial).  
  * La revolución causal como pilar fundamental.

---

### **Módulo 1: Diseño de Experimentos y Encuestas \- La Arquitectura del Conocimiento**

* **Tema 1: La Ontología del Control: Experimentos.**  
  * **Filosofía:** Realismo-Manipulacionista. La aleatorización como acto de creación de conocimiento causal.  
  * **Métodos:** Diseño Completamente Aleatorizado, Diseño en Bloques, Diseños Factoriales.  
  * **Concepto Clave:** Validez Interna.  

<br>

* **Tema 2: La Ontología de la Observación: Encuestas.**  
  * **Filosofía:** Realismo-Estructural. La población como una entidad finita y real.  
  * **Métodos de Muestreo:** Muestreo Aleatorio Simple (MAS), Muestreo Estratificado, Muestreo por Conglomerados, Muestreo Sistemático.  
  * **Concepto Clave:** El Marco de Muestreo y las Probabilidades de Selección.  

<br>

* **Tema 3: La Epistemología del Diseño.**  
  * Por qué la aleatorización *es* la justificación, no un detalle técnico.  
  * Comparación de la fuerza inferencial: Control vs. Observación.

---

### **Módulo 2: Análisis Exploratorio y Descriptivo \- El Arte de Escuchar a los Datos**

* **Tema 1: La Ontología de los Datos Vistos.**  
  * **Filosofía:** Fenomenismo (los datos son la realidad) vs. Agnosticismo (los datos son una pista).  

<br>

* **Tema 2: El Reduccionismo de la Agregación.**  
  * **Métodos:** Media, Mediana, Moda, Varianza, Desviación Estándar.  
  * **Análisis Filosófico:** ¿Por qué la media es sensible a valores atípicos y la mediana no? ¿Qué visión del "centro" representa cada una?  

<br>

* **Tema 3: El Holismo de la Visualización.**  
  * **Métodos:** Histogramas, Diagramas de Caja (Boxplots), Gráficos de Dispersión.  
  * **Análisis Filosófico:** La visualización como un acto de descubrimiento inductivo. El rol del AED en la generación de hipótesis.

---

### **Módulo 3: Inferencia Estadística \- El Motor de la Generalización**

* **Unidad 3.1: La Gran División \- Frecuentismo vs. Bayesianismo**  
  * **Tema 1: El Mundo Frecuentista.**  
    * **Filosofía:** Realismo Objetivo. El parámetro es fijo, la probabilidad es una frecuencia.  
    * **Concepto Profundo:** El p-valor.  
      * Definición matemática: `P(Datos | H0 es cierta)`.  
      * Lo que NO es: `P(H0 es cierta | Datos)`.  
      * La controversia y la crisis de replicabilidad.  
    * **Métodos:** Intervalos de Confianza, Pruebas t, Chi-cuadrado, ANOVA.  

<br>

  * **Tema 2: El Mundo Bayesiano.**  
    * **Filosofía:** Subjetivismo. El parámetro es una variable aleatoria, la probabilidad es un grado de creencia.  
    * **Concepto Profundo: El Teorema de Bayes.**  
      * `Creencia Posterior ∝ Evidencia × Creencia Previa`.  
      * El rol y la controversia de los *priors*.  
    * **Métodos:** Intervalos de Credibilidad, Factores de Bayes. Introducción a la computación (MCMC).  

<br>

* **Unidad 3.2: La Fuente de la Aleatoriedad \- Diseño vs. Modelo**  
  * **Tema 1: Inferencia Basada en el Diseño.**  
    * **Filosofía:** El procedimiento lo es todo.  
    * **Métodos:** Estimadores de Horvitz-Thompson, Uso de pesos de muestreo, Tests de Permutación.  
  * **Tema 2: Inferencia Basada en un Modelo.**  
    * **Métodos Paramétricos (Legalismo):** Regresión Lineal (MCO), Modelos Lineales Generalizados (GLM).  
    * **Métodos No Paramétricos (Agnosticismo):** Tests de Mann-Whitney, Kruskal-Wallis, Estimación de Densidad por Kernels.  
    * **Métodos Semiparamétricos:** Modelos de Regresión No Paramétrica.  

<br>

* **Unidad 3.3: El Objetivo \- Estimación, Contraste y Predicción**  
  * **Tema 1: Estimación. Métodos:** Máxima Verosimilitud (MLE).  
  * **Tema 2: Contraste de Hipótesis. Conceptos:** Error de Tipo I y II, Potencia estadística.  
  * **Tema 3: Predicción. Métodos:** Introducción a la Validación Cruzada (Cross-Validation).  

<br>

* **Unidad 3.4: La Revolución Causal**  
  * **Tema 1: Más Allá de la Asociación. Filosofía:** La escalera de la causalidad de Pearl.  
  * **Tema 2: El Lenguaje de la Causalidad. Métodos:** Grafos Acíclicos Dirigidos (DAGs).  
  * **Tema 3: El Cálculo** `do` y los Efectos Potenciales de Rubin. Diferenciar `P(Y|X)` de `P(Y|do(X))`.

---

### **Módulo 4: Toma de Decisiones y Comunicación \- Del Número a la Acción**

* **Tema 1: La Ontología de las Consecuencias.**  
  * **Filosofía:** Pragmatismo y Consecuencialismo.  
  * **Métodos:** Funciones de Pérdida (cuadrática, 0-1), Riesgo Frecuentista (Minimax), Pérdida Esperada Bayesiana.  

<br>

* **Tema 2:** La Epistemología de la Comunicación.  
  * **Filosofía:** Deontología (deber de transparencia) vs. Retórica (arte de persuadir).  
  * **Métodos:** Principios de visualización de datos. Cómo comunicar incertidumbre. La ética de los dashboards.

---

### **Módulo 5: Temas Avanzados y Síntesis Final**

* **Tema 1: La Epistemología Algorítmica.**  
  * **Métodos:** Random Forests, Boosting (XGBoost), Redes Neuronales.  
  * **Filosofía:** El desafío de la "caja negra". Precisión vs. Interpretabilidad (XAI, SHAP, LIME).  

<br>

* **Tema 2: Ética y Justicia Algorítmica.**  
  * **Filosofía:** Teoría Crítica y CTS.  
  * **Conceptos:** Sesgo algorítmico, paridad, *fairness constraints*, accountability.  

<br>

* **Tema 3: La Vaguedad y la Lógica Difusa.**  
  * **Filosofía:** Crítica a la "precisión forzada".  
  * **Métodos:** Introducción a los conjuntos y la lógica difusa.  

<br>

* **Tema 4: Proyecto Final de Síntesis.**  
  * Los estudiantes recibirán un conjunto de datos y un problema. Deberán escribir un informe que justifique, en cada paso del ciclo de vida, sus elecciones metodológicas y filosóficas.

---

## **Evaluación**

* **Ensayos Cortos (30%):** Reflexiones sobre lecturas filosóficas clave (ej. un ensayo sobre el significado del p-valor, otro sobre la ética de los algoritmos).  
* **Problemas Prácticos (30%):** Implementación de los métodos vistos en clase, con un fuerte componente de justificación de supuestos.  
* **Proyecto Final (40%):** El trabajo de síntesis del Módulo 5, que evaluará tanto la competencia técnica como la profundidad del razonamiento filosófico.

---

## **Duración del Curso**

| Formato | Duración | Profundidad | Ideal para... |
| :---- | :---- | :---- | :---- |
| **Semestre Universitario** | 15 semanas | Alta | Estudiantes de posgrado que buscan una base sólida y crítica. |
| **Dos Cuatrimestres** | 20-24 semanas | Muy Alta | Futuros investigadores o profesionales que quieren dominizar el campo. |
| **Bootcamp Intensivo** | 6-8 semanas | Media-Alta | Profesionales que necesitan una actualización rápida y práctica. |
