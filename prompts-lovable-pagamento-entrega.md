# Prompts Lovable: Pagamento, Entrega e Pós-venda

Use estes prompts no projeto Lovable criado nas aulas anteriores. Eles devem simular e estruturar o fluxo com segurança. Não peça ao Lovable para coletar dados reais de cartão diretamente no app.

## 1. Project Knowledge

```text
Este projeto é uma loja online de [produto] para [público].
O produto é [físico/digital/serviço/assinatura].
O objetivo da próxima versão é completar a jornada do pedido: resumo, pagamento seguro, entrega, rastreamento e pós-venda.

Regras:
- manter a identidade visual já criada;
- não coletar dados reais de cartão dentro do app;
- usar link de pagamento externo ou QR Code Pix ilustrativo;
- explicar que o pagamento é processado por plataforma segura;
- mostrar status e próximas ações;
- criar uma experiência clara para cliente e vendedor.
```

## 2. Módulo de Resumo do Pedido

```text
Crie uma seção de resumo do pedido.
Ela deve mostrar:
- produto;
- variação;
- quantidade;
- preço;
- frete;
- prazo estimado;
- total;
- botão para escolher forma de pagamento.

O visual deve ser limpo, responsivo e coerente com a loja.
```

## 3. Seleção de Pagamento

```text
Crie uma etapa de seleção de pagamento com as opções:
- Pix QR Code;
- Link de pagamento;
- Cartão via checkout seguro externo;
- Boleto, se fizer sentido para o produto.

Para cada opção, explique em uma frase:
- quando usar;
- tempo de confirmação;
- cuidado principal.

Não crie formulário de cartão dentro do app.
```

## 4. QR Code Pix Ilustrativo

```text
Crie um bloco de pagamento Pix com QR Code ilustrativo e botão "Copiar código Pix".
Mostre também:
- valor;
- nome do pedido;
- prazo de expiração;
- status inicial como "aguardando pagamento".

Inclua aviso: "Este é um modelo visual para aula. Em uma operação real, o QR Code deve ser gerado pela plataforma de pagamento."
```

## 5. Link de Pagamento Externo

```text
Crie um botão de link de pagamento externo.
O botão deve indicar que o cliente será direcionado para uma página segura de pagamento.

Inclua campos simulados:
- plataforma escolhida;
- valor;
- validade do link;
- status do pedido.

Texto do botão: "Pagar em ambiente seguro".
```

## 6. Status de Pagamento

```text
Crie um painel de status de pagamento com:
- pendente;
- aprovado;
- recusado;
- expirado;
- reembolsado.

Para cada status, mostre:
- significado;
- próxima ação da loja;
- mensagem para o cliente.
```

## 7. Modelo de Entrega Física

```text
Crie uma seção de entrega para produto físico.
Inclua:
- retirada local;
- entrega própria;
- Correios;
- transportadora;
- fulfillment.

Para cada modelo, mostre:
- quando usar;
- ponto forte;
- cuidado operacional;
- impacto no prazo e na margem.
```

## 8. Modelo de Entrega Digital

```text
Crie uma seção de entrega para produto digital.
Inclua:
- envio por e-mail;
- link de download;
- acesso em área de membros;
- licença ou chave de acesso;
- suporte de acesso.

Mostre que a liberação deve ocorrer somente após pagamento confirmado.
```

## 9. Frete e Margem

```text
Crie um comparador de estratégias de frete:
- frete calculado;
- frete fixo;
- frete grátis embutido no preço;
- frete grátis acima de valor mínimo.

Para cada estratégia, mostre:
- benefício comercial;
- risco para margem;
- quando usar.
```

## 10. Rastreamento e Pós-venda

```text
Crie uma página ou seção de pós-venda.
Ela deve mostrar:
- pedido recebido;
- em separação;
- enviado;
- em rota;
- entregue;
- problema ou suporte.

Para cada status, inclua uma mensagem automática para o cliente e uma próxima ação da loja.
Inclua também pedido de avaliação, recompra e política de troca.
```

## 11. Prompt Mestre

```text
Atue como especialista em e-commerce, checkout seguro, logística e pós-venda.

Minha loja no Lovable vende [produto] para [público].
O produto é [físico/digital/serviço/assinatura].
O canal principal de venda é [canal].

Crie ou refatore no meu projeto Lovable um módulo final de pedido com:
- resumo do pedido;
- seleção de meio de pagamento;
- botão de link de pagamento externo;
- QR Code Pix ilustrativo;
- mensagem de segurança explicando que dados sensíveis são processados pela plataforma de pagamento;
- status de pagamento: pendente, aprovado, recusado, expirado e reembolsado;
- modelo de entrega adequado ao produto;
- status de entrega ou acesso digital;
- política de troca, devolução ou suporte;
- mensagem de pós-venda e pedido de avaliação.

Meio de pagamento escolhido: [meio].
Plataforma considerada: [PagBank/PagSeguro, Mercado Pago, Stripe ou outra].
Modelo de entrega escolhido: [modelo].
Estratégia de frete: [modelo de frete].

Critérios de qualidade:
- não coletar cartão diretamente no app;
- deixar claro onde o pagamento acontece;
- mostrar próximas ações para cada status;
- explicar prazo, rastreio ou acesso;
- manter identidade visual da loja;
- ser responsivo e fácil de apresentar em sala.
```

