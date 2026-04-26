# Data Model: Elementos Mágicos

## Entidades

### 1. Hechizo
- **Nombre**: (Texto) Ej. "Chispa de Ámbar"
- **Efecto Sensorial**: (Texto) Descripción de luz, sonido o tacto.
- **Coste**: (Texto) Qué consume el robot o el entorno.
- **Emoción Asociada**: (Melancolía / Esperanza)

### 2. Poción
- **Nombre**: (Texto) Ej. "Elixir de Cables Fríos"
- **Ingredientes**: (Lista) Elementos del entorno.
- **Efecto**: (Texto) Cambio en el estado del protagonista.

## Ejemplo de Instancia

```json
{
  "tipo": "Hechizo",
  "nombre": "Canto de Silicio",
  "sensacion": "Un silbido agudo que templa el metal frío",
  "emocion": "Esperanza"
}
```
