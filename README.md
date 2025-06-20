# Previsão de Preços Imobiliários com Rede Neural

Este projeto utiliza uma rede neural artificial (ANN) para prever preços de imóveis com base em dados do famoso dataset "House Prices" do Kaggle. O objetivo é demonstrar um pipeline completo de machine learning, desde o pré-processamento até a avaliação e visualização dos resultados.

## Funcionalidades

- **Pré-processamento de dados:** tratamento de valores ausentes, codificação de variáveis categóricas e padronização.
- **Construção e treinamento de rede neural:** arquitetura customizável com camadas densas e regularização (Dropout, EarlyStopping).
- **Avaliação do modelo:** métricas como MAE, MSE e R².
- **Visualização:** gráficos de desempenho, resíduos e estrutura da rede.
- **Código comentado e didático.**

## Como usar

1. **Clone o repositório:**
   ```sh
   git clone https://github.com/weltondionisio/rede_neural_previsao_imoveis.git
   cd rede_neural_previsao_imoveis
   ```

2. **Instale as dependências:**
   ```sh
   pip install -r requirements.txt
   ```
   Ou instale manualmente:
   ```sh
   pip install tensorflow pandas numpy matplotlib seaborn scikit-learn kagglehub
   ```

3. **Execute o notebook:**
   - Abra o arquivo `rede_neural.ipynb` no VS Code ou Jupyter Notebook.
   - Siga as células sequencialmente.

4. **(Opcional) Baixe o dataset do Kaggle:**
   - O notebook já faz o download automático via `kagglehub`.

## Estrutura do Projeto

- `rede_neural.ipynb` — Notebook principal com todo o pipeline.
- `model_nn.png` — Visualização estrutural da rede neural (gerada pelo notebook).
- `requirements.txt` — Dependências do projeto.

## Resultados

O modelo atinge bons resultados de previsão, com métricas de erro e gráficos de desempenho apresentados ao final do notebook.

## Observações

- O projeto é didático e pode ser expandido para outras arquiteturas ou técnicas de regressão.
- Para visualizar a estrutura da rede, utilize a célula com `plot_model`.

## Autor

[Welton Dionisio](https://github.com/weltondionisio)

---

Sinta-se à vontade para abrir issues
