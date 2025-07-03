# 🍕 Entregas de Keka

Keka trabaja como repartidora de pizzas en un barrio. Cada pedido tiene un **código de dos dígitos `n` (10 ≤ n ≤ 99)**.

Para que un pedido sea **“rápido de entregar”** (y así Keka se gane un bono), el código del pedido debe cumplir:

1️⃣ Ser **múltiplo de 3** (los pedidos con códigos múltiplos de 3 corresponden a zonas con calles rectas).  
2️⃣ La **diferencia entre las dos cifras del código sea mayor a 3** (la distancia entre los barrios sea significativa, para aprovechar el bono).  
3️⃣ El **código no termina en 0** (los códigos que terminan en 0 indican zonas con portería difícil y no dan bono).

Si el pedido cumple estas condiciones, Keka imprime: **SI**

y sale de inmediato a entregarlo. Si no, imprime: **NO**


y espera el siguiente pedido.

---

##  Tu tarea

Dado el número `n` (código del pedido), imprime `"SI"` si Keka puede salir rápido a entregarlo, o `"NO"` en cualquier otro caso.

---

## Restricciones

- Sin bucles.  
- Solo `if`.  
- Puedes usar `//`, `%`, `abs`, `str()` si lo deseas.

---

##  Ejemplo 1

**Entrada:**

51


**Salida:**

SI


**Explicación:**

- 51 es múltiplo de 3 ✅
- Dígitos: 5 y 1 → diferencia = 4 > 3 ✅
- Termina en 1 (≠ 0) ✅

Todas las condiciones se cumplen, por lo que Keka puede salir a entregar de inmediato.





