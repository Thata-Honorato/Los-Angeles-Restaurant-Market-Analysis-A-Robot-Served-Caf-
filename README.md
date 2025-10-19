# Sprint 10 – Pesquisa de Mercado: Cafeteria com Garçons Robôs em Los Angeles

## Descrição do Projeto

Neste projeto, meu objetivo foi aplicar os conhecimentos de **storytelling com dados** para realizar uma pesquisa de mercado. Decidi abrir uma pequena cafeteria com **garçons robôs** em Los Angeles. Como se trata de um investimento alto, meus parceiros pediram que eu analisasse o mercado para avaliar a viabilidade do negócio e apresentar recomendações aos investidores.

O foco principal foi:

- Entender o perfil dos restaurantes existentes em LA.  
- Avaliar proporções de diferentes tipos de estabelecimentos.  
- Identificar características de redes de restaurantes e seus padrões de assentos.  
- Fornecer recomendações sobre o tipo de restaurante e tamanho mais apropriado.  
- Preparar uma apresentação clara e estruturada para investidores.

---

## Dados Utilizados

### Restaurantes (`rest_data_us_upd.csv`)

- **object_name** — nome do estabelecimento.  
- **chain** — se o estabelecimento é de rede (`TRUE`/`FALSE`).  
- **object_type** — tipo de estabelecimento.  
- **address** — endereço completo.  
- **number** — número de assentos.

---

## Passos do Projeto

### Passo 1: Preparação dos Dados
- Carreguei os dados em um DataFrame e verifiquei os tipos de dados de cada coluna.  
- Tratei valores ausentes ou duplicados quando necessário.  
- Separei o nome da rua em uma coluna específica para análise geográfica.

### Passo 2: Análise de Dados
- Investiguei a proporção de diferentes tipos de estabelecimentos e construí gráficos para visualização.  
- Analisei a proporção de restaurantes de rede versus independentes.  
- Identifiquei padrões de assentos em redes de restaurantes: muitos estabelecimentos com poucos assentos ou poucos estabelecimentos com muitos assentos?  
- Calculei o número médio de assentos por tipo de restaurante e destaquei qual tipo possui, em média, o maior número de assentos.  
- Analisei as ruas com maior número de restaurantes e criei gráficos de distribuição.  
- Identifiquei ruas com apenas um restaurante.  
- Avaliei a distribuição do número de assentos em ruas com muitos restaurantes e tirei conclusões sobre padrões de capacidade.

### Passo 3: Conclusão e Recomendações
- Baseado nos resultados, recomendei **o tipo de restaurante mais apropriado**, o número médio de assentos ideal e a viabilidade de desenvolver uma rede de cafeterias.  
- Preparei uma **apresentação para investidores** em PDF, destacando insights estratégicos e gráficos claros que comunicam minhas recomendações de forma eficaz.

---

## Ferramentas e Formato
- Todo o projeto foi desenvolvido em **notebook Jupyter**.  
- O código está em células de código (`code`) e explicações em células de texto (`markdown`).  
- Organizei o notebook com títulos, seções e comentários detalhados para facilitar a compreensão.

---

## Critérios de Avaliação

Meu projeto foi avaliado com base em:

- Preparação e limpeza de dados para análise.  
- Construção de gráficos adequados aos dados e interpretação correta.  
- Uso de bibliotecas de visualização, incluindo **Seaborn**.  
- Estruturação de uma apresentação clara para investidores.  
- Comunicação eficaz da mensagem principal com base nos dados.  
- Organização do notebook e clareza do código.  
- Conclusões fundamentadas em análises e insights.  
- Comentários detalhados em cada passo do projeto.

---

## Conclusão

Com este projeto, consegui aplicar técnicas de **análise de dados e storytelling** para transformar dados brutos em insights acionáveis. Desenvolvi recomendações estratégicas sobre o tipo de restaurante e a capacidade ideal para garantir que o projeto da cafeteria com garçons robôs em Los Angeles seja viável e atraente para investidores.

