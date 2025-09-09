# Máquina de Turing con LEDs y Sensor de Luminosidad

Este proyecto implementa una **Máquina de Turing física** utilizando **LEDs** y un **sensor de luminosidad (LDR)**. 
El objetivo es representar operaciones aritméticas básicas en **unario**, de forma didáctica y visual.

## 👨‍💻 Autores

Proyecto desarrollado por:

- **Bastián André Salinas Collado** — RUT: 21.848.994-K  
- **Tomás Alexis Guerra Reyes** — RUT: 21.664.334-5  

---
### Operadores
- **Rojo (LED)** → Suma ➕  
- **Azul (LED)** → Resta ➖  
- **Amarillo (LED)** → Multiplicación ✖️  
- **Verde (LED)** → Indica si una celda está **encendida** (ON) o **apagada** (OFF).

---

### Funcionamiento
1. Una **cinta de cartón** contiene celdas con LEDs.  
2. Un **sensor de luminosidad (LDR)** lee cada celda.  
3. Según la operación seleccionada, se enciende el LED correspondiente al tipo de operación:  
   - **Rojo** → Suma  
   - **Azul** → Resta  
   - **Amarillo** → Multiplicación  
4. El LED **Verde** indica el estado ON/OFF de la celda actual.  
---

### Componentes
- Arduino Uno/Nano
- LDR + resistencia 10kΩ
- 4 LEDs (Rojo, Azul, Amarillo, Verde) + resistencias 220Ω
- Cinta de cartón o cartulina con LEDs
- Pilas o alimentación externa para la cinta
- Botones (opcional) para seleccionar la operación
