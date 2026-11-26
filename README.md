
<div align="center">
<img src="./logo-tec.png" alt="Tecnológico de Monterrey" width="200">

# Evidencia 1
## Video individual de etapas iniciales

### Reto de Business Intelligence
### OT Consulting

**Tecnológico de Monterrey — Campus Monterrey**

Soporte Analítico para la Toma de Decisiones  
Grupo 301 · Equipo 3

Profesoras<br>
Claudia Aja Leyva<br>
Maria Imelda Valdez <br>

**Daniela Benítez Mendoza**  
**Matrícula: A00841811**

Noviembre 26, 2026

</div>

---

## Descripción del reto

Desarrollar una solución de Business Intelligence que permita a OT Consulting aprovechar la información de su plataforma de Recursos Humanos para mejorar la toma de decisiones relacionadas con colaboradores, asignaciones, habilidades, proyectos y costos.

La propuesta incluye un tablero de indicadores y un simulador de equipos y costos.

## Etapas del reto

| Etapa | Descripción |
| :--- | :--- |
| 01 | Justificación y planeación |
| 02 | Exploración de datos |
| 03 | Tratamiento y acondicionamiento de datos |
| 04 | Diseño del modelo dimensional lógico |

[Consultar documentación de las cuatro etapas](./Entregas%20Avances)

---

## Evidencias técnicas

### Exploración de datos

- Revisión de ocho fuentes de datos.
- Identificación de inconsistencias y valores faltantes.
- Definición de preguntas de análisis, métricas e indicadores.

### Tratamiento y acondicionamiento

- Limpieza de ocho tablas mediante SQL.
- Estandarización y validación de datos.
- Definición de nuevos atributos y reglas de negocio.
- Transformación de la matriz de habilidades.

**Archivos técnicos:**

- [Scripts SQL de limpieza](./SQL%20commands%20limpieza)
- [Limpieza de colaboradores](./SQL%20commands%20limpieza/colaboradores_limpia.sql)
- [Limpieza de asignaciones](./SQL%20commands%20limpieza/asignaciones_limpia.sql)
- [Transformación de matriz de habilidades](./SQL%20commands%20limpieza/matriz_limpia.sql)
- [Verificación final](./SQL%20commands%20limpieza/verificacion_final.sql)
- [Resultados de las tablas acondicionadas](./Resultados%20Tablas%20Limpieza)

### Modelo dimensional lógico

- Metodología Kimball.
- Tres tablas de hechos.
- Siete dimensiones.
- Modelo de constelación de hechos.

---

## Demostración de la propuesta

Prototipo funcional del módulo de Inteligencia de Negocios:

- Resumen ejecutivo.
- Disponibilidad de consultores.
- Análisis de habilidades.
- Simulador de equipos y costos.
- Proyectos y activos.

**[Abrir demo de OT Consulting](https://otc-app-equipo3.netlify.app/#)**

---

## Conclusiones y acciones futuras

- Validar las reglas de negocio con el socio formador.
- Confirmar los supuestos utilizados para calcular costos.
- Incorporar información sobre la ocupación de los colaboradores.
- Continuar validando los indicadores y visualizaciones.
- Evaluar la integración con la plataforma original de OTC.
