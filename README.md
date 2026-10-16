# 📊 Análise Estatística: Hábitos de Estudo e Desempenho Acadêmico

## 📌 Sobre o Projeto

Este projeto tem como objetivo explorar e analisar dados relacionados aos hábitos de estudantes e sua relação com o desempenho acadêmico, utilizando Python e bibliotecas voltadas para análise estatística e visualização de dados.

A análise considera diferentes fatores da rotina dos estudantes, como horas de estudo, tempo nas redes sociais, consumo de conteúdo na Netflix, horas de sono, frequência escolar, prática de exercícios físicos e saúde mental, buscando compreender como essas variáveis podem estar relacionadas às notas em exames.

O projeto foi desenvolvido em um Jupyter Notebook como parte da minha jornada de aprendizado em **Análise de Dados e Estatística**.

## 🎯 Objetivos

- Explorar e compreender a estrutura do conjunto de dados.
- Identificar características e padrões nos hábitos dos estudantes.
- Analisar a distribuição das notas dos exames.
- Investigar possíveis relações entre hábitos de estudo e desempenho acadêmico.
- Utilizar gráficos para facilitar a interpretação dos dados.
- Praticar conceitos de estatística descritiva e análise exploratória de dados (EDA).

## 🛠️ Tecnologias e Bibliotecas

- **Python:** linguagem utilizada para desenvolver a análise.
- **Pandas:** leitura, organização, manipulação e exploração dos dados.
- **Matplotlib:** criação e personalização de gráficos.
- **Seaborn:** visualizações estatísticas para identificar padrões e comparar variáveis.
- **Jupyter Notebook:** ambiente interativo para executar o código e documentar as análises.

## 📂 Estrutura do Projeto

```text
Projeto_2_Estatisticas/
│
├── analise.ipynb
├── student_habits_performance.csv
└── README.md
```

**Observação:** o arquivo CSV precisa estar disponível no diretório de execução do notebook para que a leitura dos dados funcione corretamente.

## 📈 Conjunto de Dados

O conjunto de dados contém **1.000 registros e 16 colunas**, com informações sobre os estudantes e seus hábitos.

Entre as principais variáveis analisadas estão:

| Variável | Descrição |
|---|---|
| `age` | Idade do estudante |
| `gender` | Gênero |
| `study_hours_per_day` | Horas de estudo por dia |
| `social_media_hours` | Tempo diário nas redes sociais |
| `netflix_hours` | Tempo dedicado à Netflix |
| `part_time_job` | Indica se o estudante possui trabalho de meio período |
| `attendance_percentage` | Percentual de frequência escolar |
| `sleep_hours` | Horas de sono |
| `diet_quality` | Qualidade da alimentação |
| `exercise_frequency` | Frequência de exercícios físicos |
| `parental_education_level` | Nível de escolaridade dos responsáveis |
| `internet_quality` | Qualidade da conexão com a internet |
| `mental_health_rating` | Avaliação de saúde mental |
| `extracurricular_participation` | Participação em atividades extracurriculares |
| `exam_score` | Nota obtida no exame |

A coluna `student_id` identifica cada registro de estudante.

## 🔍 Etapas da Análise

### 1. Importação das bibliotecas

Importação das ferramentas necessárias para manipular os dados e construir visualizações estatísticas.

### 2. Carregamento dos dados

Leitura do arquivo CSV utilizando Pandas e visualização dos registros por meio de um DataFrame.

### 3. Exploração inicial

Verificação da estrutura do conjunto de dados, dos tipos de variáveis, da quantidade de registros e da presença de valores ausentes.

### 4. Análise estatística e visualização

Utilização de gráficos estatísticos para explorar a distribuição das notas e comparar o desempenho acadêmico com diferentes características dos estudantes.

### 5. Investigação de padrões

Exploração de possíveis associações entre desempenho acadêmico, horas de estudo, frequência escolar, sono, saúde mental, alimentação e prática de exercícios físicos.

### 6. Interpretação dos dados

Análise dos padrões observados nas visualizações, considerando as limitações dos dados e a diferença entre associação estatística e causalidade.

## ⚙️ Como Executar o Projeto

### Pré-requisitos

- Python 3 instalado.
- Jupyter Notebook ou Visual Studio Code com suporte a notebooks.
- Arquivo `student_habits_performance.csv`.

### 1. Clone o repositório

```bash
git clone https://github.com/YanMoreira04/Projeto_2_Estatisticas.git
```

### 2. Acesse a pasta do projeto

```bash
cd Projeto_2_Estatisticas
```

### 3. Instale as bibliotecas

```bash
pip install pandas matplotlib seaborn jupyter
```

### 4. Execute o notebook

Inicie o Jupyter Notebook:

```bash
jupyter notebook
```

Abra o arquivo `analise.ipynb` e execute as células em sequência.

**Importante:** mantenha o arquivo CSV na pasta de execução ou ajuste o caminho informado na função `pd.read_csv()`.

## 💡 Aprendizados

Com este projeto, pratiquei conceitos importantes para a área de dados:

- Manipulação e exploração de dados com Pandas.
- Inspeção de DataFrames e identificação de valores ausentes.
- Análise de variáveis numéricas e categóricas.
- Criação de gráficos estatísticos com Matplotlib e Seaborn.
- Investigação de relações entre diferentes variáveis.
- Interpretação de informações para transformar dados em conhecimento.

## 🚀 Próximos Passos

Como possibilidades de evolução do projeto, pretendo explorar:

- Tratamento e padronização de valores ausentes.
- Análise de correlação entre variáveis numéricas.
- Comparação estatística entre diferentes grupos de estudantes.
- Criação de um dashboard interativo com Power BI ou outra ferramenta de visualização.
- Desenvolvimento de novas análises para aprofundar a investigação sobre o desempenho acadêmico.

## 👨‍💻 Autor

**Yan Moreira**

Estudante de Engenharia de Software, com formação em Análise e Desenvolvimento de Sistemas e interesse em Análise de Dados, Engenharia de Dados, Inteligência Artificial e Automação.

🔗 **GitHub:** [YanMoreira04](https://github.com/YanMoreira04)

🔗 **Repositório do projeto:** [Projeto_2_Estatisticas](https://github.com/YanMoreira04/Projeto_2_Estatisticas)

---

⭐ Se este projeto despertou seu interesse, fique à vontade para explorar o repositório!
