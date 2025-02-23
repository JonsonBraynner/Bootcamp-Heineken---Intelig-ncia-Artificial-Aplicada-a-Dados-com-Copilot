# Modelo de Base de dados para E-Commerce

Este modelo é baseado no desafio proposto no bootcamp de Inteligência Artificial Aplicada a Dados com Copilot da DIO, no qual deveria ser feito os seguintes refinamentos:
- Cliente PJ e PF – Uma conta pode ser PJ ou PF, mas não pode ter as duas informações;
- Pagamento – Pode ter cadastrado mais de uma forma de pagamento;
- Entrega – Possui status e código de rastreio;

### Neste modelo
- Na tabela Cliente será salvo o número do documento, sendo que, para diferenciar o CPF do CNPJ será salvo também a que tipo de documento o número se refere.
- Na tabela Pagamento, um cliente poderá ter um ou mais meios de pagamento, porém cada pedido pode utilizar somente um.
- Na tabela Frete serão armazenadas informações de entrega, foi adicionado também o nome da transportadora e a previsão de entrega. Cada frete poderá estar relacionado a somente um pedido e vice-versa.
