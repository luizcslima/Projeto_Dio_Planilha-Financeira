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

- [ChatGPT](https://chat.openai.com/) -- Geração de insights
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

>> ℹ️ **NOTA_3:** A ideia é utilizar o dashboard em um zoom que permida a visualização de todos os slicers e o o gráfico de fluxo de caixa. Caso o usuário necessite ver algum detalhes extra, ele pode descer a barra de rolagem. Um período adequado de uso seria o de 1 ano, períodos mais extensos podem impactar na visualização do dashboard.
>> ℹ️ **NOTA_4:** Alguns dados foram inseridos na planilha "Formatação em Tabela" a fim de testar se a atualização automática do power query, tabelas dinâmicas e o dashboard estavam funcionando adequadamente. Lembre-se sempre de utilizar o "Atualizar Tudo" na aba "Dados" para garantir que as informações das tabelas e gráficos estejam atualizadas.
<br/>

> 2️⃣ **PROMPT #1 [COPILOT], [ChatGPT] - Solicitação de insights sobre os dados:**
> .
<br/>

> 3️⃣ **AÇÃO #2 - Documentação final do projeto:**
>Upload de arquivos para o GitHub.
>Finalização das seções presentes na página (resultados, discussão, conclusão, autor)
<br/> 


## Resultados 🔎📊
<p align="justify">
O resultado do presente trabalho foi o conteúdo presente nesse arquivo readme.md e o arquivo excel "", que se encontra na pasta "outputs" de respositório. <br/>
Os ícones utilizados no e-book encontram-se na past "assets".
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
