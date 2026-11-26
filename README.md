# Analisis-deportivo

# PRIMER PROYECTO DE PRUEBA: Motor de similitud de jugadores: Mundial 2018

Proyecto de análisis de datos deportivos construido en Python con los datos abiertos de **StatsBomb** (64 partidos del Mundial de Rusia 2018). Dado un futbolista, el modelo calcula las métricas normalizadas por 90 minutos, filtra por rol y devuelve los diez jugadores con un perfil estadístico más parecido mediante similitud coseno.

📄 **[Leer el informe completo del proyecto (PDF)](./motor_similitud_jugadores_mundial_2018%20(1).pdf)**

## Contenido del repositorio
- `01_primer_analisis_statsbomb.ipynb` — Exploración inicial de eventos y estructura de datos de StatsBomb.
- `02_informe_equipo.ipynb` — Visualización de pases progresivos, tiros (xG) y zonas de recuperación de Francia.
- `final_mundial.ipynb` — Informe automatizado aplicado a la final Francia-Croacia (4-2) con validación de marcador y goles en propia puerta.
- `01_jugadores.ipynb` — Tabla de métricas por jugador (por 90 minutos), agrupación por roles y motor de similitud (caso de estudio: Luka Modrić).
