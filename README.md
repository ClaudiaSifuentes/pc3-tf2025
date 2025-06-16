# pc3-tf2025
# 🧠 Análisis Predictivo de Seguridad Ciudadana – Proyecto PC3 CC65

Este proyecto propone una solución distribuida y concurrente basada en programación en Go, Machine Learning y procesamiento de datos en tiempo real para la predicción de zonas con alta incidencia delictiva en Perú.

## 👨‍💻 Integrantes
- Luciano Valentino Achin Angeles – U202113624
- Claudia Letizia Mendieta Sifuentes – U20211A147
- Marcelo Roberto Poggi Díaz – U202213741

## 📌 Objetivo
Construir una solución distribuida de análisis predictivo en seguridad ciudadana, utilizando datos abiertos de denuncias policiales, procesados mediante algoritmos de ML distribuidos, contenedores Docker y una arquitectura en capas.

## 🗃 Dataset
**Fuente:** INEI – Registro Nacional de Denuncias de Delitos y Faltas 2017  
🔗 https://datosabiertos.gob.pe/dataset/registro-nacional-de-denuncias-de-delitos-y-faltas-2017-instituto-nacional-de-estad%C3%ADstica-e

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
