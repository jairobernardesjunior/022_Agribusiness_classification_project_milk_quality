## Projeto compliance default

### Problem:
The total annual loans in Brazil is around R$ 5.3 trillion making this modality one of the most active in the financial sector. On this amount, the interest rate applies which represents the part of the profitability of the business. Thus, for success in this operation, it is necessary, logically, for the lender to receive faithfully the due interest and the borrowed amount. The certainty of receiving the profits and the loan amount must be ensured before the deal is closed..

O total de empréstimos anual no Brasil está em torno de R$ 5,3 trilhões tornando essa modalidade uma das mais ativas no setor financeiro. Sobre esse montante incide a taxa de juros que representa a parte da lucratividade do negócio. Assim para que se tenha sucesso nessa operação faz-se necessário, logicamente, para quem empresta, receber fielmente os juros devidos e o montante emprestado. A certeza de receber os lucros e o montante do empréstimo deve ser assegurado antes do negócio ser fechado.

### Motivation:
The need to know whether a loan will be duly received in full, with interest and adjustments, leads companies that work with lending money to look for ways to anticipate whether the borrower has the conditions and profile capable of faithfully repaying the amount borrowed. To this end, the company granting the loan needs to be aware of two fundamental issues for its security: knowing the percentage level of the borrower's risk and knowing, based on the level of this risk, whether or not to lend the negotiated amount.

A necessidade de saber se um empréstimo será recebido devidamente em sua integralidade, com juros e correção, leva as empresas que trabalham emprestando dinheiro, procurar meios de antecipar se o tomador do empréstimo tem condições e um perfil capaz de pagar, com fidelidade, o valor tomado. Para isso a empresa que cede o empréstimo precisa estar a par de duas questões fundamentais para sua segurança: saber qual o nível percentual do risco do tomador e saber, conforme o nível desse risco, se empresta ou não o valor negociado.

### Solution:
Using the company's own financial loan data, we will conduct an in-depth study and adaptation of this data. Several machine learning models, such as deep learning, will be trained, defining and choosing the model that best generalizes in the definition of defaulters and reveals the percentage level of risk of making a certain loan to a specific person. This will enable and support the financial loan team to make the best decision regarding the security percentage of that loan, reducing default events against the company.

Através de dados de empréstimos financeiros da própria empresa, faremos um estudo profundo e adequação desses dados. Será feito o treinamento de vários modelos de machine learning, como de deep learning, definindo e elegendo o modelo que melhor generaliza na definição do inadimplente e revela o nível percentual do risco de se fazer um determinado empréstimo para uma pessoa específica. Isso possibilitará e apoiará a equipe de empréstimos financeiros a tomar a melhor decisão com relação ao percentual de segurança daquele empréstimo, reduzindo os eventos de inadimplência contra a empresa.

### Objective:
- The objective of this work is to train a classification model that can inform us whether a person may default on a financial loan.

- Nesse projeto vamos para a fase investigatória do Milk_Diagnostic (aparelho de coleta e envio de dados do leite na fazenda via sms), vamos fazer uma classificação, utilizando modelos de machine learning, para demonstrar se a variação de temperatura indica alguma anomalia ou não de contaminaçao no leite que está armazenado no tanque da fazenda, aguardando ser recolhido.

### Data Origin:
- Dataset: https://www.kaggle.com/datasets/itssuru/loan-data

- Publicly available data from LendingClub.com. Lending Club connects people who need money (borrowers) with people who have money (investors). Fortunately, as an investor, you would want to invest in people who show a profile of having the security of paying you back.

- Dados disponíveis publicamente do LendingClub.com. O Lending Club conecta pessoas que precisam de dinheiro (tomadores de empréstimo) com pessoas que têm dinheiro (investidores). Felizmente, como investidor, você gostaria de investir em pessoas que mostrassem um perfil de ter a segurança de pagar você de volta.

- Aqui está o que as colunas representam:

    credit.policy: 1 se o cliente atender aos critérios de subscrição de crédito do LendingClub.com e 0 caso contrário.

    purpose: O propósito do empréstimo (assume os valores "credit_card", "debt_consolidation", "educational", "major_purchase", "small_business" e "all_other").

    int.rate: A taxa de juros do empréstimo, como uma proporção (uma taxa de 11% seria armazenada como 0,11). Os mutuários considerados pelo LendingClub.com como mais arriscados recebem taxas de juros mais altas.

    installment: As parcelas mensais devidas pelo mutuário se o empréstimo for financiado.

    log.annual.inc: O logaritmo natural da renda anual autodeclarada do mutuário.

    dti: A relação dívida/renda do mutuário (valor da dívida dividido pela renda anual).

    fico: A pontuação de crédito FICO do mutuário.

    days.with.cr.line: O número de dias em que o mutuário teve uma linha de crédito.

    revol.bal: Saldo rotativo do mutuário (valor não pago no final do ciclo de cobrança do cartão de crédito).

    revol.util: Taxa de utilização da linha rotativa do mutuário (o valor da linha de crédito usada em relação ao crédito total disponível).

    inq.last.6mths: Número de consultas do mutuário por credores nos últimos 6 meses.

    delinq.2yrs: Número de vezes que o mutuário atrasou um pagamento em mais de 30 dias nos últimos 2 anos.

    pub.rec: Número de registros públicos depreciativos do mutuário (declarações de falência, penhoras fiscais ou julgamentos).

    not.fully.paid: O empréstimo não foi totalmente pago.
