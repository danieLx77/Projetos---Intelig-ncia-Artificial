# Projetos de Inteligência Artificial

Este repositório reúne os trabalhos práticos da disciplina de Inteligência Artificial.

A proposta e documentar cada projeto de forma organizada, mantendo código, notebooks e análises no mesmo lugar.

## Projetos disponíveis


### 01 - Classificação com KNN

Implementação e avaliação do algoritmo KNN com a base Iris, incluindo:

- versão manual (hardcore);
- versão com Scikit-learn;
- comparação de desempenho por métricas e matriz de confusão.

Pasta do projeto: [KNN](KNN/)

### 02 - Clusterização com K-means

Implementação e análise do algoritmo K-means na base Iris, contemplando:

- versão manual (hardcore);
- versão com Scikit-learn;
- avaliação por Silhouette Score, tempo de execução e visualização dos clusters (PCA);
- comparação detalhada entre as abordagens.

Pasta do projeto: [K-MEANS](K-MEANS/)

### 03 - Classificação com MLPClassifier

Implementação e avaliação do classificador MLP (Perceptron Multicamadas) nas bases Iris e Wine, incluindo:

- normalização dos dados com StandardScaler;
- métricas de avaliação e matriz de confusão;
- comparação com o KNN (Trabalho Prático 01).

Pasta do projeto: [MLPC](MLPC/)

### 04 - Jogo dos Oito

Implementação e comparação de algoritmos de busca para resolver o problema clássico do Jogo dos Oito, incluindo:

- representação do tabuleiro como espaço de estados;
- geração dos movimentos possíveis a partir do espaço vazio;
- busca cega em largura (BFS);
- busca informada A* com heurística da Distância de Manhattan;
- comparação de desempenho por quantidade de movimentos, nós explorados e tempo de execução.

Pasta do projeto: [JOGO_8](JOGO_8/)

## Ambiente virtual

Recomenda-se utilizar uma `venv` local e instalar as dependências listadas em `requirements.txt`.

Fluxo recomendado no Windows:

1. Criar a venv na raiz do projeto:

```powershell
python -m venv .venv
```

2. Ativar a venv:

```powershell
.venv\Scripts\Activate.ps1
```

3. Instalar as dependências:

```powershell
pip install -r requirements.txt
```

4. No VS Code, selecionar o interpretador da pasta `.venv` para abrir e executar os notebooks.

Fluxo recomendado no Linux:

1. Criar a venv na raiz do projeto:

```bash
python3 -m venv .venv
```

2. Ativar a venv:

```bash
source .venv/bin/activate
```

3. Instalar as dependências:

```bash
pip install -r requirements.txt
```

4. No VS Code, selecionar o interpretador da pasta `.venv` para abrir e executar os notebooks.

## Colaboradores

- Daniel de Jesus Moreira
- João Guilherme Santos Ribeiro

---

_Atualizado em: 26/05/2026_