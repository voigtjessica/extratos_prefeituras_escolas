# extratos_prefeituras_escolas

Trabalhando com dados dos extratos das contas bancárias de prefeituras municipais criadas para movimentações bancárias para construção de escolas e creches financiadas pelo FNDE

O script serve para deixar o arquivo original de acordo com as orientações do TCU (órgão que forneceu a planilha à Transparência Brasil). Segundo o órgão:

a. A ligação entre os Dados do Simec com o Extrato deve ser feito por CNPJ, BANCO , AGENCIA E CONTA

b. Em extrato, os campos com prefixo beneficiário, referem-se aquelas empresas que receberam pagamentos

c. Valores de aplicações e resgates financeiros não devem ser considerados i. Textos do campo histórico na plainha extrato ii. 'Poupança', 'BB FIX', 'APLICAÇÃO', 'CDB', 'RESGATE', 'TARIFA'

    (que foram retirados com o filter) 

d. Existem casos em que há mais de uma obra na mesma conta bancária.
