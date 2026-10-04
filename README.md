# Processamento de Linguagem Natural (PLN)
## Resolução da Tarefa PC.19: Treebanks da Língua Portuguesa

**Professor:** Fabrício Galende Marques de Carvalho  
**Atividade:** PC.19  

---

### 📌 Enunciado da Tarefa

> **PC.19.** Selecione ao menos 2 Treebanks da língua portuguesa e demonstre a instalação de eventuais pacotes, seu carregamento e utilização.

---

### 📂 Treebanks Selecionados

Para a resolução desta tarefa, foi utilizado o ecossistema do **NLTK (Natural Language Toolkit)** em Python, explorando dois dos principais recursos da língua portuguesa:

1. **Mac-Morpho:**
   - Corpus composto por mais de 1 milhão de palavras extraídas de textos jornalísticos da *Folha de S. Paulo* (1994).
   - Amplamente utilizado no treinamento e avaliação de etiquetadores morfossintáticos (*Part-of-Speech* / POS Tagging) para o português do Brasil.

2. **Floresta Sintática:**
   - Treebank desenvolvido no âmbito do projeto *Linguateca*.
   - Contém textos em português do Brasil e de Portugal com anotação sintática profunda em formato de árvore (*parse trees* / constituintes e dependências), além de marcação morfossintática.

---

### 🛠️ Pré-requisitos e Instalação

#### 1. Dependências do Python
Certifique-se de ter o Python 3 instalado. Instale os pacotes necessários via pip:

```bash
pip install nltk jupyter
```

#### 2. Download dos Recursos no NLTK
No código Python ou Jupyter Notebook, faça o download dos corpora:

```python
import nltk
nltk.download('mac_morpho')
nltk.download('floresta')
```

---

### 🚀 Como Executar

Abra o notebook [`Resolucao_PC19.ipynb`](./Resolucao_PC19.ipynb) utilizando o Jupyter Notebook, JupyterLab ou a extensão Jupyter do VS Code:

```bash
jupyter notebook Resolucao_PC19.ipynb
```

Execute as células em sequência para conferir:
- O download e a inicialização dos pacotes;
- Estatísticas do **Mac-Morpho** (total de palavras, sentenças e distribuição das 5 classes gramaticais mais frequentes);
- Exploração da **Floresta Sintática** (palavras etiquetadas e exibição da estrutura em árvore de sentenças analisadas).

---

### 📁 Estrutura do Diretório

```text
├── Resolucao_PC19.ipynb   # Notebook Jupyter com a resolução prática da tarefa
├── README.md              # Documentação da atividade
├── Tarefas PLN.pdf        # Relação de tarefas práticas da disciplina
└── pln_introduction.pdf   # Material teórico introdutório de PLN
```
