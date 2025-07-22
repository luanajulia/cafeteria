# Sistema de Pedidos para Cafeteria
## Cenário do Problema
Imagine uma cafeteria que quer modernizar seu sistema de pedidos. Os clientes podem fazer pedidos online, a cafeteria precisa processá-los, notificar os clientes sobre o status do pedido e oferecer diferentes formas de pagamento.

## Design Patterns que Vamos Aplicar <br>
- Singleton: Para garantir que haja apenas uma instância do processador de pedidos (ou do caixa), pois só um pode gerenciar todos os pedidos da cafeteria.

- Factory Method: Para criar diferentes tipos de bebidas (Café, Chá, Suco) sem expor a lógica de criação ao cliente.

- Observer: Para notificar os clientes (observadores) sobre mudanças no status do pedido (sujeito).

- Strategy: Para permitir que o sistema use diferentes estratégias de pagamento (Cartão de Crédito, Pix, Dinheiro) de forma intercambiável.
