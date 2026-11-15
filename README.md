# 📊 Introdução à Ciência de Dados com Python

Repositório oficial contendo o notebook prático e a base de dados utilizados no minicurso de **Introdução à Ciência de Dados com Python**, ministrado na **Universidade Federal de Rondônia (UNIR)**.

---

## 🎯 Sobre o Minicurso

Esta capacitação teve como objetivo introduzir estudantes de graduação e público externo ao fluxo real de trabalho em **Ciência de Dados**, partindo da compreensão estratégica do papel do profissional de dados até a implementação prática de coleta, saneamento, estatística descritiva e visualização de dados utilizando Python.

### 🧠 Conceitos Abordados na Apresentação
* **Fundamentos de Ciência de Dados:** A interseção entre Computação, Estatística e Conhecimento de Negócio.
* **Rotina Profissional e Mercado:** O ciclo de vida de projetos de dados, a importância do saneamento (que representa cerca de 80% do trabalho) e o impacto da tomada de decisão orientada a evidências (*Data-Driven*).
* **Prática Guiada:** Aplicação completa sobre o catálogo da Netflix (`NetFlix.csv`) e desafio prático autônomo utilizando dados do Spotify.

---

## 🔍 Etapas Desenvolvidas no Notebook (`minicurso-de-ciencia-de-dados.ipynb`)

O código do projeto está organizado em **5 etapas sequenciais** sobre a base `NetFlix.csv` (composta por **7.787 títulos** entre filmes e séries):

1. **Importação das Bibliotecas:** Configuração do ambiente analítico com `pandas` (manipulação tabular), `numpy` (cálculo vetorial), `seaborn` e `matplotlib` (visualização gráfica).
2. **Carga e Diagnóstico Inicial:** Leitura do arquivo CSV e inspeção estrutural para identificar tipos de dados, amostras de registros e mapeamento de valores ausentes (`NaN`) nas 12 colunas da base.
3. **Saneamento e Filtragem (Data Cleaning):**
   * Imputação de valores nulos nas colunas de país, diretor, elenco, data de adição e classificação indicativa com rótulos descritivos padronizados, garantindo a preservação integral dos registros.
   * Filtragem booleana e criação de cópia segura do subconjunto contendo exclusivamente os **5.377 filmes** do catálogo.
4. **Estatística Descritiva Vetorial com NumPy:** Extração da coluna de duração dos filmes para um *array* unidimensional NumPy, obtendo de forma instantânea:
   * **Média de duração:** 99,3 minutos.
   * **Mediana de duração:** 98,0 minutos (indicando distribuição equilibrada sem forte distorção por extremos).
   * **Percentil 90:** 133,0 minutos (90% dos filmes da plataforma duram até 2h13min).
5. **Visualização de Dados (Data Storytelling):** Geração de gráfico de contagem categórica comparando diretamente a proporção do catálogo entre **Filmes (5.377 títulos — ~69%)** e **Séries de TV (2.410 títulos — ~31%)**.

---

## 📁 Estrutura do Repositório

* `minicurso-de-ciencia-de-dados.ipynb` — Notebook completo executado durante o minicurso.
* `NetFlix.csv` — Base de dados do catálogo da Netflix (7.787 registros).
* `README.md` — Documentação técnica do projeto.

---

## 🚀 Como Executar

1. Faça o clone deste repositório ou baixe os arquivos diretamente.
2. Instale as bibliotecas necessárias no seu ambiente Python (`pandas`, `numpy`, `seaborn`, `matplotlib` e `jupyter`).
3. Abra o arquivo `minicurso-de-ciencia-de-dados.ipynb` no **Jupyter Notebook**, **VS Code**, **Kaggle Notebooks** ou **Google Colab**.
4. Caso execute fora do ambiente Kaggle, ajuste o caminho de leitura do arquivo CSV para apontar diretamente para o diretório onde salvou o `NetFlix.csv`.

---

## 👨‍💻 Ministrante

**Carlos Eduardo Evangelista dos Santos**  
Graduando em Ciência da Computação — Universidade Federal de Rondônia (UNIR)  
Pesquisador PIBIC na área de Engenharia e Pipelines de Dados.

* 🔗 **GitHub:** [CarlosEduDev](https://github.com/CarlosEduDev)
* 🎓 **Currículo Lattes:** *http://lattes.cnpq.br/7648810465510265*
* 💼 **LinkedIn:** *https://www.linkedin.com/in/carlos-eduardo-evangelista/*
