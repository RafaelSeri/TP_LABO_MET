# TP Grupal — Laboratorio de Métodos Cuantitativos Aplicados a la Gestión

Trabajo práctico grupal de exploración, análisis y presentación de datos reales asistido por IA.
Facultad de Ciencias Económicas (UBA) · 2do Cuatrimestre 2026.

---

## Integrantes

| Integrante | Usuario de GitHub |
|---|---|
| Catalina Fiorini | [@catafiorini](https://github.com/catafiorini) |
| Rafael Seri | [@RafaelSeri](https://github.com/RafaelSeri) |
| Federico Mingorance | [@fedem2004](https://github.com/fedem2004) |
| Micaela Berzoni | [@micaelaberz](https://github.com/micaelaberz) |
| Genaro D'Angelo | [@GenaroDangelo](https://github.com/GenaroDangelo) |

---

## Tema y pregunta de investigación

**Tema:** demanda de electricidad en Argentina.

**Pregunta principal:** ¿Cuánto influye la temperatura en la demanda eléctrica de Argentina y en qué épocas del año es más crítica?

**Fuente de los datos:** CAMMESA — Demanda de Electricidad (Cuadro 1.28), publicado por el Ministerio de Economía de la Nación
en *Economía en números*: https://www.argentina.gob.ar/economia/datos/nivel-de-actividad

**Cobertura:** serie anual 2005–2025, trimestral y mensual hasta agosto de 2026.

**Variables principales:** demanda total, demanda residencial, comercio e industria, grandes usuarios,
temperatura promedio, potencia máxima y demanda por distribuidora (EDENOR, EDESUR, EPEC, EPESF, etc.).

---

## Estructura del repositorio

```
├── DF/                          # Datasets
│   ├── actividad_ied.xlsx       # Base cruda (hoja 1.28 Electricidad), la lee el notebook
│   └── base_limpia.xlsx         # Base depurada, la genera el notebook
├── notebooks/
│   └── Tp_labo.ipynb            # Notebook de Google Colab: carga, limpieza, análisis y gráficos
├── graficos/                    # Gráficos exportados con plt.savefig()
├── Informe/
│   ├── informe.tex              # Código LaTeX del informe
│   └── Tp_LabMetCuant.pdf       # Informe académico compilado
├── PPT/
│   └── Presentacion_Oral.html   # Presentación de la defensa
├── GuiaTP/                      # Enunciado del TP
└── README.md
```

---

## Estado de las entregas

| Entregable | Ubicación | Estado |
|---|---|---|
| Inscripción del grupo | Formulario | ✅ |
| Dataset crudo y limpio | `DF/` | ✅ |
| Notebook ejecutado (.ipynb) | `notebooks/` | ✅ |
| Gráficos (mín. 3, tipos distintos) | `graficos/` | ⏳ |
| Informe académico (PDF) | `Informe/` | ✅ |
| Presentación (6–10 diapositivas) | `PPT/` | 🔄 En curso |
| Complemento opcional (video / sitio web) | _[link]_ | — |

**Defensa:** viernes 6 de noviembre de 2026 (virtual), 5–7 minutos de exposición.
