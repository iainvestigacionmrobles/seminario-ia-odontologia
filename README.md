# 🦷 Seminario: IA y Seguridad de Datos en Odontología

**Ponente:** Marco Antonio Robles Huamán — Keluma SAC  
**Audiencia:** Especialistas en Odontología — Sudamérica

---

## ▶ Ejecutar en Google Colab — Un clic

| Notebook | Descripción | Abrir |
|----------|-------------|-------|
| **Demo Completo** | Dataset NIH + IA + Grad-CAM + Excel | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/iainvestigacionmrobles/seminario-ia-odontologia/blob/main/EJECUTAR_TODO.ipynb) |
| **Mis Radiografías** | Convierte tus propios DICOMs en dataset IA | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/iainvestigacionmrobles/seminario-ia-odontologia/blob/main/PARA_ALUMNOS_mis_radiografias.ipynb) |

---

## 📋 ¿Qué aprenderás?

- Cómo funciona la IA aplicada al diagnóstico por imagen dental
- Flujo completo: **DICOM → PNG → Dataset → Modelo → Predicción**
- Cómo anonimizar radiografías (HIPAA / Ley 29733 Perú / LGPD Brasil)
- Qué son Pearl, Overjet y Grad-CAM — y cómo replicarlos con Python
- Cómo construir tu propio dataset con las radiografías de tu clínica

---

## 🗂️ Notebooks

### 1. `EJECUTAR_TODO.ipynb` — Demo del seminario
El ponente ejecuta este notebook en vivo durante el seminario.

**Incluye 7 módulos (seleccionables desde un menú visual):**
1. Estadísticas del dataset NIH (112,120 radiografías · 14 patologías)
2. Galería visual por enfermedad
3. Exportar 1,000 imágenes PNG a Google Drive
4. Flujo DICOM completo con anonimización
5. Entrenar red neuronal con Transfer Learning (MobileNetV2) — ~4 min
6. Mapa de calor Grad-CAM (equivalente a Pearl/Overjet)
7. Excel completo: catálogo de 112,120 imágenes + predicciones + glosario

### 2. `PARA_ALUMNOS_mis_radiografias.ipynb` — Trabajo práctico
El alumno lo ejecuta con sus **propias radiografías dentales**.

**Flujo:**
1. Sube tus archivos `.dcm` a Google Drive
2. Completa un Excel con el diagnóstico de cada caso
3. El notebook convierte, anonimiza, nombra y cataloga todo
4. Obtén tu dataset PNG + Excel + modelo entrenado con tus datos

---

## 📦 Dataset utilizado en el demo

**ChestMNIST** — MedMNIST / NIH Clinical Center  
- 112,120 radiografías de tórax  
- 14 patologías etiquetadas  
- Libre acceso — sin credenciales  
- [medmnist.com](https://medmnist.com)

---

## 🔒 Privacidad y seguridad de datos

Este seminario enfatiza el cumplimiento normativo:

| Marco legal | País | Aplica a |
|-------------|------|----------|
| **HIPAA** | EE.UU. | Datos de salud en sistemas conectados |
| **Ley 29733** | Perú | Datos personales sensibles |
| **LGPD** | Brasil | Datos personales incluyendo salud |

**Regla de oro:** anonimizar el DICOM **antes** de subirlo a cualquier nube.

---

## 🚀 Cómo usar

### Opción A — Google Colab (recomendado)
1. Haz clic en el botón **Open in Colab** de la tabla de arriba
2. El notebook se abre en tu cuenta de Google
3. Ejecuta las celdas en orden (Shift+Enter)

### Opción B — Clonar el repositorio
```bash
git clone https://github.com/iainvestigacionmrobles/seminario-ia-odontologia.git
cd seminario-ia-odontologia
pip install medmnist tensorflow pydicom pillow openpyxl scikit-learn seaborn
jupyter notebook EJECUTAR_TODO.ipynb
```

---

## 📚 Referencias

- [MedMNIST](https://medmnist.com) — Dataset ChestMNIST
- [Pearl AI](https://hellopearl.com) — IA dental comercial
- [Overjet](https://www.overjet.com) — IA dental comercial
- [pydicom](https://pydicom.github.io) — Procesamiento DICOM en Python
- [TensorFlow / Keras](https://tensorflow.org) — Framework de Deep Learning

---

*Seminario "Encuentro 1" — IA y Seguridad de la Información aplicada a la Odontología*  
*Marco Antonio Robles Huamán · Keluma SAC · Lima, Perú*
