# pc4-tf2025
# 🧠 Análisis Predictivo del Rendimiento Académico – Proyecto PC4 CC65

Este proyecto propone una solución distribuida y concurrente basada en programación en Go, aprendizaje automático y procesamiento de datos en tiempo real para la predicción del promedio académico proyectado de estudiantes universitarios en el Perú.

## 👨‍💻 Integrantes
- Luciano Valentino Achin Angeles – U202113624
- Claudia Letizia Mendieta Sifuentes – U20211A147
- Marcelo Roberto Poggi Díaz – U202213741

## 📌 Objetivo
Construir una solución distribuida para el análisis predictivo del rendimiento académico, utilizando datos abiertos de matrícula universitaria, procesados mediante algoritmos de machine learning, contenedores Docker y una arquitectura por capas optimizada para concurrencia.

## 🗃 Dataset
**Fuente:** Superintendencia Nacional de Educación Superior Universitaria (SUNEDU) – Lista de matriculados de pregrado 2025-I
🔗 https://www.datosabiertos.gob.pe/dataset/lista-de-matriculados-de-pregrado-2025-1

## 📂 Estructura del Proyecto
```
/backend
└── api/ # API REST en Go
└── cluster/ # Código concurrente del modelo ML
/frontend
└── spa/ # Interfaz Web SPA
/scripts
└── etl/ # Limpieza y carga de datos
/docs
└── arquitectura.png # Diagrama de arquitectura
```

## 🔧 GitFlow
```
- main        ← Producción
  └── develop   ← Rama de integración
        ├── feature/backend-api
        ├── feature/ml-model
        └── feature/frontend-spa

```
