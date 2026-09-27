📊 Relatório de Vendas e Lucros
🎯 Objetivo

Neste projeto eu montei um relatório interativo no Power BI usando uma planilha de vendas pronta (Financial Sample). O foco não foi em criar um modelo de dados complicado, e sim em deixar o relatório fácil de navegar: várias páginas conectadas, gráficos que trocam de tipo com um clique e alguns ajustes pra organizar e destacar as informações.

🧠 Sobre o projeto
Relatório com 4 páginas conectadas por botões
Gráficos que trocam de tipo (barra, pizza, mapa) sem sair da página
Cálculos pra agrupar dados e destacar os produtos que mais vendem
Preocupação com acessibilidade (texto explicando o gráfico pra quem usa leitor de tela)
⭐ Páginas do relatório
🏠 Home page — capa do relatório
📈 Vendas — total de vendas, unidades vendidas, e gráficos por produto, por segmento, por país e por período
🔍 Lucro — vendas por semestre, por mês, e um gráfico que agrupa as vendas em faixas de quantidade
🏆 TOPN & Outliers — os produtos mais vendidos e um gráfico comparando vendas com lucro por produto
🟡 Base de dados

Uma única tabela chamada financials, com as informações de cada venda: produto, país, segmento, valor vendido, lucro e data. Não precisei ligar tabelas diferentes — está tudo junto nessa tabela.

🔢 O que eu fiz nos cálculos
Separei as unidades vendidas em faixas, pra montar um gráfico de quantidade
Separei os meses em dois semestres
Usei uma ferramenta do próprio Power BI que agrupa sozinha os produtos com resultados parecidos
Criei cálculos simples de soma, média e uma meta (80% do total de vendas)
Descobri automaticamente os 3 produtos mais vendidos
🧭 Navegação
Botões trocam o tipo de gráfico sem sair da página
Setas levam para a próxima página ou para a anterior
Um botão com ícone de casa volta pra página de Vendas de qualquer lugar do relatório
⚙️ Etapas do desenvolvimento
Importei a planilha de vendas pro Power BI
Criei os cálculos pra organizar e resumir os dados
Montei as 4 páginas do relatório
Testei os botões de navegação e troca de gráfico
Adicionei texto explicativo em alguns gráficos pra acessibilidade
🛠️ Tecnologias
Power BI
Power Query (importação dos dados)
DAX (fórmulas usadas nos cálculos)
🖥️ Redes Sociais

www.linkedin.com/in/matheus-zerbinatti-a991b7204/
