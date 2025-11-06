# Replicação do DLIR: Deep Learning of Dynamic POI Generation and Optimisation for Itinerary Recommendation

Este repositório contém a replicação do código original do modelo DLIR, proposto no artigo *"Deep Learning of Dynamic POI Generation and Optimisation for Itinerary Recommendation"*.

O código foi replicado a partir do [repositório original](https://github.com/sajalhalder/DLIR) disponibilizado pelos autores.

## 🎯 Sobre o Projeto

A replicação busca reproduzir o funcionamento do modelo *deep learning* para recomendação de itinerários, que considera o interesse dinâmico do usuário, padrões espaciais complexos e tempos de fila entre Pontos de Interesse (POIs).

Este código serviu de base para um estudo comparativo onde o modelo DLIR foi comparado com abordagens *shallow* (aprendizado raso).

## ✨ Modelos e algoritmos implementados

* **Arvore de Decisão**
* **Random Forest**
* **Regressão Logistica**
* **LightGBM**
* **XGBoost**


## 🛠️ Instalação

Recomenda-se criar um ambiente virtual (por exemplo, com `venv` ou `conda`) para isolar as dependências.

1.  Clone o repositório:
    ```bash
    git clone [https://github.com/SEU-USUARIO/SEU-REPOSITORIO.git](https://github.com/SEU-USUARIO/SEU-REPOSITORIO.git)
    cd SEU-REPOSITORIO
    ```

2.  Crie e ative um ambiente virtual (exemplo com `venv`):
    ```bash
    python -m venv venv
    source venv/bin/activate  # No Windows: .\venv\Scripts\activate
    ```

3.  Instale os pacotes necessários. Você pode criar um arquivo `requirements.txt` com o conteúdo abaixo e executar `pip install -r requirements.txt`.

    **requirements.txt**
    ```txt
    tensorflow==2.4.1
    pandas==1.2.2
    ```

## 🚀 Como Usar

O script principal para treinar e avaliar o modelo é o `main.py`.

```bash
# Comando para executar o treinamento/avaliação
python main.py
