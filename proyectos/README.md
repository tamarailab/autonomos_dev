# Proyectos Autonomos Dev

Esta carpeta contiene proyectos independientes del equipo.

## Estructura:
- Cada proyecto es un repositorio Git independiente
- No se sincronizan con el repo principal (están en .gitignore)
- Cada uno tiene su propio README y configuración

## Proyectos actuales:
1. autonomos_dev/ - Template base clonado
2. [próximo proyecto]/

## Para crear nuevo proyecto:
```bash
cd proyectos/
git clone https://github.com/usuario/nuevo-proyecto.git
# o crear desde cero:
mkdir nuevo-proyecto && cd nuevo-proyecto && git init
ls -la docs/
ls -la proyectos/
Después podemos buscar y documentar otros repos del equipo. ¿Ejecutas?
# Crear repo SIE en proyectos
cd proyectos
mkdir sie-superintendencia && cd sie-superintendencia
git init

# Estructura inicial
echo "# SIE - Superintendencia de Educación" > README.md
echo "" >> README.md
echo "Sistema para [definir propósito]" >> README.md

# Crear .gitignore básico
echo "node_modules/" > .gitignore
echo ".env" >> .gitignore
echo "*.log" >> .gitignore

# Primer commit
git add .
git commit -m "feat: inicializar proyecto SIE"

# Volver al directorio principal
cd ../..
🧩 Descripción del Desafío

En Chile, más de 11.000 establecimientos educacionales operan con financiamiento público, gestionados por más de 5.000 sostenedores. Actualmente, no existen mecanismos eficaces que orienten y retroalimenten el uso pedagógico y financiero de estos recursos. En 2023, se detectaron $46.200 millones en gastos no aceptados, evidenciando la necesidad de herramientas que permitan a los sostenedores anticiparse y mejorar su gestión en tiempo real.

El desafío consiste en crear una plataforma digital que integre datos de distintas fuentes y entregue análisis en línea, recomendaciones, alertas y comparaciones con pares, todo desde una interfaz sencilla y amigable para el usuario. Esta herramienta debe ayudar a tomar decisiones informadas, mejorar la planificación y fortalecer el vínculo entre gestión, transparencia y calidad educativa.

📅 Fechas Clave

* Periodo de postulación: 22 de mayo de 2025 al 9 de julio de 2025
* Duración total del desafío: 10 meses


💰 Financiamiento Total
Hasta $200.000.000 CLP por proyecto. 


🧪 Etapas del Desafío

1. Diseño de Indicadores Clave
Proyectos a financiar: 5
Monto por proyecto: $40.000.000 CLP
Objetivo: Identificar, diseñar y validar indicadores clave que permitan evaluar el uso eficiente de los recursos públicos en el sistema escolar. Se espera la creación de un prototipo inicial de la plataforma digital, considerando interoperabilidad con fuentes existentes y una experiencia de usuario accesible.


2. Validación en Contexto Real
Proyectos a financiar: 3
Monto por proyecto: $90.000.000 CLP
Objetivo: Implementar las plataformas desarrolladas en un número reducido pero diverso de sostenedores reales, evaluando su desempeño frente a datos auténticos y necesidades del día a día. Se medirá la utilidad de las alertas, la claridad de las recomendaciones y la capacidad del sistema para integrarse a procesos existentes.

3. Escalamiento y Operación Funcional
Proyecto a financiar: 1
Monto por proyecto: $200.000.000 CLP


Objetivo: Desplegar completamente la solución tecnológica, acompañando a los sostenedores en la toma de decisiones estratégicas y promoviendo una cultura de mejora continua en la gestión escolar.

📌 ¿Comienzan 5 y termina 1?
Sí. El desafío está diseñado en 3 etapas consecutivas donde los proyectos se van seleccionando y eliminando según su desempeño. Es como un "embudo competitivo":


1. Etapa 1: Diseño de Indicadores Clave

Postulan muchos, pero solo 5 proyectos son seleccionados.

Deben desarrollar un prototipo inicial de la solución, con indicadores y diseño funcional.

⬇️

2. Etapa 2: Validación en Contexto Real

De los 5 iniciales, solo 3 proyectos pasan a esta etapa.

Deben probar sus soluciones en entornos reales (con sostenedores reales), midiendo eficacia y usabilidad.

⬇️

3. Etapa 3: Escalamiento y Operación Funcional

# Crear estructura del proyecto SIE
cd proyectos
mkdir sie-superintendencia && cd sie-superintendencia
git init

# README principal
cat > README.md << 'EOF'
# SIE - Sistema de Retroalimentación para el Buen Uso de Recursos Públicos en Educación

## 🎯 Objetivo
Desarrollar una plataforma innovadora que optimice la gestión, fiscalización y retroalimentación de recursos en el sistema educativo chileno, promoviendo un gasto efectivo que impacte positivamente en los aprendizajes.

## 📊 Contexto
- 11.000+ establecimientos educacionales
- 5.000+ sostenedores
- USD 9 mil millones anuales en subvenciones
- $46.200 millones en gastos no aceptados (2023)

## 🚀 Solución Propuesta
Plataforma digital con:
- Análisis predictivo de gastos
- Alertas tempranas
- Benchmarking con pares
- Recomendaciones basadas en evidencia
- Dashboard interactivo

## 📅 Timeline
- **Etapa 1** (10 meses): Diseño de indicadores - $40M CLP
- **Etapa 2** (8 meses): Validación real - $90M CLP  
- **Etapa 3** (6 meses): Escalamiento - $70M CLP

## 🏆 Estructura Competitiva
# Crear estructura del proyecto SIE
cd proyectos
mkdir sie-superintendencia && cd sie-superintendencia
git init

# README principal
cat > README.md << 'EOF'
# SIE - Sistema de Retroalimentación para el Buen Uso de Recursos Públicos en Educación

## 🎯 Objetivo
Desarrollar una plataforma innovadora que optimice la gestión, fiscalización y retroalimentación de recursos en el sistema educativo chileno, promoviendo un gasto efectivo que impacte positivamente en los aprendizajes.

## 📊 Contexto
- 11.000+ establecimientos educacionales
- 5.000+ sostenedores
- USD 9 mil millones anuales en subvenciones
- $46.200 millones en gastos no aceptados (2023)

## 🚀 Solución Propuesta
Plataforma digital con:
- Análisis predictivo de gastos
- Alertas tempranas
- Benchmarking con pares
- Recomendaciones basadas en evidencia
- Dashboard interactivo

## 📅 Timeline
- **Etapa 1** (10 meses): Diseño de indicadores - $40M CLP
- **Etapa 2** (8 meses): Validación real - $90M CLP  
- **Etapa 3** (6 meses): Escalamiento - $70M CLP

## 🏆 Estructura Competitiva
## 📁 Estructura del Proyecto
