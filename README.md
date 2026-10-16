# Matemática II: Cálculo Integral Aplicado a la Ingeniería Ambiental
### Proyecto Integrador de Asignatura — Ciclo Septiembre 2026 – Febrero 2027
**Universidad Nacional de Loja (UNL)**  
**Facultad Agropecuaria y de Recursos Naturales Renovables**  
**Carrera de Ingeniería Ambiental**  
**Docente:** Dr. Guillermo Chuncho  

---

## 📌 Guías Oficiales del Curso

1. 🚀 **[Guía Paso a Paso para Estudiantes: GitHub, VS Code, venv y Terminal](GUIA_ESTUDIANTE_CONFIGURACION_ENTORNO.md)**  
   *Consulte este documento para instalar herramientas, clonar el repositorio, crear el entorno virtual y configurar VS Code.*
2. 📄 **[Guía General del Proyecto Integrador (PDF)](Unidad_1/guias_de_estudio/guia_1/guia_general_proyecto_integrador_matematica.pdf)** y código fuente **[.tex](Unidad_1/guias_de_estudio/guia_1/guia_general_proyecto_integrador_matematica.tex)**.
3. 📄 **[Guía Práctica de Entorno y GitHub para Estudiantes (PDF)](Unidad_1/guias_de_estudio/guia_2/guia_estudiante_entorno_github_vscode.pdf)** y código fuente **[.tex](Unidad_1/guias_de_estudio/guia_2/guia_estudiante_entorno_github_vscode.tex)**.

---

## 📂 Estructura del Repositorio

```text
Informacion_matematica/
├── requirements.txt                     <- Dependencias cientificas de Python
├── GUIA_ESTUDIANTE_CONFIGURACION_ENTORNO.md <- Guia metodologica y practica de terminal
├── Unidad_1/
│   ├── avance_proyecto_integrador/
│   │   ├── avance_1/
│   │   ├── avance_2/
│   │   └── avance_3/
│   ├── guias_de_estudio/
│   │   ├── guia_1/                      <- Guía general del proyecto (PDF y LaTeX)
│   │   ├── guia_2/                      <- Guía de entorno y GitHub (PDF y LaTeX)
│   │   └── guia_3/                      <- Guía de integrales (PDF y LaTeX)
│   ├── lecciones/
│   ├── base_de_datos/                   <- Única carpeta de bases oficiales
│   │   ├── Grupo_01_Relieve_Norte/
│   │   ├── Grupo_02_Relieve_Sur/
│   │   ├── Grupo_03_Cobertura_Norte/
│   │   ├── Grupo_04_Cobertura_Sur/
│   │   ├── Grupo_05_Clima_Norte/
│   │   ├── Grupo_06_Clima_Sur/
│   │   └── Grupo_07_Incendios_Loja/
│   ├── defensa_individual/
│   ├── formulacion/
│   ├── guia/                            <- Sílabo, fechas, presentaciones y exámenes
│   └── producto_tecnico/
├── Unidad_2/
│   ├── avance_proyecto_integrador/
│   │   ├── avance_1/
│   │   ├── avance_2/
│   │   └── avance_3/
│   ├── guias_de_estudio/
│   │   ├── guia_1/                      <- Guía general del proyecto (PDF y LaTeX)
│   │   └── guia_2/                      <- Guía de entorno y GitHub (PDF y LaTeX)
│   ├── lecciones/
│   ├── defensa_individual/
│   ├── formulacion/
│   ├── guia/
│   └── producto_tecnico/
└── Unidad_3/
    ├── avance_proyecto_integrador/
    │   ├── avance_1/
    │   ├── avance_2/
    │   └── avance_3/
    ├── guias_de_estudio/
    │   ├── guia_1/                      <- Guía general del proyecto (PDF y LaTeX)
    │   └── guia_2/                      <- Guía de entorno y GitHub (PDF y LaTeX)
    ├── lecciones/
    ├── defensa_individual/
    ├── formulacion/
    ├── guia/
    └── producto_tecnico/
```

---

## 📊 Asignación de Equipos y Bases de Datos

Las siete bases oficiales están en [`Unidad_1/base_de_datos/`](Unidad_1/base_de_datos/), organizadas por grupo. Las definiciones de variables y el manifiesto se conservan en [`Unidad_1/guias_de_estudio/datos_referencia/`](Unidad_1/guias_de_estudio/datos_referencia/). Son **ventanas de estudio** pequeñas, preparadas para plantear integrales directamente (transectos, series de 72 meses y regiones rectangulares).

| Equipo | Temática Asignada | Zona Territorial | Subcarpeta | Tamaño |
| :---: | :--- | :---: | :--- | :--- |
| **Equipo 1** | Relieve y Accesibilidad | Zona Norte | `equipo_01_relieve_norte/` | 400 celdas (20×20), 400 reg, 17 col |
| **Equipo 2** | Relieve y Accesibilidad | Zona Sur | `equipo_02_relieve_sur/` | 400 celdas (20×20), 400 reg, 17 col |
| **Equipo 3** | Cobertura y Suelo | Zona Norte | `equipo_03_cobertura_norte/` | 100 celdas (10×10) × 72 meses, 7.200 reg, 28 col |
| **Equipo 4** | Cobertura y Suelo | Zona Sur | `equipo_04_cobertura_sur/` | 100 celdas (10×10) × 72 meses, 7.200 reg, 28 col |
| **Equipo 5** | Clima y Atmósfera | Zona Norte | `equipo_05_clima_norte/` | 100 celdas (10×10) × 72 meses, 7.200 reg, 22 col |
| **Equipo 6** | Clima y Atmósfera | Zona Sur | `equipo_06_clima_sur/` | 100 celdas (10×10) × 72 meses, 7.200 reg, 22 col |
| **Equipo 7** | Incendios y Severidad | Cantón Completo | `equipo_07_incendios_loja/` | Serie mensual (72 reg) y resumen por celda (7.997 reg) |

---

## ⚡ Comandos Rápidos para Empezar

```bash
# 1. Clonar el repositorio
git clone https://github.com/cguillermo79/Informacion_matematica.git
cd Informacion_matematica

# 2. Abrir en VS Code
code .

# 3. Crear entorno virtual (en la terminal de VS Code)
python -m venv .venv

# 4. Activar entorno virtual
# En Windows PowerShell:
.\.venv\Scripts\Activate.ps1
# En Linux/macOS:
source .venv/bin/activate

# 5. Instalar dependencias cientificas
pip install -r requirements.txt
```
