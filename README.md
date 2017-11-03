# Red Neuronal Perceptron AND
Red Neuronal (Perceptron): AND
Implementado en Python

  umbral = 0.5
  tasa_de_aprendizaje = 0.1
  pesos=[0,0]
  conjunto_de_entrenamiento = [((0,0), 0), ((0,1), 0), ((1,0), 0), ((1,1), 1)]

  perceptronAND=PerceptronAND()
  perceptronAND.establecerConjuntoEntrenamiento(conjunto_de_entrenamiento)
  perceptronAND.establecerPesos(pesos)
  perceptronAND.establecerUmbral(umbral)
  perceptronAND.establecerTasaDeAprendizaje(tasa_de_aprendizaje)
  perceptronAND.entrenarRed()
  perceptronAND.imprimirPesos()

  #probando la red neuronal
  print perceptronAND.sumarEntradasYPesos((1,1))>umbral
