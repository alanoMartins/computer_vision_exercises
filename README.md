
# Computer vision exercises

  

> Todos os exercícios podem ser feitos na linguagem desejada e usando bibliotecas como OpenCV, Tensorflow, Keras, etc

  

## 1) Optical flow e tracking

  

Selecionar uma área de um video e realizar o tracking utilizando Optical Flow. Desenhe o vetor resultante entre as localizações das features.

  

Utilizar imagens da câmera do dispositivo (notebook ou celular) local, caso não tenha acesso, baixar um vídeo de exemplo e anexar no resultado.

  
  

Exemplo output:

  

Sparse:

  

<a href="https://raw.githubusercontent.com/alanoMartins/computer_vision_exercises/master/optical_flow/output/opticalflow_dense.png"><img src="https://raw.githubusercontent.com/alanoMartins/computer_vision_exercises/master/optical_flow/output/opticalflow_dense..png"></a>

  

Dense:

  

<a href="https://raw.githubusercontent.com/alanoMartins/computer_vision_exercises/master/optical_flow/output/opticalflow_sparse.jpg"><img src="https://raw.githubusercontent.com/alanoMartins/computer_vision_exercises/master/optical_flow/output/opticalflow_sparse.jpg" width=320></a>

  
  

## 2) Image stitching

  

Utilizar descritores de imagem, como SURF, SIFT ou ORB para identificar descritores similares entre imagens e conecta-las, gerando uma única imagem.

  

Exemplo de input:

  

<a href="https://raw.githubusercontent.com/alanoMartins/computer_vision_exercises/master/image_stitching/assets/image1.jpg"><img src="https://raw.githubusercontent.com/alanoMartins/computer_vision_exercises/master/image_stitching/assets/image1.jpg" align="left" width="128"></a>

  

<a href="https://raw.githubusercontent.com/alanoMartins/computer_vision_exercises/master/image_stitching/assets/image2.jpg"><img src="https://raw.githubusercontent.com/alanoMartins/computer_vision_exercises/master/image_stitching/assets/image2.jpg" align="left" width="128"></a>

  

<a href="https://raw.githubusercontent.com/alanoMartins/computer_vision_exercises/master/image_stitching/assets/image3.jpg"><img src="https://raw.githubusercontent.com/alanoMartins/computer_vision_exercises/master/image_stitching/assets/image3.jpg" align="left" width="128"></a>

  

<a href="https://raw.githubusercontent.com/alanoMartins/computer_vision_exercises/master/image_stitching/assets/image4.jpg"><img src="https://raw.githubusercontent.com/alanoMartins/computer_vision_exercises/master/image_stitching/assets/image4.jpg" align="left" width="128"></a>

  

<a href="https://raw.githubusercontent.com/alanoMartins/computer_vision_exercises/master/image_stitching/assets/image5.jpg"><img src="https://raw.githubusercontent.com/alanoMartins/computer_vision_exercises/master/image_stitching/assets/image5.jpg" width="128"></a>

  

Exemplo output:

  

<a href="https://raw.githubusercontent.com/alanoMartins/computer_vision_exercises/master/image_stitching/output/output.png"><img src="https://raw.githubusercontent.com/alanoMartins/computer_vision_exercises/master/image_stitching/output/output.png" width="512"></a>

  
  

## 3) Object detection com deep learning

  

Detectar objetos em imagens ou vídeo utilizando um método de deep learning pre treinado com imagens do dataset ImageNet, MS COCO ou outros. Você poderá utilizar algoritmos ou adaptações já implementadas para essa atividade.

  

Justificar a escolha do modelo e apresentar seguintes resultados:

  

* Métrica de validação

* Métricas de treinamento

* Frames por segundos

  
  

Exemplo de input:

  

<a href="https://raw.githubusercontent.com/alanoMartins/computer_vision_exercises/master/object_detection/assets/input.jpeg"><img src="https://raw.githubusercontent.com/alanoMartins/computer_vision_exercises/master/object_detection/assets/input.jpeg" width="512"></a>

  
  

Exemplo output:

  

<a href="https://raw.githubusercontent.com/alanoMartins/computer_vision_exercises/master/object_detection/output/output.png"><img src="https://raw.githubusercontent.com/alanoMartins/computer_vision_exercises/master/object_detection/output/output.png" width="512"></a>



## 4) Object detection com deep learning (Avançado)

Implementar uma versão da arquitetura MnasNet ou MobileNet utilizando Python e tensorflow 2.x ou Keras para detecção de objetos treinado com o dataset ImageNet, COCOS MS ou outro. O método de detecção fica a seu critério, podendo escolher SSD, RetinaNet ou outro.

Papers:
* MnasNet: https://arxiv.org/pdf/1807.11626.pdf
* MobileNet: https://arxiv.org/pdf/1704.04861.pdf
* SSD: https://arxiv.org/pdf/1512.02325.pdf
* RetinaNet: https://arxiv.org/pdf/1708.02002.pdf

O resultado desse exercicio deverá ser:

* Imagem com os bounding boxes 
* Métrica de treinamento da rede
* Métrica de validação

Exemplo de output: 

<a href="https://raw.githubusercontent.com/alanoMartins/computer_vision_exercises/master/object_detection/output/loss.jpg"><img src="https://raw.githubusercontent.com/alanoMartins/computer_vision_exercises/master/object_detection/output/output.png" width="512"></a>

Treinamento: 
<a href="https://raw.githubusercontent.com/alanoMartins/computer_vision_exercises/master/object_detection/output/output.png"><img src="
https://raw.githubusercontent.com/alanoMartins/computer_vision_exercises/master/object_detection/output/loss.jpg" width="512"></a>

Validação: MAp: 86%


## 5) Context segmentation com deep learning (Avançado)

Implementar uma versão da arquitetura Segnet, UNet ou FCN utilizando Python e tensorflow 2.x ou Keras para segmentação de contexto treinado com um dataset publico, como PASCAL, CAMVID  ou outro. A rede / arquitetura para extração de features fica a seu critério, podendo escolher MobileNet, VGG, ResNet ou outra.

Exemplos de datasets:

* CAMVID: http://mi.eng.cam.ac.uk/research/projects/VideoRec/CamVid/
* COCOS: http://cocodataset.org/#stuff-2017
* PASCAL: https://cs.stanford.edu/~roozbeh/pascal-context/

Papers:
* Segnet: https://arxiv.org/pdf/1807.11626.pdf
* UNet: https://arxiv.org/pdf/1505.04597.pdf
* FCN: https://arxiv.org/pdf/1605.06211.pdf
* MobileNet: https://arxiv.org/pdf/1704.04861.pdf
* VGG: https://arxiv.org/pdf/1512.02325.pdf
* ResNet: https://arxiv.org/pdf/1708.02002.pdf

O resultado desse exercicio deverá ser:

* Mascara de segmentação e imagem
* Métrica de treinamento da rede
* Métrica de validação

Exemplo de output: 

<a href="https://raw.githubusercontent.com/alanoMartins/computer_vision_exercises/master/segmentation/output/loss.jpg"><img src="https://raw.githubusercontent.com/alanoMartins/computer_vision_exercises/master/segmentation/output/output.png" width="512"></a>

Treinamento: 
<a href="https://raw.githubusercontent.com/alanoMartins/computer_vision_exercises/master/object_detection/output/output.png"><img src="
https://raw.githubusercontent.com/alanoMartins/computer_vision_exercises/master/object_detection/output/loss.jpg" width="512"></a>

Validação: IoU: 0.73



