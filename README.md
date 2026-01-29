# 📈 Series de Tiempo

Este repositorio tiene como objetivo servir como **guía práctica y teórica** para el análisis y modelado de **series de tiempo**, con especial énfasis en aplicaciones económicas y financieras. Está pensado como material de apoyo académico y como referencia para proyectos de análisis de datos.

---

## 📌 Contenido

### 1. Introducción a las series de tiempo

Se presenta el concepto de serie de tiempo, sus componentes principales y su importancia en áreas como economía, finanzas, ingeniería y ciencia de datos.

**Temas incluidos:**
- Definición de serie de tiempo
- Componentes: tendencia, estacionalidad, ciclo y ruido
- Series estacionarias vs no estacionarias
- Transformaciones básicas

**Ejemplos:**
- Series económicas (PIB, inflación)
- Series financieras (precios, rendimientos)
- Series reales (temperatura, tráfico, demanda)

---

### 2. Modelos ARIMA y SARIMA

Se estudian los modelos clásicos para series de tiempo univariadas.

#### 🔹 ARIMA (p, d, q)
- Componentes autorregresivos (AR)
- Diferenciación (I)
- Media móvil (MA)
- Interpretación de parámetros

#### 🔹 SARIMA (p, d, q)(P, D, Q)s
- Extensión estacional del modelo ARIMA
- Identificación de patrones estacionales
- Casos de uso típicos

---

### 3. Funciones de autocorrelación

Herramientas clave para la identificación de modelos:

- **ACF (Autocorrelation Function)**
- **PACF (Partial Autocorrelation Function)**

Se explica cómo interpretarlas y cómo ayudan a seleccionar los parámetros del modelo.

---

### 4. Selección y evaluación de modelos

Criterios estadísticos utilizados para comparar modelos:

- **Log-verosimilitud**
- **Criterio de Información de Akaike (AIC)**
- **Criterios bayesianos (BIC)**

Se discuten ventajas, limitaciones y buenas prácticas en la selección de modelos.

---

### 5. Series de tiempo financieras

Introducción al modelado de la volatilidad, característica común en datos financieros.

#### 🔹 Modelos ARCH y GARCH
- Heterocedasticidad con
