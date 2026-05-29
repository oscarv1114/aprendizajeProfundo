# Ejercicios Prácticos de Aprendizaje Profundo
**Autor:** Oscar Vergara

---

## Ejercicio 1: Red Neuronal Densa (MLP) para Clasificación de Imágenes

### Descripción
Se implementa un perceptrón multicapa (MLP) en PyTorch para clasificar imágenes del dataset Intel Image Classification en 6 categorías: buildings, forest, glacier, mountain, sea y street. Las imágenes se convierten a escala de grises y se redimensionan a 150×150 px antes de ingresarlas a la red, produciendo vectores de entrada de 22,500 dimensiones.

---

## Ejercicio 2: Clasificación de imágenes en Tiny ImageNet

### Descripción
Tiny ImageNet es un subconjunto de ImageNet reducido a 200 clases, con imágenes de 64×64 píxeles. El objetivo es entrenar un clasificador que asigne correctamente cada imagen a una de esas 200 categorías, utilizando transfer learning sobre un modelo preentrenado en ImageNet completo.

---

## Ejercicio 3: Implementación de RNNs/GRUs para modelar dependencias temporales en datos secuenciales

### Descripción
Se implementó una red neuronal recurrente GRU en PyTorch para modelar dependencias temporales en datos secuenciales de demanda horaria de bicicletas. Los datos fueron normalizados y organizados en secuencias de 24 horas. La arquitectura utiliza una capa GRU con 64 unidades ocultas, Dropout (p=0.2) y una capa lineal de salida. El entrenamiento empleó Adam (lr=0.001), MSELoss, batch size de 256 y hasta 150 épocas, incorporando EarlyStopping, scheduler dinámico y gradient clipping.

---

## Ejercicio 4: [Ejercicio Pendiente]

### Descripción
Ejercicio Pendiente
