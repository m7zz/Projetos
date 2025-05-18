🛒 Sistema de Gerenciamento de Produtos

Bem-vindo ao Sistema de Gerenciamento de Produtos!
Este é um sistema simples, interativo e em modo console, projetado para auxiliar administradores no controle de estoque de produtos durante o expediente.
📋 Funcionalidades

O sistema permite ao administrador realizar as seguintes ações:

    📃 Listar Produtos

    ➕ Cadastrar Novo Produto

    ✏️ Editar Produto Existente

    ❌ Excluir Produto

    🚪 Sair do Sistema

Cada produto contém as seguintes informações:

    Nome: Identificação do produto

    Preço: Valor unitário do produto

    Quantidade: Quantidade disponível em estoque

🖥️ Interface Principal

=====================================
     Gerenciamento de Produtos
=====================================
[1] - Listar Produtos
[2] - Cadastrar Produto
[3] - Editar Produto
[4] - Excluir Produto
[5] - Sair
=====================================
--> Selecione uma Opção:

🧠 Lógica do Sistema

    Os produtos são armazenados em uma estrutura de dados (recomenda-se lista de dicionários) para facilitar buscas, edições e exclusões.

    Exemplo:

    produtos = [
        {"nome": "Teclado", "preco": 99.90, "quantidade": 10},
        {"nome": "Mouse", "preco": 49.90, "quantidade": 15}
    ]

    Cada operação (listar, cadastrar, editar, excluir) é implementada como uma função separada.

    O sistema permanece em execução até que o usuário escolha a opção [5] - Sair.

🛠️ Tecnologias Utilizadas

    Linguagem: Python 3.x

    Ambiente: Console / Terminal

▶️ Como Executar

    Certifique-se de que o Python 3 esteja instalado em sua máquina.

    Salve o código principal como gerenciador_produtos.py.

    Execute no terminal com:

python gerenciador_produtos.py

✨ Sugestões Futuras (Extras)

Se desejar expandir o sistema, aqui vão algumas ideias:

    💾 Salvamento e carregamento de produtos em arquivos .json ou .csv

    🔍 Filtro de busca por nome ou faixa de preço

    🧮 Cálculo automático de valor total em estoque

    📊 Interface gráfica com Tkinter ou web com Flask

📄 Licença

Este projeto é de uso educacional e livre para aprimoramento pessoal ou acadêmico.
