# Dimensionalidade de Imagens 📐
Bem vindo ao meu estudo sobre dimensionalidade de imagens! <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Hand%20gestures/Waving%20Hand.png" alt="Waving Hand" width="25" height="25" />

Nesse desafio do bootcamp, foi proposto que aplicássemos filtros para pré-processar imagens. Mas, eu fui um pouco além, a motivo de curiosidade, para ver como um modelo de classificação de imagens se sairia tendo o dataset de treinamento pré-processado de maneiras diferentes.

## 🛠️ Tecnologias Utilizadas

1. **Linguagem de Programação:**
   - ![Python](https://img.shields.io/badge/-Python-333?style=flat&logo=python&logoColor=white) Python

2. **Bibliotecas e Frameworks:**
   - ![TensorFlow](https://img.shields.io/badge/-TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white) TensorFlow
   - ![Keras](https://img.shields.io/badge/-Keras-D00000?style=flat&logo=keras&logoColor=white) Keras
   - ![NumPy](https://img.shields.io/badge/-NumPy-013243?style=flat&logo=numpy&logoColor=white) NumPy
   - ![Matplotlib](https://img.shields.io/badge/-Matplotlib-11557C?style=flat&logo=matplotlib&logoColor=white) Matplotlib
   - ![scikit-learn](https://img.shields.io/badge/-scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white) scikit-learn
   - ![Pillow](https://img.shields.io/badge/-Pillow-333?style=flat&logo=pillow&logoColor=white) Pillow
   - ![Requests](https://img.shields.io/badge/-Requests-333?style=flat&logo=python&logoColor=white) Requests

3. **Outras Ferramentas:**
   - ![Google Drive](https://img.shields.io/badge/-Google%20Drive-4285F4?style=flat&logo=google-drive&logoColor=white) para armazenamento de arquivos.
   - ![Google Colab](https://img.shields.io/badge/-Google%20Colab-F9AB00?style=flat&logo=google-colab&logoColor=white) para desenvolvimento e execução do notebook.

## 📑 Tópicos Abordados

1. **🧩 O que é Redução de Dimensionalidade**
   - Um breve texto explicando o que é e o porquê dessa técnica.
  
2. **🖼️ Carregar imagem da internet**
   - Criar funções para carregar uma imagem da internet e mostrar ela e seu tamanho em bytes no colab.

4. **🔳 Filtro de Tons de Cinza**
   - Desenvolver uma função para aplicar o filtro de escala de cinza em uma imagem.

5. **📊 PCA (Principal Component Analysis)**
   - Desenvolver uma função para aplicar a técnica de PCA em uma imagem.
    
7. **Treinando o modelo**
   - Sem pré-processamento
   - Aplicando a escala de cinza
   - Aplicando o método PCA
  
6. **📕 Conclusão**
   - O que pode ser aprendido desse estudo.
   
8. **🔗 Referências**
   - Os sites usados de inspiração para o estudo.

## ✅ Resultados
Foi observado que ao converter uma imagem para a escala de cinza seu tamanho diminui cerca de 3 vezes! Mas aplicando a técnica PCA, o tamanho não muda.

Esse foi o resultado obtido ao treinar um modelo de classificação com diferentes técnicas de pré-processamento:
|<p align="center">Técnica</p>|<p align="center">Tempo de Treinamento (s)</p>|<p align="center">Acurácia</p>|
|----------------------------------------|-----------------------------------------------|--------------------------------|
| <p align="center">Sem pré-processamento</p> | <p align="center">11.9561</p>               | <p align="center">0.3392568659127625</p> |
| <p align="center">Com escala de cinza</p>  | <p align="center">7.57</p>                  | <p align="center">0.6639741518578353</p> |
| <p align="center">Com PCA</p>          | <p align="center">23.2667</p>                | <p align="center">0.6397415185783522</p> |

## :eyes: Confira os detalhes
Confira em detalhes como esses resultados foram obtidos no meu notebook: [Redução de Dimensionalidade](https://colab.research.google.com/drive/19PfZsRwThQstkUR1MMQ5xydq8wvAGYno?usp=sharing).
