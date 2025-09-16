# 📚 Projeto: Análise de Empréstimos do Sistema de Bibliotecas da UFRN

Este projeto, desenvolvido como parte do desafio **#7DaysOfCode** da **Alura**, foi uma imersão prática em **análise exploratória de dados (AED)** usando **Python** e a biblioteca **Pandas**. O objetivo principal foi extrair, limpar e analisar dados de empréstimos das bibliotecas da UFRN para identificar padrões e gerar insights estratégicos para a gestão do acervo.

As principais etapas do projeto incluíram a manipulação de dados de múltiplas fontes, a criação de visualizações informativas e a geração de relatórios estilizados, prontos para a tomada de decisões.

---

## 🛠️ Habilidades e Ferramentas

* **Linguagem de Programação:** Python
* **Bibliotecas de Análise:** `Pandas` para manipulação e agregação de dados.
* **Visualização de Dados:** `Matplotlib` e `Seaborn` para a criação de gráficos informativos.
* **Análise de Dados:** Filtragem, agrupamento, criação de colunas calculadas e uso de tabelas dinâmicas.
* **Relatórios Profissionais:** Geração de tabelas estilizadas em HTML.
* **Manipulação de Arquivos:** Leitura de `.csv`, `.parquet`, `.xlsx` e `.json`.

---

## 🚀 Resumo das Análises por Dia

### Dia 1: Preparação de Dados
* **O que foi feito:** Coleta de dados de empréstimos e exemplares de diferentes fontes. Unificação das informações em um único DataFrame para iniciar a análise.
* **O principal aprendizado:** A base de qualquer projeto de dados é uma boa etapa de coleta, limpeza e unificação de dados de múltiplas fontes.

### Dia 2: Enriquecimento de Dados
* **O que foi feito:** Enriquecimento do DataFrame com a criação de uma nova coluna (`CDU_geral`) que traduziu códigos numéricos para categorias de temas, tornando os dados mais significativos.
* **O principal aprendizado:** Entender o contexto do negócio (a CDU) é fundamental para transformar dados brutos em informações úteis.

### Dia 3: Análise de Tendências Temporais
* **O que foi feito:** Análise das tendências de empréstimos por ano, mês e hora. Gráficos de linha e barra foram usados para identificar picos de demanda.
* **O principal aprendizado:** A visualização de dados é uma ferramenta poderosa para revelar padrões. A análise confirmou picos de empréstimos em meses específicos, como março e setembro, e em horários de maior movimento.

### Dia 4: Explorando Variáveis Categóricas
* **O que foi feito:** Exploração dos dados por tipo de usuário, coleção e biblioteca. Criei uma função reutilizável para gerar tabelas de frequência (quantidade e percentual).
* **O principal aprendizado:** Funções de análise customizadas agilizam o trabalho e garantem a consistência. A análise permitiu ranquear as coleções mais populares e entender o perfil de usuário mais ativo.

### Dia 5: Comparando Perfis de Usuários
* **O que foi feito:** Análise segmentada dos empréstimos de alunos de graduação e pós-graduação. Usei box plots para comparar a distribuição de empréstimos ao longo do tempo.
* **O principal aprendizado:** A análise de subgrupos revela insights que a análise geral pode esconder, como as diferenças no comportamento de empréstimos entre graduação e pós-graduação.

### Dia 6: Integrando Novas Fontes de Dados
* **O que foi feito:** Simulação de um cenário real, integrando dados de cadastro de usuários de arquivos Excel e JSON. Criei uma tabela dinâmica (pivot_table) para resumir empréstimos por curso e ano.
* **O principal aprendizado:** Um bom analista de dados sabe lidar com diferentes formatos de arquivos e usa tabelas dinâmicas para criar relatórios concisos e de alto valor.

### Dia 7: Relatórios e Apresentação
* **O que foi feito:** Cálculo da variação percentual de empréstimos entre anos e inclusão de dados de previsão. O resultado foi exportado para uma tabela HTML estilizada com cores para indicar crescimento (verde) ou queda (vermelho).
* **O principal aprendizado:** A última etapa da análise é a comunicação. Apresentar resultados de forma clara e visualmente agradável é o que transforma um projeto em um entregável valioso para a equipe ou diretoria.