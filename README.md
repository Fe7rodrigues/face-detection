# Face Detection

Este projeto é um notebook Jupyter que demonstra como utilizar a biblioteca OpenCV para realizar a detecção de rostos em imagens e vídeos.

O objetivo deste projeto é fornecer um exemplo simples de como utilizar a detecção de rostos em um projeto de visão computacional. A detecção de rostos é um recurso importante em várias aplicações, incluindo reconhecimento de faces, segurança, detecção de expressões faciais e muito mais.

O código está escrito em Python e utiliza a biblioteca OpenCV. O projeto está dividido em duas seções: detecção de rostos em imagens e detecção de rostos em vídeo.

## Linguagens e Ferramentas Utilizadas

- Python
- Google Colab

## Bibliotecas e Requisitos Necessários

- `imutils`: utilizada para redimensionamento e rotação da imagem.
- `numpy`: responsável por trabalhos matemáticos como vetores e matrizes das imagens.
- `opencv-python`: utilizado para ajudar no processo de detecção da face.
- `google.colab.patches.cv2_imshow`: dependência do Google Colab para trabalhar com imagens.
- `IPython.display.display`, `IPython.display.Javascript`: bibliotecas necessárias para trabalhar com a leitura da webcam.
- `google.colab.output.eval_js`: dependência do Google Colab para trabalhar com leitura da webcam.
- `base64.b64decode`: utilizada para codificar dados binários.

Para utilizar este projeto, é necessário ter o Google Colab instalado e ter as bibliotecas acima instaladas no ambiente Python. A biblioteca `opencv-python` pode ser instalada utilizando o gerenciador de pacotes pip:



## Detecção de Rostos em Imagens

A seção de detecção de rostos em imagens contém o código necessário para carregar uma imagem, detectar os rostos presentes na imagem e desenhar um retângulo em volta de cada rosto detectado. Para executar esta seção do projeto, basta carregar uma imagem de sua escolha e executar as células do notebook.

## Detecção de Rostos em Vídeo

A seção de detecção de rostos em vídeo contém o código necessário para capturar imagens de uma câmera de vídeo em tempo real, detectar os rostos presentes em cada imagem e desenhar um retângulo em volta de cada rosto detectado. Para executar esta seção do projeto, basta executar as células do notebook.

## Como Executar o Código

Para executar o código deste projeto, é necessário ter o Jupyter Notebook instalado e ter a biblioteca OpenCV instalada no ambiente Python. É possível instalar o Jupyter Notebook utilizando a distribuição Anaconda. Para instalar a biblioteca OpenCV, basta utilizar o gerenciador de pacotes pip:


## Conclusão

Este projeto é um exemplo simples de como utilizar a detecção de rostos em um projeto de visão computacional. A detecção de rostos é uma técnica importante em várias aplicações e pode ser utilizada em conjunto com outras técnicas para criar sistemas mais avançados de visão computacional.
