# Como-organizar-sua-vida-Financeira-com-Planilhas-Inteligentes-e-IA-

Guia para Criação da Planilha de Controle de Gastos

Este documento explica como a planilha CONTROLE DE GASTO.xlsx foi criada, detalhando os dados, gráficos e tabelas dinâmicas. Ele é útil para quem deseja replicar ou documentar o processo no GitHub.

1. Estrutura e organização dos dados (Planilha DATA)

Passo 1: Inserção dos dados

Crie uma tabela com as seguintes colunas:

Data: Data da transação.

Mês: Mês correspondente.

Tipo: Classificação da transação (ENTRADA ou SAÍDA).

Categoria: Tipo de despesa ou receita (e.g., Renda Fixa, Alimentação, Transporte).

Descrição: Detalhes adicionais sobre a transação.

Valor: Valor em reais (R$).

Operação Bancária: Tipo de operação (e.g., Cartão de Crédito, Transferência).

Status: Status da transação (e.g., Pago, Pendente).

Passo 2: Formatação da tabela

Utilize as ferramentas do Excel para formatar a tabela:

Selecione os dados e aplique o estilo de tabela.

Escolha uma cor que diferencie linhas e colunas claramente.

Passo 3: Validação de dados

Adicione regras de validação para evitar erros:

Coluna "Tipo": Permitir apenas "ENTRADA" ou "SAÍDA".

Coluna "Status": Permitir "Pago", "Pendente", ou "Recebido".

2. Criação de uma Tabela Dinâmica (Planilha Controller)

Passo 1: Inserir uma Tabela Dinâmica

No Excel:

Selecione toda a tabela na planilha DATA.

Clique em Inserir > Tabela Dinâmica.

Escolha criar em uma nova planilha.

Passo 2: Configuração da Tabela Dinâmica

Campos utilizados:

Linhas: "Data" agrupada por mês.

Colunas: "Tipo".

Valores: Soma de "Valor".

Passo 3: Formatação e ajustes

Adicione filtros para categorias ou períodos.

Renomeie os campos para facilitar a leitura:

"Soma de Valor" para "Total".

3. Resumos e Metas (Planilha Economia)

Passo 1: Cálculos principais

Adicione células com:

Total Reservado: Soma dos valores de "ENTRADA" acumulados.

Meta de Reserva: Valor alvo.

Passo 2: Configuração dos campos

Utilize funções do Excel como:

=SOMA(SE(Tipo="ENTRADA";Valor;0)) para calcular entradas.

Insira manualmente a meta.

4. Gráficos no Dashboard

Passo 1: Inserção do gráfico

Selecione os dados da tabela dinâmica.

Clique em Inserir > Gráfico e escolha o tipo:

Gráfico de barras para comparar categorias.

Gráfico de linhas para mostrar tendências mensais.

Passo 2: Personalização

Adicione:

Título.

Legenda para facilitar a interpretação.

Passo 3: Posicionamento

Insira os gráficos na planilha Dashboard.

Organize para que os gráficos e tabelas dinâmicas sejam visíveis ao mesmo tempo.
