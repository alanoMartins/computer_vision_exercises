# Computer vision exercises

> Todos os exercícios podem ser feitos na linguagem desejada e usando bibliotecas como OpenCV, Tensorflow, Keras, etc

##  1) Optical flow e tracking

Selecionar uma área de um video e realizar o tracking utilizando Optical Flow. Desenhe o vetor resultante entre as localizações das features.

Utilizar imagens da câmera do dispositivo (notebook ou celular) local, caso não tenha acesso, baixar um vídeo de exemplo e anexar no resultado.


Exemplo output:

Sparse:

<a href="https://raw.githubusercontent.com/alanoMartins/computer_vision_exercises/master/optical_flow/output/opticalflow_dense.png"><img src="https://raw.githubusercontent.com/alanoMartins/computer_vision_exercises/master/optical_flow/output/opticalflow_dense..png"></a>

Dense:

<a href="https://raw.githubusercontent.com/alanoMartins/computer_vision_exercises/master/optical_flow/output/opticalflow_sparse.jpg"><img src="https://raw.githubusercontent.com/alanoMartins/computer_vision_exercises/master/optical_flow/output/opticalflow_sparse.jpg" width=320></a>


## 2) Image stitching

Utilizar descritores de imagem, como SURF, SIFT ou ORB para identificar descritores similares entre imagens e conecta-las, gerando uma unica imagem.

Exemplo de input:

<a href="https://raw.githubusercontent.com/alanoMartins/computer_vision_exercises/master/image_stitching/assets/image1.jpg"><img src="https://raw.githubusercontent.com/alanoMartins/computer_vision_exercises/master/image_stitching/assets/image1.jpg" align="left" width="128"></a>

<a href="https://raw.githubusercontent.com/alanoMartins/computer_vision_exercises/master/image_stitching/assets/image2.jpg"><img src="https://raw.githubusercontent.com/alanoMartins/computer_vision_exercises/master/image_stitching/assets/image2.jpg" align="left" width="128"></a>

<a href="https://raw.githubusercontent.com/alanoMartins/computer_vision_exercises/master/image_stitching/assets/image3.jpg"><img src="https://raw.githubusercontent.com/alanoMartins/computer_vision_exercises/master/image_stitching/assets/image3.jpg" align="left" width="128"></a>

<a href="https://raw.githubusercontent.com/alanoMartins/computer_vision_exercises/master/image_stitching/assets/image4.jpg"><img src="https://raw.githubusercontent.com/alanoMartins/computer_vision_exercises/master/image_stitching/assets/image4.jpg" align="left" width="128"></a>

<a href="https://raw.githubusercontent.com/alanoMartins/computer_vision_exercises/master/image_stitching/assets/image5.jpg"><img src="https://raw.githubusercontent.com/alanoMartins/computer_vision_exercises/master/image_stitching/assets/image5.jpg" width="128"></a>

Exemplo output:

<a href="https://raw.githubusercontent.com/alanoMartins/computer_vision_exercises/master/image_stitching/output/output.png"><img src="https://raw.githubusercontent.com/alanoMartins/computer_vision_exercises/master/image_stitching/output/output.png" width="512"></a>


## 3) Object detection com deep learning

Detectar objetos em imagens ou vídeo utilizando um método de deep learning pre treinado com imagens do dataset ImageNet, MS COCO ou outros.

Justificar a escolha do modelo e apresentar seguintes resultados:

* Métrica de validação
* Métricas de treinamento
* Frames por segundos


Exemplo de input:

<a href="https://raw.githubusercontent.com/alanoMartins/computer_vision_exercises/master/object_detection/assets/input.jpeg"><img src="https://raw.githubusercontent.com/alanoMartins/computer_vision_exercises/master/object_detection/assets/input.jpeg" width="512"></a>


Exemplo output:

<a href="https://raw.githubusercontent.com/alanoMartins/computer_vision_exercises/master/object_detection/output/output.png"><img src="https://raw.githubusercontent.com/alanoMartins/computer_vision_exercises/master/object_detection/output/output.png" width="512"></a>



