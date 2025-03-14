# Sistema de Gestión de Turnos de una Clínica

## Descripción 📝
Este proyecto es un sistema backend para gestionar los turnos de una clínica médica. Permite a los pacientes reservar turnos, cancelarlos y recibir recordatorios. El sistema está diseñado para ser eficiente, escalable y fácil de usar.

## Requisitos 🎯
### Estructuras de datos
- **Lista enlazada (LinkedList)**: Para gestionar los turnos disponibles.
- **Hash map (Dictionary)**: Para almacenar los detalles de cada turno (paciente, médico, fecha, hora).

### Algoritmos
- **Asignación automática de turnos**: Asigna un turno a un paciente basado en la disponibilidad del médico.
- **Detección de conflictos de horarios**: Detecta si dos turnos están asignados al mismo médico a la misma hora.

### Patrones de diseño
- **Observer**: Para enviar recordatorios a los pacientes un día antes de su turno.
- **Factory**: Para crear diferentes tipos de turnos (consulta, emergencia, seguimiento).

### Lógica de programación
- **Validación de turnos**: Un paciente no puede reservar más de un turno por día.
- **Cancelación de turnos**: Libera el horario cuando un turno es cancelado.

## Tecnologías utilizadas 🛠️
- **Lenguaje de programación**: C#
- **Framework**: .NET Core
- **Estructuras de datos**: Listas enlazadas, hash maps.
- **Patrones de diseño**: Observer, Factory.
- **Herramientas**: Git
