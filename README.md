**Sistema de Controle de Estoque**

Este é um sistema simples e eficiente para gerenciamento de inventário desenvolvido em Python. O software permite o cadastro, consulta, atualização e remoção de produtos através de uma interface de linha de comando (CLI).

**Funcionalidades**

Adicionar Item: Cadastra novos produtos validando código, nome, quantidade e preço.
Listar Itens: Exibe todos os produtos atualmente armazenados.
Atualizar Quantidade: Permite alterar o estoque de um produto existente.
Remover Item: Exclui permanentemente um produto.
Buscar Item: Localiza informações detalhadas de um produto.

**Requisitos**

Para rodar este projeto, você precisará de:
Python 3
O módulo estoque.py (responsável pelas operações de banco de dados).

**Estrutura de Arquivos**

main.py: Contém a lógica do menu principal e as validações de entrada de usuário.
estoque.py: Deve conter as funções criar_banco(), adicionar_item(), listar_itens(), atualizar_quantidade(), remover_item() e buscar_item().

**Como usar**

-  Certifique-se de que os arquivos main.py e estoque.py estão na mesma pasta.
-  Abra o terminal ou prompt de comando.
-  Execute o comando: python main.py
    
**Validações de Dados**

O sistema conta com proteções contra entradas inválidas:
- Impede códigos vazios ou negativos.
- Garante que o código seja um número inteiro (sem vírgulas ou pontos).
- Garante que o nome do item não esteja em branco.
- Trata erros de tipo (ValueError) para entradas numéricas de preço e quantidade.
