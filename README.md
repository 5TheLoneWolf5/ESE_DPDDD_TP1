# Diagrama de Classes UML

<img src="Library UML Diagram.jpg" width="1300" height="1300">

## Justificativa para os Padrões utilizados:

- Factory Method para a criação de diferentes tipos de itens da biblioteca (livros, DVDs).
- Singleton para garantir uma única instância da classe Library.
- Facade para simplificar as interações entre os clientes do sistema e as operações internas da biblioteca.
- Observer para notificar sobre mudanças de status, como empréstimos vencidos.
- Strategy para encapsular diferentes algoritmos de busca para livros, usuários e outros itens.
