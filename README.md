# shift
um sistema que controla os movimentos financeiros

A difirença desse sistema com os muito outros de "controle financeiro" que ja existe é que ele é focado na transação em sí.


Não focando no saldo total, não importando no final das contas, mas apenas nas transações, para saber como ta chegando e saindo o suado dinheiro.


O sistema deve permitir um laçamento de "Correção de saldo" onde é atualizado o saldo que o sistema calculou baseado nos gasto com o saldo real da suas contas.


Esse laçamento é especial para vc descobrir quanto foi movimentado sem saber para onde ter ido. Analizando o montante que não foi rastreado é possivel criar uma consiencia dos gastos não planejado que poderiam ser desnecessarios.


O sistema deve permitir que todos os gasto sejam categorizados em 0..n categorias que são criadas dinamicamentes. Assim é possivel rastrear a transação do dinheiro.


O sistema tem que permir se criar contas. As contas possuem saldo. Cada transação altera o valor do saldo da conta, gerando o "saldo gerado"(mudar esse nome?). Então temos dois saldos possivel, o saldo gerado e o saldo real. O saldo real é informado pelo usuario e o gerado é calculado a partir das transações de um saldo.
