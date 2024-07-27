# IA-Generativa

## Introducción

Los modelos generativos crean nuevos datos a partir de patrones aprendidos en datos de entrenamiento existentes. Tres de los modelos más destacados son los Modelos de Lenguaje Extensos (LLM), los Autoencoders Variacionales (VAE) y las Redes Generativas Antagónicas (GAN). Con el objetivo de comprender mejor sus procesos matemáticos y brindar un enriquecido aporte durante nuestro servicio social, se desarrollaron y analizaron estos modelos utilizando herramientas básicas como Excel y numpy, sin recurrir a frameworks avanzados como TensorFlow o Keras.

## Modelos

### Autoencoders Variacionales (VAE)
Los VAE aprenden representaciones latentes de los datos a través de una arquitectura de red neuronal. 
- Se investigó el "Reparametrization Trick" para entender el proceso matemático durante la fase de backpropagation en un VAE. 
- Documentación en Excel del comportamiento matemático realizado por un modelo VAE durante el aprendizaje de una imagen tomada del dataset de números de MNIST.
- Realización del forward támbien conocida como propagación hacia adelante y el calculo de la función de perdida de ELBO
- Cálculo de nuevos pesos y sesgos para capa de la red neuronal, y repetición del proceso durante 4 iteraciones.

### Redes Generativas Antagónicas (GAN)
Las GAN enfrentan una red generativa contra una red discriminativa para generar datos realistas. 
- Investigación profunda sobre el modelo GAN (Generative Adversarial Network).
- Se creó un modelo GAN en Python usando solo numpy para comprender el proceso matemático subyacente. 
- Se realizaron pruebas del modelo junto con un amplificador de resolución para mejorar los resultados generados, permitiendo observar de cerca el aprendizaje adversarial y la mejora de la calidad de los datos generados.
- Elaboración de un documento en Látex, con la explicación detallada sobre el modelo GAN y su funcionamiento en base al código

### Modelos de Lenguaje Extensos (LLM)
Los LLM, generan texto que imita el lenguaje humano. Para entender su funcionamiento, 
- Se realizó un embedding usando solo numpy en Google Colab y se implementó la codificación posicional basada en el embedding creado. Esto permitió una comprensión más clara de cómo los modelos de lenguaje procesan y generan texto secuencialmente.
- Realización de la codificación posicional en base al Embedding previamente creado.
- Mejora de resultados del Embedding creado gracias al algoritmo Skip Gram.
- Entendimiento y codificación de los mecanismos de atención “Self attention”, “Multi head attention” y entendimiento de la normalización por capas “Layer Normalization".
- Construcción completa del transformer
