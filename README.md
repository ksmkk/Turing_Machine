# 🖥️ Máquina de Turing con LEDs y Sensor de Luminosidad

Este proyecto implementa una **Máquina de Turing física** utilizando **LEDs** y un **sensor de luminosidad (LDR)** en lugar de imanes y sensores Hall.  
El objetivo es representar operaciones aritméticas básicas en **unario**, de forma didáctica y visual.

---

## 🔢 Representación en Unario
- El número `3` se representa como `111`.
- El número `5` se representa como `11111`.

### Operadores
- **Rojo (LED)** → Suma ➕  
- **Azul (LED)** → Resta ➖  
- **Amarillo (LED)** → Multiplicación ✖️  
- **Verde (LED)** → Indica si una celda está **encendida** (ON) o **apagada** (OFF).

---

## ⚙️ Funcionamiento
1. Una **cinta de cartón** contiene celdas con LEDs.  
2. Un **sensor de luminosidad (LDR)** lee cada celda.  
3. Según la operación seleccionada, se enciende el LED correspondiente al tipo de operación:  
   - **Rojo** → Suma  
   - **Azul** → Resta  
   - **Amarillo** → Multiplicación  
4. El LED **Verde** indica el estado ON/OFF de la celda actual.  

---

## 🛠️ Componentes
- Arduino Uno/Nano
- LDR + resistencia 10kΩ
- 4 LEDs (Rojo, Azul, Amarillo, Verde) + resistencias 220Ω
- Cinta de cartón o cartulina con LEDs
- Pilas o alimentación externa para la cinta
- Botones (opcional) para seleccionar la operación

---

## 📂 Estructura del Repositorio
