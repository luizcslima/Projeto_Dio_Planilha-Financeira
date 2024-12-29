# Projeto_Dio_Planilha-Financeira 🤖📊

<p align="justify">
O presente trabalho faz parte de um dos entregáveis do bootcamp "CAIXA - IA Generativa com Microsoft Copilot", especificamente da seção "Projetos Práticos com IA" e consiste na criação de uma planilha financeira.

Acesso à plataforma: [DIO](https://dio.me)
</p>

> ℹ️ **NOTA_1:** Este repositório é para fins de aprendizado. O autor não se responsabiliza pelas informações aqui fornecidas.

## Índice 🗃️
- [Tecnologias utilizadas no projeto](#tecnologias_utilizadas_no_projeto)
- [Passo-a-Passo](#passo_a_passo)
- [Resultados](#resultados)
- [Discussão](#discussao)
- [Conclusão](#conclusao)
- [Referências Úteis](#referencias_uteis)
- [Licença](#licenca)
- [Autor](#autor)

## Tecnologias utilizadas no projeto 💻

- [Copilot](https://copilot.microsoft.com/) -- Geração de insights
- [Excel](https://www.microsoft.com/en/microsoft-365/excel) -- Ferramenta de edição de planilhas eletrônicas


## Passo-a-Passo

> ℹ️ **NOTA_2:** Normalmente é necessário um planejamento da planilha/dashboard a ser preparado, como se desenhará a análise de dados, quais as métricas que se quer analisar e relacionados. No entanto, como os vídeos da DIO já direcionaram o que é esperado e forneceram uma base de dados consistente, o processo de passo-a-passo será, em partes, simplificado. Lembre-se sempre de planejar o trabalho que será feito em um arquivo de excel, sendo os requerimentos de usuário um guia importante para isso.
<br/>

> 1️⃣  **AÇÃO #1 - [Excel] - Edição da pasta de trabalho:** </br>
> 1a - Criação de cópia da pasta de trabalho; </br>
> 1b - Renomear a pasta de trabalho copiada com um nome intuitivo do que se pretende fazer "Projeto DIO - Planilha Financeira - Luiz Lima";  </br>
> 1c - Renomear a planilha que contém os dados como "RAW" (indicará que é a planilha com os dados brutos);  </br>
> 1d - Copiar a planilha "RAW" e providenciar um nome intuitivo do que está sendo feito com a base de dados:  </br>
>> - Formatação em Tabela --> Organização, entendimento dos campos, nomeação da tabela ("tbl_Gastos");
>> - tbl_Gastos_PQ --> Automatização da tarefa de organização, limpeza e formatação dos dados (conforme mencionado na NOTA_2, a base de dados já veio bem consistente e guiada pelos vídeos da DIO, mas, em outras circustâncias, o passo do power query ajudaria bastante na identificação de dados problemáticos e também na "automatização" do passo de apêndice de novos dados). No caso, houve a criação de um identificador único por transação, criação das colunas "MÊS", "ANO" a "VALOR_FLUXO" (Coluna Condicional para gerar um valor negativo para as transações do tipo "SAÍDA") e a reorganização das colunas.
>> - tbl_Gastos_TD --> Criação das tabelas dinâmicas para responder as perguntas que serão a base do dashboard final.
>>> - Saldo (pt_saldo)
>>> - Status da Transação (pt_status)
>>> - Fluxo de Caixa - Detalhado (pt_fluxoDeCaixaDetalhado)
>>> - Fluxo de Caixa - Mensal (pt_fluxoDeCaixaMensal)
>>> - Tipos de Transação (pt_transacao)
>>> - Categoria de Gastos (pt_categoria)
>>> - Categoria de Gastos - Saídas (pt_categoriaSaida)
>>> - Descrição de Gastos (pt_descricao)
>>> - Descrição de Gasost - Saídas (pt_descricaoSaida)
>> - Dashboard_Financeiro --> Criação dos gráficos dinâmicos, slicers e linha do tempo. 
<br/>

>> ℹ️ **NOTA_3:** A ideia é utilizar o dashboard em um zoom que permida a visualização de todos os slicers e o o gráfico de fluxo de caixa. Caso o usuário necessite ver algum detalhes extra, ele pode descer a barra de rolagem. Um período adequado de uso seria o de 1 ano, períodos mais extensos podem impactar na visualização do dashboard. <br/>
>> ℹ️ **NOTA_4:** Alguns dados foram inseridos na planilha "Formatação em Tabela" a fim de testar se a atualização automática do power query, tabelas dinâmicas e o dashboard estavam funcionando adequadamente. Lembre-se sempre de utilizar o "Atualizar Tudo" na aba "Dados" para garantir que as informações das tabelas e gráficos estejam atualizadas.
<br/>

> 2️⃣ **PROMPT #1 [COPILOT] - Solicitação de insights sobre os dados:**
> Contexto: Copilot/ChatGPT, você agora é um coaching financeiro e especialista em finanças, planilhas, excel, elaboração de dashboards, estatística e análise de tendências.
Função: Utilizar a tabela de dados contida no documento anexado, como base de conhecimentos e gerar insights.
Tópico: Planejamento financeiro.
Ação: Gerar insights sobre os dados.
Expectativa: >Forneça análises estatísticas relevantes >Forneça dados relevantes >Forneça insights práticos relevantes >Forneça ações que o usuário deve tomar de imediato."
<br/>

> 3️⃣ **AÇÃO #2 - Documentação final do projeto:**
>Upload de arquivos para o GitHub.
>Finalização das seções presentes na página (resultados, discussão, conclusão, autor)
<br/> 


## Resultados 🔎📊
<p align="justify">
O resultado do presente trabalho foi o conteúdo presente nesse arquivo readme.md e o arquivo excel "Projeto DIO - Planilha Financeira - Luiz Lima", que se encontra na pasta "outputs" de respositório. <br/>
Os ícones utilizados no e-book encontram-se na past "assets".<br/>
  
>**Reposta prompt [Copilot]:** <br/>
>Fantástico! Vamos analisar esses dados para proporcionar insights valiosos e ações práticas. Vamos começar com algumas análises estatísticas:
>
>### Análises Estatísticas Relevantes:
>1. **Receitas Totais**: O valor total de entradas foi de **R$ 18.500,00**, com as seguintes contribuições:
>   - Salário Mensal: R$ 15.000,00
>   - Dividendos de Ações: R$ 800,00
>   - Projeto Freelancer: R$ 1.200,00
>   - Venda de Equipamentos Eletrônicos: R$ 1.500,00
>
>2. **Despesas Totais**: O valor total de saídas foi de **R$ 14.720,00**, distribuído entre as seguintes categorias principais:
>   - Alimentação: R$ 2.100,00
>   - Transporte: R$ 1.100,00
>   - Lazer: R$ 700,00
>   - Saúde: R$ 1.060,00
>   - Educação: R$ 1.100,00
>   - Vestuário: R$ 2.100,00
>   - Eletrônicos: R$ 3.200,00
>   - Utilidades Domésticas: R$ 1.950,00
>   - Presentes: R$ 1.080,00
>   - Beleza: R$ 550,00
>   - Pet Care: R$ 350,00
>   - Viagem: R$ 1.250,00
>   - Gastronomia: R$ 570,00
>
>3. **Saldo Liquido**: O saldo líquido das transações durante o período é de **R$ 3.780,00**.
>
>### Dados Relevantes:
>- **Maior Despesa**: Compra de novo smartphone em 23/09/2024, no valor de R$ 1.500,00.
>- **Maior Receita**: Salário mensal, recebendo R$ 5.000,00 em três ocasiões em 01/08, 01/09 e 01/10.
>- **Despesas Pendente**: R$ 8.630,00 ainda estão pendentes.
>
>### Insights Práticos Relevantes:
>1. **Controle de Gastos em Eletrônicos**: Há uma alta quantidade de despesas com eletrônicos. Revisar a necessidade destes gastos frequentes pode ajudar a poupar.
>2. **Despesa com Pendente**: Grande parte das despesas pendentes é preocupante. Tentar minimizar despesas ou efetuar os pagamentos para evitar juros futuros.
>3. **Categoria de Transporte**: A categoria de transporte é relativamente alta. Avaliar a possibilidade de reduzir a frequência destes gastos, ou explorar alternativas mais economicas.
>
>### Ações Imediatas:
>1. **Priorize Pagamentos Pendentes**: Concentre-se em realizar os pagamentos pendentes para evitar penalidades adicionais.
>2. **Reveja Gastos em Eletrônicos**: Tente adiar novas comprar eletrônicas grandes, e veja se consegue evitar.
>3. **Ajuste de Orçamento**: Considere ajustar o orçamento alocado em categorias com maiores despesas, como Eletrônicos e Vestuário, para poupar mais e reduzir contas futuras.
>
>Estes insights e ações te ajudarão a ter um controle mais eficiente das suas finanças e também a poupar para o futuro! Se precisar de mais detalhes ou ajuda com planilhas e dashboards, estou a disposição.
  
</p>


## Discussão 📑
<p align="justify">


</p>

## Conclusão 📝💡
<p align="justify">


</p>

## Referências Úteis 📚
<p align="justify">
N/A
</p>  

## Licença 📄
<p align="justify">
Os ícones utilizados no e-book são provenientes do site [IconArchive](https://www.iconarchive.com). Eles não são de minha autoria!
The icons used in the e-book are from the website [IconArchive](https://www.iconarchive.com). They are not my authorship.
</p>

## Autor 🤓
<p align="justify">
Luiz Lima - Q&R | VSC / CSV | Compliance & Melhoria Contínua - https://www.linkedin.com/in/luizslima/  
</p>
