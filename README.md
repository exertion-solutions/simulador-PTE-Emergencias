# Simulador PTE Emergencias

Simulador de una planta de tratamiento de efluentes de una fábrica de bebidas (PLC-01), pensado para entrenar operadores en la operación diaria y en simulacros de emergencia ambiental.

**Abrir:** https://exertion-solutions.github.io/simulador-PTE-Emergencias/

## Qué incluye

- Sinóptico de la planta con equipos operables, alarmas priorizadas, tendencias y calidad de vuelco con límites editables.
- 4 escenarios de operación: pH fuera de control, sólidos suspendidos altos, bulking filamentoso y fósforo alto.
- 3 emergencias ambientales: derrame de ácido sulfúrico, corte de energía eléctrica y descarga masiva de jarabe.
- Plan de contingencia con acciones fuera del tablero (avisos, contención, generador, camión atmosférico, muestra, notificación a la autoridad, libro de planta).
- Impacto del evento con indicador de riesgo y su motivo.
- Evaluación con puntaje, procedimiento recomendado y acta del simulacro para copiar.

## Cómo funciona

Es un único archivo `index.html`: todo corre en el navegador, no envía datos a ningún servidor.

## Alcance y límites

- Es un modelo simplificado con fines de entrenamiento. No reemplaza el plan de contingencia ni el permiso de vuelco de la planta.
- Los límites de vuelco de referencia (Res. ADA 336/03, tabla ACUMAR) deben verificarse contra el permiso vigente de cada planta.
- Los indicadores de riesgo del simulacro no son una determinación legal.
- El registro de simulacros de esta versión publicada se guarda solo en el navegador de cada persona (no se comparte). Para conservar un resultado, copiá el acta desde la pantalla de evaluación.
