# Calculadora_SpringBoot

Este é um repositório que contém a implementação de uma calculadora em Java e Spring Boot. 

# Descrição 

• A interface da calculadora é uma página web acessível através do navegador.

• A página web possui campos de entrada para dois números (num1 e num2) e um menu suspenso para selecionar a operação desejada (operation).

Processamento da Operação:

• Os valores dos campos num1, num2, e operation são enviados para o controlador Spring Boot quando o formulário é enviado.

• O controlador realiza a operação matemática correspondente (adição, subtração, multiplicação ou divisão).

Tratamento de Erros:

• São realizadas verificações adicionais para tratar casos especiais, como divisão por zero

• Se houver erros durante o processo (por exemplo, divisão por zero), mensagens de erro apropriadas são exibidas na interface para informar o usuário.

# Tecnologias Utilizadas 

A aplicação utiliza o framework Spring Boot para o desenvolvimento do lado do servidor e Thymeleaf como mecanismo de template para a criação de páginas HTML dinâmicas.
