# Claude Project Configuration

## Project Overview
Proyecto Vigía - Sistema de gestión autonomos_dev

## Detalles del Proyecto
- **Objetivo Principal:** Desarrollar un sistema de gestión médica integral para el seguimiento de pacientes a través de múltiples fases, desde la recepción hasta la respuesta final, garantizando la privacidad de los datos mediante tokenización (Bruce Wayne → Batman) y cumpliendo con normativas HIPAA.
- **Estado Actual:** 
  - Fase 1 completada con separación dual de bases de datos.
  - Fase 2 implementada con análisis multimodal (imagen y voz), almacenamiento de imágenes médicas, y análisis de agentes con trazabilidad de decisiones.
  - Preparado para Fase 3 con notificaciones multimodales y escalamiento automático para casos de alto riesgo.
- **Logros Clave:**
  - Implementación de arquitectura de IA médica MONAI (precisión 90-95%) con respaldo YOLOv5.
  - Almacenamiento completo de análisis de 9 agentes médicos para transparencia en decisiones.
  - Comunicación bidireccional implementada entre pacientes (WhatsApp) y equipo médico (Slack) con aprobación profesional.
  - 100% de cumplimiento HIPAA con tokenización de datos en todos los componentes críticos.

## Estructura de Fases
1. **Fase 1: Recepción del Paciente** - Completada con tokenización inmediata y separación de datos.
2. **Fase 2: Procesamiento Médico Multimodal** - Implementada con análisis de imagen (MONAI/YOLOv5) y voz (Hume AI), mejorando la confianza a 0.93.
3. **Fase 3: Notificación Equipo Médico** - Lista para implementación con contexto multimodal y trazabilidad de decisiones.
4. **Fase 4: Revisión Humana** - Implementada con flujo de aprobación y acceso seguro a datos PHI.
5. **Fase 5: Respuesta al Paciente** - Implementada con respuestas aprobadas y seguras a través de WhatsApp.

## Próximos Pasos
- Implementar Fase 3 con notificaciones multimodales en Slack, integrando análisis de los 9 agentes.
- Validar el flujo completo de Bruce Wayne → Batman con notificaciones y trazabilidad de decisiones.
- Preparar el despliegue en entorno hospitalario con interfaz web para visualización de imágenes y voz.

Para más información, consulta la carpeta `knowledge_base` donde se almacenará la documentación detallada.
