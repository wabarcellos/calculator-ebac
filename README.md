Calculadora Inteligente 🔢
Aluna: Walessa Barcellos

Este repositório contém o código de uma calculadora inteligente que foi desenvolvida utilizando dois scripts: um em Shell Script (.sh) e outro em Python.

Como Executar o Script
Executando o Script Shell (.sh):
Para rodar o script .sh, siga os passos abaixo:

Abra o terminal.
Navegue até o diretório onde o arquivo calculadora.sh está salvo.
Torne o script executável com o comando:
chmod +x calculadora.sh
Execute o script utilizando o seguinte comando:
./calculadora.sh
Isso iniciará o script da calculadora inteligente no seu terminal. Siga as instruções exibidas para realizar as operações matemáticas.

Executando o Código Python:
Para rodar o script Python, basta seguir os passos abaixo:

Abra o terminal.
Navegue até o diretório onde o arquivo calculadora.py está salvo.
Execute o script com o comando:
python3 calculadora.py
O código Python permite que você escolha qual operação matemática realizar, como adição, subtração, multiplicação e divisão. A interação com o usuário é feita através da linha de comando.

Descrição do Código
Script Shell (calculadora.sh):
O script em Shell realiza operações matemáticas básicas no terminal utilizando comandos de shell. O fluxo do programa é o seguinte:

O usuário é solicitado a inserir dois números (inteiros ou decimais) através do comando read.
O script oferece opções para o usuário escolher qual operação matemática deseja realizar, como adição, subtração, multiplicação ou divisão.
O programa valida a entrada do usuário e executa a operação escolhida, exibindo o resultado na tela usando o comando echo.
O programa permite que o usuário realize várias operações consecutivas até que ele decida encerrar o processo.
Script Python (calculadora.py):
O script Python foi desenvolvido para realizar operações matemáticas simples de forma interativa. O funcionamento é o seguinte:

O código utiliza a função input() para receber números do usuário. Os valores são convertidos para o tipo apropriado (int ou float).
O usuário escolhe qual operação deseja realizar: adição, subtração, multiplicação ou divisão.
O programa utiliza uma estrutura de repetição para permitir que o usuário faça várias operações em sequência, se desejar.
Ao final de cada operação, o resultado é mostrado na tela com a função print().
O código possui um controle de fluxo para garantir que a entrada do usuário seja válida, oferecendo uma experiência interativa simples e eficaz.
Exemplo de Execução
Shell Script:
O script pede ao usuário para inserir dois números:
Insira o primeiro número: 5
Insira o segundo número: 3
O usuário escolhe a operação:
Escolha uma operação:
1. Adição
2. Subtração
3. Multiplicação
4. Divisão
O resultado é exibido:
O resultado da adição é: 8
Python:
O script solicita a inserção dos números e da operação desejada:
Insira o primeiro número: 5
Insira o segundo número: 3
Escolha a operação (+, -, *, /): +
O resultado é exibido:
Resultado: 8
