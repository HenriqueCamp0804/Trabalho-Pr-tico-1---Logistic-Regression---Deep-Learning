# Trabalho-Pratico-1---Logistic-Regression---Deep-Learning

Classificador de Imagens com Regressão Logística

Este projeto consiste na implementação de um algoritmo de **Regressão Logística para classificação binária de imagens**, construído do zero utilizando apenas Python e NumPy. O objetivo é criar um modelo capaz de diferenciar imagens de **gatos** e **não-gatos**.

Este trabalho foi desenvolvido como um exercício prático para solidificar os conceitos fundamentais por trás das redes neurais e do processo de treinamento de um modelo de machine learning.

🧠 Conceitos Abordados

O notebook percorre todas as etapas essenciais para a construção de um classificador, incluindo:

-   **Carregamento de Dados:** Leitura de datasets no formato `.h5`.
-   **Pré-processamento de Imagens:** Redimensionamento, achatamento (flattening) e normalização dos dados.
-   **Inicialização de Parâmetros:** Criação dos vetores de pesos `w` e bias `b`.
-   **Função de Ativação:** Implementação da função Sigmoid.
-   **Forward Propagation:** Cálculo das previsões e da função de custo (Entropia Cruzada Binária).
-   **Backward Propagation:** Cálculo dos gradientes para a otimização.
-   **Gradiente Descendente:** Implementação do loop de otimização para treinar o modelo e minimizar o custo.
-   **Avaliação:** Medição da acurácia do modelo nos conjuntos de treino e teste.
-   **Previsão:** Uso do modelo treinado para classificar uma nova imagem fornecida pelo usuário.

 🛠️ Tecnologias Utilizadas

-   **Python 3**
-   **NumPy:** Para todas as operações matemáticas e manipulação de vetores.
-   **Matplotlib:** Para visualização das imagens e gráficos.
-   **h5py:** Para carregar os dados do dataset.
-   **Pillow (PIL):** Para o processamento da imagem final de teste.
-   **Jupyter Notebook / Google Colab:** Como ambiente de desenvolvimento.

🚀 Como Executar

1.  Clone este repositório:
    ```bash
    git clone [https://github.com/SEU-USUARIO/NOME-DO-REPOSITORIO.git](https://github.com/SEU-USUARIO/NOME-DO-REPOSITORIO.git)
    ```
2.  Abra o arquivo `.ipynb` no Jupyter Notebook ou Google Colab.
3.  Execute as células em ordem sequencial.
4.  Para a última parte (teste com uma imagem própria), faça o upload de uma imagem para o ambiente e atualize a variável `image_path` com o caminho correspondente.

---
