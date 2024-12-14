# Image-Recommendation

Este projeto utiliza aprendizado profundo para construir um sistema de recomendação baseado em similaridade de imagens, com uso de TensorFlow e TensorFlow Hub. As imagens são organizadas e processadas para extrair recursos e realizar recomendações. 
<br>
<br>

## Funcionalidades

- **Download e organização de dados:**  
  Automatiza o download, extração e organização de imagens por categorias.  
- **Treinamento do modelo:**  
  Utiliza um modelo pré-treinado do TensorFlow Hub para transfer learning.  
- **Extração de recursos:**  
  Gera embeddings das imagens para cálculo de similaridade.  
- **Sistema de recomendação:**  
  Recomendação baseada em similaridade usando o índice Annoy.  

## Resultados

- **Treinamento:**  
  Métricas de acurácia e perda disponíveis nos gráficos.
  
- **Recomendação:**  
  Retorna as 5 imagens mais similares a uma imagem de entrada.
