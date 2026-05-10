# Diagrama de Classes UML

<img src="Library UML Diagram.jpg" width="1300" height="1300">

## Justificativa para os Padrões utilizados:

- Factory Method -> para a criação de diferentes tipos de itens da biblioteca (como livros e DVDs).
- Singleton -> a classe Library só pode conter uma única instância, simplificando e centralizando seu uso.
- Facade -> simplificação das interações entre os clientes do sistema e as operações internas da biblioteca.
- Observer -> notificação sobre mudanças de empréstimos vencidos.
- Strategy -> para estabelecer um contrato e implementar diferentes algoritmos de busca para usuários e itens.
