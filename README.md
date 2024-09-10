# Análise
## Como a pandemia afetou o Enem em 2020 e quais os fatores impactaram o público do sexo feminino
- **Arquivos para Downloads:**
- [2018](https://download.inep.gov.br/microdados/microdados_enem_2018.zip)
- [2019](https://download.inep.gov.br/microdados/microdados_enem_2019.zip)
- [2020](https://download.inep.gov.br/microdados/microdados_enem_2020.zip)
- [2021](https://download.inep.gov.br/microdados/microdados_enem_2021.zip)
- [2022](https://download.inep.gov.br/microdados/microdados_enem_2022.zip)

## 1 Descricao
Este projeto visa analisar o impacto da pandemia de COVID-19 no desempenho das participantes do sexo `feminino` no ENEM (Exame Nacional do Ensino Médio), comparando os anos de 2019 (pré-pandemia) e 2020 (durante a pandemia). O foco da análise é entender como fatores socioeconômicos, raciais e o acesso à internet influenciaram o desempenho das alunas em diferentes áreas do conhecimento e na redação.

## 2 Objetivo

### Objetivos Gerais:
- Avaliar o impacto da pandemia no desempenho geral das estudantes do sexo `feminino` no ENEM.
- Investigar possíveis disparidades educacionais entre diferentes grupos raciais e socioeconômicos.

### Objetivos Específicos:
- Comparar a média de notas nas áreas de Ciências Naturais, Ciências Humanas, Linguagens, Matemática e Redação entre 2019 e 2020.
- Analisar a influência da renda familiar per capita no desempenho das estudantes.
- Analisar a influência do acesso à internet no desempenho das estudantes.
- Analisar a relação entre raça e desempenho acadêmico. 
- Fazer um paralelo antes e durante a pandemia.

### Dicionário de Dados:
- `Cor`: Grupo racial dos participantes (ex.: Branca, Parda, Preta, Amarela, Indígena, Não Declarado).
- `Faixa_Renda_Percapita`: Faixa de renda familiar per capita (ex.: Baixa Renda, Média Renda, Alta Renda).
- `Acesso_à_Internet`: Indica se o estudante tinha acesso à internet em casa (Sim ou Não).
- `NU_NOTA_CN`: Nota em Ciências Naturais.
- `NU_NOTA_CH`: Nota em Ciências Humanas.
- `NU_NOTA_LC`: Nota em Linguagens.
- `NU_NOTA_MT`: Nota em Matemática.
- `NU_NOTA_REDACAO`: Nota na Redação.
- `Ano`: Ano de participação no ENEM (2019 ou 2020).

## 4. Metodologia

### 4.1. Limpeza de Dados:
- Tratamento de valores ausentes e inconsistentes.
- Mapeamento de categorias para tornar os dados mais interpretáveis (ex.: substituição de códigos numéricos por descrições de cor/raça, de acesso à internet, etc).

### 4.2. Análise Estatística:
- **Agrupamento dos dados**: Por ano, raça, faixa de renda e acesso à internet.
- **Média de notas**: Cálculo das médias nas áreas de conhecimento.
- **Comparação temporal**: Análise comparativa entre presentes de 2018 a 2022. Comparativo das notas de 2019 e 2020.

### 4.3. Visualização de Dados:
- Gráficos para ilustrar os presentes por grupos em 2019 e 2020.
- Gráficos para ilustrar o desempenho médio dos grupos em 2019 e 2020.
- Análise visual das diferenças de desempenho entre diferentes combinações de fatores (raça, renda, acesso à internet).

## 5. Perguntas de Pesquisa

### 5.1. Impacto na Presença Geral
- Qual foi o impacto da pandemia na presenca do sexo feminino no Enem 2020?
- Houveram grupos mais impactados que os outros?

### 5.2. Diferenças no Desempenho Geral:
- Quais foram as mudanças no desempenho médio dos estudantes entre 2019 e 2020?

### 5.3. Impacto da Pandemia no Desempenho:
- Houve uma queda significativa nas notas de 2020 em comparação a 2019?

### 5.4. Fatores Socioeconômicos e Raça:
- Como a combinação de fatores como raça, renda e acesso à internet afetou o desempenho no ENEM?
- Existe uma interação entre raça e renda que possa destacar disparidades educacionais?

### 5.5. Desempenho por Área do Conhecimento:
- Quais grupos (com base na combinação de raça, renda e acesso à internet) tiveram melhor desempenho em disciplinas específicas (Ciências Naturais, Humanas, Linguagens, Matemática, Redação)?

### 5.6. Fatores que Influenciam a Nota de Redação:
- O desempenho na redação foi mais afetado por renda ou acesso à internet? Como isso variou entre diferentes grupos raciais?

## 6. Resultados

### Principais Descobertas:
- A pandemia teve grande impacto na presenca de todos os grupos. 
- Não houve um impacto significativo no desmpenho das participantes.
- 

### Visualizações:
- Gráficos comparativos de desempenho por raça, renda e acesso à internet entre os anos de 2019 e 2020.

## 7. Conclusão

A pandemia de COVID-19 trouxe impactos profundos e inesperados para a população brasileira, com as escolas fechadas evidenciando sérios desafios na educação. Além de afetar os alunos em geral, é crucial analisar como essa crise afetou de maneira desproporcional grupos minoritários, considerando aspectos como gênero, raça, acesso à internet e renda.

Os dados revelam que, em geral, mulheres de raças "Branca" e "Amarela", que possuem maior renda e acesso à internet, apresentaram notas significativamente mais altas em comparação com as raças "Preta" e "Indígena", que enfrentam condições socioeconômicas mais precárias e acesso limitado à internet. Além disso, é possível constatar que as mulheres indígenas foram as mais afetadas em relação a presença nas provas, enquanto as outras classificações de raça e cor tiveram índices similares.
Essas discrepâncias no desempenho acadêmico sublinham a correlação entre fatores socioeconômicos e acesso à internet com o sucesso escolar, evidenciando as disparidades  entre diferentes grupos raciais e econômicos.



## 8. Tecnologias Utilizadas

- **Linguagem de Programação**: Python
- **Bibliotecas**:
  - `pandas`: Manipulação de dados
  - `numpy`: Cálculos numéricos
  - `matplotlib` e `seaborn`: Visualização de dados

## 9. Próximos Passos

- EAnalisar o impacto para o sexo Masculino;

- Analisar por Região do Brasil;

## Autores:
- **Luan Gabriel**  
  [GitHub](https://github.com/LuanGBS) | [LinkedIn](https://br.linkedin.com/in/luan-gabriel-barroso-santos-15aba71b6)

- **Májda Alvarenga**  
  [GitHub](https://github.com/majdaalvarenga) | [LinkedIn](https://www.linkedin.com/in/majdaalvarenga/)

- **Marcos Carvalho Junior**  
  [GitHub](https://github.com/MarcosFN2014) | [LinkedIn](https://www.linkedin.com/in/marcos-carvalho-8173a2241/)

- **Mateus Cunha**  
  [GitHub](https://github.com/Mateusclm) | [LinkedIn](https://www.linkedin.com/in/mateusclm/)

- **Mille Amorim**  
  [GitHub](Link) | [LinkedIn](Link)
