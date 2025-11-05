# Estoque Com Graficos

Este script Python gerencia um inventário de produtos via terminal. Ele usa pandas para dados e matplotlib para gráficos.

# Funcionalidades

Ao iniciar, o script cria 400 produtos aleatórios e salva em planilha_produtos_400.xlsx.
O menu principal permite:

1 - Cadastrar novo produto: Adiciona um item ao estoque.
2 - Listar produtos: Mostra itens cadastrados desde que o programa abriu.
3 - Listar todos os produtos (DataFrame): Mostra o estoque completo (400+).
4 - Excluir produto: Remove um item cadastrado na sessão.
5 - Gráficos: Abre o sub-menu de visualização.
6 - Sair: Fecha o programa.
7 - Salvar e Sair: Salva as alterações no Excel/CSV e fecha.

# Entendendo a Função Gráficos
Dúvida comum: "Por que o gráfico tem tantas bolinhas se eu selecionei só um item?"

Resposta curta: Você não selecionou um item, você selecionou um tipo de produto (ex: "Bolo de Chocolate").
O script gera 400 itens aleatórios no começo. Muitos desses itens repetem o nome ("Bolo de Chocolate"), mas cada um tem um preço aleatório e uma quantidade aleatória.
O gráfico plota todas as bolinhas (todos os registros) que têm aquele nome. Ele mostra a dispersão de preço vs. quantidade para todos os itens daquele mesmo tipo no seu estoque.

# Instalação
Baixe e descompacte o arquivo .zip do projeto.
Abra o terminal na pasta do projeto.
Instale as dependências necessárias

Execute o script sistemaestoque.py
