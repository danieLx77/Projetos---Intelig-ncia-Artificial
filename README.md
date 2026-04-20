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

_Atualizado em: 04/04/2026_