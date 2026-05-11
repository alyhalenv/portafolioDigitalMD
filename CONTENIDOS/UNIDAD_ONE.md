<div align="center">
 
# 🎓 PORTAFOLIO DE LÓGICA MATEMÁTICA - UNIDAD 1

</div>


---

# 1. DEFINICIÓN DE PROPOSICIÓN
Una proposición es el elemento fundamental de la lógica. Se define como una oración declarativa de la cual podemos afirmar, sin ambigüedad, que es **Verdadera (V)** o **Falsa (F)**. En computación, este concepto se conoce como *bit* (1 o 0).

Para que una expresión sea proposición, debe tener un valor de verdad objetivo. Las preguntas, órdenes o exclamaciones no se consideran proposiciones porque no pueden ser calificadas como verdaderas o falsas.

**Ejemplos simples:**
* **p:** "Hoy es lunes". (Proposición)
* **q:** "El número 10 es par". (Proposición)
* **r:** "¿Cómo estás?". (NO es proposición)



---

# 2. TIPOS DE PROPOSICIONES
Las proposiciones se clasifican según su estructura y complejidad:

* **Proposiciones Simples (Atómicas):** Son aquellas que expresan una sola idea y no tienen conectores lógicos.
  * *Ejemplo:* "El cielo es azul".
* **Proposiciones Compuestas (Moleculares):** Son el resultado de unir dos o más proposiciones simples mediante enlaces lógicos. Su valor de verdad depende de los conectores utilizados.
  * *Ejemplo:* "El cielo es azul **y** está lloviendo".



---

# 3. CONECTORES LÓGICOS
Son operadores que permiten modificar o combinar proposiciones simples para crear estructuras más complejas.

| Operación | Símbolo | Significado | Explicación Teórica |
| :--- | :---: | :--- | :--- |
| **Negación** | $\neg$ | "No" | Cambia el valor de verdad al opuesto. |
| **Conjunción** | $\wedge$ | "Y" | Solo es verdadera si AMBAS partes son verdaderas. |
| **Disyunción** | $\vee$ | "O" | Es verdadera si al menos una parte es verdadera. |
| **Condicional** | $\rightarrow$ | "Si... entonces" | Indica una relación de causa y efecto. |
| **Bicondicional** | $\leftrightarrow$ | "Si y solo si" | Es verdadera solo si ambos tienen el mismo valor. |

**Ejemplo simple:** "Si estudio ($p$), entonces aprobaré ($q$)".



---

# 4. TABLAS DE VERDAD
Las tablas de verdad son herramientas que muestran todos los posibles valores de verdad de proposiciones compuestas según los valores de sus proposiciones simples, se clasifican en:

* **Tautología:** El resultado final es siempre Verdadero.
* **Contradicción:** El resultado final es siempre
* **Contingencia:** El resultado tiene valores Verdaderos y Falsos.

# TABLA DE VERDAD LOGICA PROPOSICIONAL

<div align="center">

  <img width="677" height="421" alt="image" src="https://github.com/user-attachments/assets/2c2de455-ec70-4568-964a-7b7a03780dca" />

  </div>

---

# 5. PRINCIPALES LEYES LÓGICAS
Las principales leyes lógicas son principios universales que garantizan la coherencia del razonamiento, incluyendo la identidad, no contradicción y el tercio excluido, entre otras equivalencias y reglas de inferencia, por lo cual dentro de computación permiten optimizar códigos y algoritmos, pues dejan simplificar proposiciones grandes:


<div align="center">
 
<img width="670" height="362" alt="image" src="https://github.com/user-attachments/assets/339beed2-3b8b-4383-83e5-96352303de6c" />

  </div>



---

# 6. REGLAS DE INFERENCIA
La inferencia es el proceso por el cual se obtienen conclusiones a partir de premisas. Si la estructura es correcta, la conclusión es válida.

1. **Modus Ponens:** Si ocurre la causa, ocurre el efecto. 
   * $[(p \rightarrow q) \wedge p] \rightarrow q$
2. **Modus Tollens:** Si el efecto no ocurrió, la causa tampoco. 
   * $[(p \rightarrow q) \wedge \neg q] \rightarrow \neg p$
3. **Silogismo Disyuntivo:** Si tengo dos opciones y descarto una, la otra debe ser cierta.
   * $[(p \vee q) \wedge \neg p] \rightarrow q$
