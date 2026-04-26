# Feature Specification: Magia, Hechizos y Pociones

**Feature Branch**: `002-magic-spells-potions`
**Created**: 2026-04-26
**Status**: Draft
**Input**: User description: "quiero que haya magia, hechizos y pociones"

## User Scenarios & Testing *(mandatory)*

### User Story 1 - Uso de Magia en la Narrativa (Priority: P1)

Como lector, quiero que los elementos mágicos se integren de forma natural en el relato para enriquecer la atmósfera sensorial y emocional del cuento.

**Why this priority**: Es el núcleo de la solicitud del usuario y define el tono fantástico del relato.

**Independent Test**: El cuento puede leerse incluyendo elementos de magia, hechizos o pociones sin perder la coherencia con los principios de melancolía y esperanza.

**Acceptance Scenarios**:

1. **Given** un momento de necesidad o conflicto, **When** el protagonista utiliza un hechizo, **Then** se debe describir su efecto utilizando el lenguaje sensorial definido en la constitución.
2. **Given** la presencia de una poción, **When** esta es consumida o utilizada, **Then** el resultado debe tener un impacto emocional claro (ej. alivio de la melancolía o un destello de esperanza).

---

### User Story 2 - El Coste de la Magia (Priority: P2)

Como lector, quiero entender que la magia no es infinita o gratuita para mantener la tensión narrativa y el realismo emocional.

**Why this priority**: Evita que la magia resuelva todos los problemas sin esfuerzo, manteniendo el tono dual de la obra.

**Independent Test**: Se identifica claramente en el texto un límite, sacrificio o ingrediente necesario para que la magia funcione.

**Acceptance Scenarios**:

1. **Given** la intención de realizar un hechizo poderoso, **When** el protagonista lo intenta, **Then** se debe mostrar el agotamiento o el material consumido para lograrlo.

## Requirements *(mandatory)*

### Functional Requirements

- **FR-001**: El sistema de magia debe expresarse íntegramente en **castellano** (ej. nombres de hechizos, descripción de efectos).
- **FR-002**: Los hechizos deben tener efectos **sensoriales** tangibles (luz, sonido, temperatura).
- **FR-003**: Las pociones deben requerir **ingredientes** que evoquen elementos del entorno (metálicos, naturales o emocionales).
- **FR-004**: La magia debe utilizarse como una herramienta para transitar entre la **melancolía y la esperanza**.
- **FR-005**: Las descripciones de los actos mágicos deben seguir la **estructura de frase corta**.

### Key Entities

- **Hechizo**: Acción mágica con un nombre evocador y un efecto sensorial inmediato.
- **Poción**: Sustancia líquida con propiedades transformadoras o curativas.
- **Ingrediente**: Elemento necesario para la elaboración de pociones o ejecución de hechizos.
- **Maná/Esencia**: Fuente de energía limitada que alimenta la magia (implícito).

## Success Criteria *(mandatory)*

### Measurable Outcomes

- **SC-001**: Al menos el 30% de los adjetivos utilizados en las escenas de magia deben ser sensoriales (vista, tacto, etc.).
- **SC-002**: Cada hechizo o poción mencionado debe tener un nombre único en castellano.
- **SC-003**: El uso de la magia debe estar directamente relacionado con un cambio en el estado emocional del relato (de melancolía a esperanza o viceversa).

## Assumptions

- La magia existe en el mismo universo que la tecnología (si se integra con el cuento del robot).
- El protagonista tiene la capacidad o el conocimiento para usar estos elementos.
- Los ingredientes para las pociones se pueden encontrar en el entorno del cuento.

## Edge Cases

- **Fallo del hechizo**: Qué ocurre cuando la magia no funciona como se esperaba por falta de esencia o ingredientes.
- **Efectos secundarios de las pociones**: El impacto de una poción en un ser no orgánico (si aplica).

## Clarifications [NEEDS CLARIFICATION]

### Q1: Integración Narrativa
**Context**: "quiero que haya magia, hechizos y pociones"
**What we need to know**: [NEEDS CLARIFICATION: ¿Cómo debe integrarse la magia con la historia existente del robot? ¿Es un robot que descubre la magia, o es un mundo puramente fantástico?]

### Q2: Tipo de Magia
**Context**: "hechizos y pociones"
**What we need to know**: [NEEDS CLARIFICATION: ¿La magia debe ser sutil y poética o explícita y poderosa (estilo RPG)?]
