# Estatística no Dia a Dia

**O que os dados dizem sobre a nossa vida?**

Projeto de extensão da Universidade Federal de Alfenas — UNIFAL-MG, ICSA (Campus Varginha), dedicado à análise de dados públicos e à divulgação da Estatística em linguagem acessível.

Investigamos perguntas sobre Varginha e o Sul de Minas, transformando dados oficiais em análises, gráficos e materiais educativos.

Este repositório reúne os temas investigados, as análises desenvolvidas e os scripts utilizados para obter, tratar e analisar os dados. **Os scripts permitem reproduzir as investigações para outros municípios**, mediante a alteração dos parâmetros indicados e conforme a disponibilidade de dados nas fontes oficiais.

## Objetivos

- Aproximar a Estatística do cotidiano da população.
- Desenvolver a leitura e a interpretação crítica de dados.
- Investigar questões demográficas, sociais e econômicas.
- Divulgar resultados com clareza e responsabilidade.
- Disponibilizar scripts e métodos para que as análises possam ser compreendidas, reproduzidas e adaptadas a outros municípios.

## Temas do projeto

Os materiais serão incorporados ao repositório conforme os scripts e as análises forem concluídos e revisados.

### População

1. [Varginha está envelhecendo?](temas/01-envelhecimento-populacional/README.md)
2. Varginha tem mais mulheres ou homens?
3. Varginha cresceu mais que as cidades vizinhas?

### Saúde e demografia

4. Está nascendo menos gente em Varginha?
5. Quais são as principais causas de morte em Varginha?

### Trabalho

6. O emprego formal está crescendo em Varginha?
7. Quais setores mais empregam em Varginha?
8. Mulheres e homens têm a mesma participação no emprego formal?
9. Existe diferença na remuneração média de homens e mulheres?

### Educação e economia

10. Varginha é uma cidade universitária?
11. Varginha é uma cidade rica?

### Cotidiano e retrospectiva

12. Quanto custa abastecer em Varginha?
13. O que os dados nos contaram sobre Varginha em 2026?

## Organização dos arquivos

Cada tema terá uma pasta própria em `temas/`, reunindo:

- **README.md:** apresentação da pergunta investigada, fonte dos dados e instruções para reproduzir a análise.
- **scripts/:** códigos utilizados para baixar os dados, realizar os cálculos e gerar tabelas e gráficos.
- **analise.md:** resultados da investigação desenvolvida pelo projeto, interpretação e limitações.

A metodologia será documentada nas instruções de cada tema, incluindo filtros, períodos, unidades, definições e fórmulas.

**As bases de dados não serão armazenadas neste repositório.** Elas serão obtidas diretamente das fontes oficiais durante a execução dos scripts e poderão ser salvas no computador do usuário, junto aos resultados gerados.

## Reproduza a análise para seu município

Varginha é o município de referência do projeto, mas as investigações podem ser adaptadas a outras localidades.

Para reproduzir uma análise, o usuário deverá:

1. Consultar o `README.md` do tema escolhido.
2. Instalar o programa e os pacotes indicados.
3. Alterar o código IBGE ou o parâmetro de seleção do município no início do script.
4. Ajustar, quando necessário, o período e a lista de municípios utilizados nas comparações.
5. Executar o script para obter os dados e gerar os resultados.
6. Interpretar as tabelas e os gráficos considerando o contexto da localidade escolhida.

Cada tema indicará os parâmetros que podem ser alterados e os arquivos que serão gerados.

A reprodução depende da cobertura da fonte consultada. Quando não houver dados para o município ou período selecionado, essa ausência deverá ser informada pelo script.

Como as fontes oficiais podem atualizar ou revisar suas bases, os resultados de uma nova execução podem diferir daqueles apresentados na análise original.

## Como trabalhamos

Cada investigação começa com uma pergunta. A equipe consulta fontes oficiais, organiza os dados, calcula indicadores e interpreta os resultados.

Antes da divulgação, os materiais passam por revisão da fonte, dos cálculos, dos gráficos e do texto.

Todas as análises devem informar o território, o período, a unidade de medida e os conceitos utilizados. As limitações são apresentadas junto aos resultados, evitando conclusões que os dados não sustentam.

## Fontes de dados

As fontes variam conforme o tema e incluem:

- Instituto Brasileiro de Geografia e Estatística — IBGE e SIDRA.
- Ministério da Saúde — DATASUS, SINASC e SIM.
- Ministério do Trabalho e Emprego — Novo Caged e RAIS.
- Instituto Nacional de Estudos e Pesquisas Educacionais Anísio Teixeira — INEP.
- Agência Nacional do Petróleo, Gás Natural e Biocombustíveis — ANP.

A fonte específica, os critérios de seleção e a data de acesso serão registrados na documentação de cada análise.

## Equipe

O projeto conta com coordenação e coordenação adjunta docente, um bolsista e duas pessoas voluntárias, que atuam na coleta de dados, análise estatística e comunicação dos resultados.

**Instituição:** Universidade Federal de Alfenas — UNIFAL-MG  
**Instituto:** Instituto de Ciências Sociais Aplicadas-ICSA (Campus Varginha)

## Como utilizar e citar os materiais

Para compreender uma investigação, consulte a apresentação do tema e sua análise. Para reproduzir os resultados ou aplicar o método a outro município, siga as instruções e execute os scripts disponibilizados.

Ao utilizar ou adaptar os materiais, cite o Projeto Estatística no Dia a Dia, a UNIFAL-MG, o título do tema e a fonte original dos dados. Identifique também o município e o período da nova aplicação.

As análises descrevem os períodos indicados em cada estudo. A data de publicação do material pode ser diferente do ano de referência dos dados.
