# Matemáticas del Machine Learning
*Repositorio para el curso 'Matemáticas del Machine Learning' de la Universidad Nacional de Colombia, tomado en 2026-1S.*

## Lista de Tareas

Este README lista todos los ejercicios asignados en el curso y tiene un link con la respuesta para cada ejercicio.

1. **Hoeffding inequality doesn't apply** — Ejercicio 1.10: Correr una simulación de computador lanzando 1,000 monedas justas. Lanzar cada moneda independientemente 10 veces. Enfocarse en 3 monedas: `c_1` es la primera moneda lanzada; `C_rand` es una moneda elegida al azar; `C_min` es la moneda que tuvo la frecuencia mínima de caras (elegir la más temprana en caso de empate). Sean `V_1`, `V_rand` y `V_min` la fracción de caras obtenida para las tres monedas respectivas.
   - (a) ¿Cuál es μ para las tres monedas seleccionadas?
   - (b) Repetir este experimento completo un gran número de veces (ej. 100,000 corridas del experimento completo) para obtener varias instancias de `V_1`, `V_rand` y `V_min`, y graficar los histogramas de las distribuciones de `V_1`, `V_rand` y `V_min`. Notar que qué monedas terminan siendo `C_rand` y `C_min` puede diferir de una corrida a otra.
   - (c) Usando (b), graficar estimaciones de P[|v−μ| > ε] en función de ε, junto con la cota de Hoeffding 2e^(−2ε²N) (en la misma gráfica).
   - (d) ¿Qué monedas obedecen la cota de Hoeffding y cuáles no? Explicar por qué.
   - (e) Relacionar la parte (d) con los múltiples bins de la figura.

<img width="729" height="604" alt="image" src="https://github.com/user-attachments/assets/ba66e1d7-4ef7-4f15-98e4-d9f65a69aca7" />

   → [Answer](#)

2. **Entropía** — Probar que log₂ P(X=i) es la cantidad de preguntas binarias que se necesitan para representar un mensaje con esa probabilidad. Realizar la demostración de por qué se puede expresar la entropía de una variable aleatoria mediante la fórmula adjunta.

<img width="537" height="137" alt="image" src="https://github.com/user-attachments/assets/712bc6de-2d80-4cbe-be3e-cee7f92d015b" />

   → [Answer](#)

3. **Support Vector Machine** — Problema de optimización asociado a cómo encontrar los mejores pesos para un SVM y desarrollarlo con optimización convexa.
   → [Answer](#)

4. **Perceptrón** — Implementar el algoritmo del perceptrón y entender por qué funciona. Hacer los ejercicios 1.2 y 1.3. Adicionalmente, responder:

<img width="796" height="585" alt="image" src="https://github.com/user-attachments/assets/41f02f52-a2d5-4fa6-a29f-a80460e8dc8b" />

   - (a) ¿El algoritmo encuentra los parámetros correctos? (¿Separa los datos?)
   - (b) ¿El algoritmo para en un número finito de pasos? (¿Cómo garantizar convergencia?)
   - (c) ¿Por qué funciona? (Esta última está más relacionada al ejercicio 1.3 de la misma presentación).
   → [Answer](#)

5. **Modelar XOR** — Modelar un XOR conectando varias neuronas básicas. Luego modelar XOR con perceptrones (con pesos específicos para cada uno).
   → [Answer](#)

6. **Reto Netflix vía SVD** — Consultar el artículo *KDD Cup 2007 Task 1 Winner Report* coautorado por Miklós Kurucz y responder detalladamente cómo se logró resolver el Reto Netflix a partir de SVD. (Sugerencia: hacer un paralelo de Temas vs. Temáticas y de Temáticas vs. Películas, deducir cómo es el comportamiento de la factorización a partir de este paralelo).
   → [Answer](#)

7. **KNN** — ¿Cuál es el conjunto hipótesis del modelo de aprendizaje K Nearest Neighbours? ¿Cuál es su algoritmo de aprendizaje?
   → [Answer](#)

8. **Cotas de concentración**
   - (a) Demostración cota Markov y 1 ejemplo.
   - (b) Demostración cota Chebyshev.
   - (c) Demostrar cota de Hoeffding (suponiendo Lema de Hoeffding).
   → [Answer](#)

9. **Inequalities (learning slide 29/30)** — Responder la última pregunta: 𝜇 is the cause of 𝜈, but we can infer that 𝜇≈𝜈. ¿Por qué?
   → [Answer](#)

10. **Desigualdad de Hoeffding — control de parámetros** — A partir de la desigualdad de Hoeffding, determine, entre los parámetros ε y δ = 2Me^(−2Nε²), ¿cuál controla de mejor manera el N? (N número de datos).
    → [Answer](#)

11. **Número efectivo de rectas separadoras** — ¿Cuál es el número efectivo de líneas (rectas) para separar 5 puntos (en 2 etiquetas) en ℝ²? (Ver todas las rectas posibles que separan 2 clases compuestas por 5 puntos, discriminar los casos en los que una recta no puede separar y así encontrar el número de rectas efectivas).
    → [Answer](#)

12. **Junturas en red neuronal shallow** — ¿Cuál es el origen de las junturas en una red neuronal shallow?
    → [Answer](#)

13. **Dobleces** — ¿Cuántos dobleces puedo tener aquí? (referente a la figura adjunta)
    → [Answer](#)

---

*Repositorio mantenido para [nombre del curso/profesor] — Machine Learning.*

