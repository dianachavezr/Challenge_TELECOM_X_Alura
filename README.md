# 📊 Challenge: TELECOM X - Alura

## 📌 Análisis de Evasión de Clientes en Telecom X

### 🧾 Descripción

Este proyecto tiene como objetivo analizar la **evasión de clientes** (Churn) de la empresa **Telecom X**. A través de un análisis de datos, se busca identificar patrones y factores clave que influyen en la **cancelación de servicios** por parte de los clientes. Este análisis incluye la exploración de datos como **tipo de contrato**, **facturación mensual**, y otras variables relacionadas.

---

## 🎯 Objetivos

- Analizar las razones de la evasión de clientes en función de diferentes variables como tipo de contrato, facturación mensual, entre otros.
- Visualizar los patrones a través de gráficos y estadísticas descriptivas.
- Proponer estrategias para reducir la tasa de evasión de clientes.

---

## ⚙️ Instalación

### ✅ Requisitos

- Python 3.x
- Bibliotecas necesarias:
  - `pandas`
  - `matplotlib`
  - `seaborn`

### 🧪 Pasos para instalar

1. Clona este repositorio:
   
2. ### Instala las dependencias:
   pip install -r requirements.txt

## 🧠 Uso

Abre el notebook en **Google Colab** o en tu entorno local (**Jupyter Notebook**).

Asegúrate de tener el archivo de datos correctamente cargado.

Ejecuta las celdas en orden para:

- Importar datos.
- Realizar limpieza y transformación.
- Ejecutar el análisis y visualizar resultados.

---

## 📊 Análisis Realizado

### 1. Limpieza y Tratamiento de Datos

- Carga de datos desde un archivo JSON.
- Eliminación de valores nulos y duplicados.
- Conversión de datos categóricos (como "Sí"/"No") a valores numéricos (1 y 0) para facilitar el análisis.

### 2. Análisis Descriptivo

- Cálculo de métricas: media, mediana, desviación estándar, etc.
- Visualización de la distribución de variables con:
  - Gráficos de barras
  - Boxplots
  - Diagramas de dispersión

### 3. Gráficos Generados

- **Evasión por tipo de contrato**: distribución de cancelaciones según el tipo de contrato.
- **Facturación mensual vs Evasión**: comparación de montos mensuales entre quienes cancelan y quienes no.
- **Total gastado vs Evasión**: diferencias de gasto total entre clientes activos e inactivos.

<img width="692" height="456" alt="image" src="https://github.com/user-attachments/assets/336e69f4-3e69-43b8-936f-e0e172091b71" />

<img width="683" height="517" alt="image" src="https://github.com/user-attachments/assets/38521ae0-674b-487b-b945-21415659a820" />

<img width="712" height="453" alt="image" src="https://github.com/user-attachments/assets/fe361598-dca3-4fd6-95bf-316f50a45317" />


### 4. Conclusiones

- Los clientes con **contratos a largo plazo** presentan menor evasión.
- Los clientes con **facturación mensual más alta** tienden a cancelar con más frecuencia.
- Variables como **estado civil y edad** pueden ser útiles para crear estrategias de retención personalizadas.

---

## 🧩 Recomendaciones

- **Incentivar contratos a largo plazo**: promociones o descuentos para contratos de 1 o 2 años.
- **Revisar precios y flexibilidad**: ofrecer planes ajustados a las necesidades de los clientes.
- **Estrategias de retención personalizadas**: enfocar esfuerzos en perfiles con mayor riesgo de evasión.

---

## 🤝 Contribuciones

¡Las contribuciones son bienvenidas! Para colaborar:

### 1. Haz un fork del repositorio.
### 2. Crea una rama para tu cambio:

   ```bash
   git checkout -b nueva-funcionalidad

### Realiza tus cambios y haz commit:

git commit -am "Agrega nueva funcionalidad"
Sube los cambios a GitHub:

git push origin nueva-funcionalidad
Abre un Pull Request.

### Licencia
📝 Licencia Este proyecto es parte de un desafío educativo de Alura Latam, y su uso es solo con fines académicos.



   ```bash
   git clone https://github.com/tu_usuario/tu_repositorio.git
