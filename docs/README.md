## [ Segmentación de Clientes](https://github.com/a-jimenezc/segmentacion_de_clientes "Clic para acceder al repositorio")

* El objetivo del presente trabajo es segmentar a los clientes de un supermercado en un número reducido de grupos, esto a partir de información obtenida a través de las tarjetas de membresía.
* Para ello, tres algoritmos de agrupamiento distintos fueron implementados: K-means, HDBSCAN y Gaussian Mixture Model. En cada caso,  se determinaron los mejores hiperparámetros. Se utilizó la biblioteca Scikit-learn para K-means y GMM, mientras que para el algoritmo HDBSCAN se utilizó la implementación provista por la biblioteca hdbscan. 
* Se usaron diversas métricas para determinar los hiperparámetros. Entre ellas está la métrica de la silueta, la inercia (elbow curve) y la métrica BIC (Bayesian Information Criterion). 
* Luego, se comparó el desempeño de los mejores modelos de cada algoritmo y se seleccionó el mejor de ellos. 
<p align="center">
<img src="images1/comparison.png" alt="Alt text 1" width="400"/>
</p>
* Adicionalmente, se inspeccionó visualmente el resultado para el mejor model.
<p align="center">
<img src="images1/result1.png" alt="Alt text 1" width="300"/> <img src="images1/result2.png" alt="Alt text 2" width="300"/>
</p>
* Finalmente, se guardaron los datos con la nueva columna de etiquetas.


## [ Predicción de Enfermedad Cardiaca con Redes Neuronales](https://github.com/a-jimenezc/Prediccion_de_enfermedad_cardiaca "Clic para acceder al repositorio")

* El objetivo de este proyecto es entrenar una Red Neuronal que permita predecir si un paciente presenta un cuadro de enferemedad de arterias coronarias.
* Para ello, se probaron tres variaciones del algoritmo MLP (Multilayer Perceptron): primero con una, luego con dos y finalmente con tres capas ocultas. En cada caso, se utilizó "Grid Seach" con "Cross-Validation" para seleccionar los hiperparámetros más óptimos. 
* Luego, se comparó el desempeño de los mejores modelos para cada variación del algoritmo y se seleccionó el mejor de ellos. 
* Finalmente, se aplicó la técnica de permutación para poder identificar las variables más importantes para el modelo y poder así interpretar el mismo.

<p align="center">
<img src="images/scores1.png" alt="Alt text 1" width="400"/>  <img src="images/imprtances_test.png" alt="Alt text 2" width="400"/>
</p>
 
