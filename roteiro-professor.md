# Roteiro do Professor: Aula 6

Tema: pagamento online seguro, links de pagamento, QR Code, plataformas como PagBank/PagSeguro, Mercado Pago e Stripe, entrega, rastreamento e pós-venda.

## Objetivo da aula

Completar o projeto criado no Lovable com uma solução possível no plano gratuito. A loja já tem produto, oferta e visual; agora precisa mostrar como o cliente paga por Pix/QR Code, envia comprovante, recebe e é atendido depois da compra.

## Tempo sugerido

- Revisão do projeto Lovable: 10 min.
- Pagamento seguro e Pix/QR Code: 25 min.
- Peculiaridades dos meios de pagamento: 15 min.
- Entrega e pós-venda: 25 min.
- Atividade final no Lovable: 35 min.

## Condução por blocos

### 1. Revisão

Fala sugerida:

"Até aqui a loja já apresenta o produto. Hoje vamos fechar a parte operacional: como o cliente paga, como a loja confirma, como entrega e como cuida do pós-venda."

Pergunta:

"No seu projeto atual, o que acontece depois que o cliente decide comprar?"

### 2. Pagamento seguro

Explique de forma direta:

- O app do aluno não deve coletar cartão diretamente.
- Não teremos backend nesta aula.
- O caminho principal será Pix/QR Code para economizar créditos e manter a prática viável.
- O Lovable deve mostrar o fluxo, orientar o cliente e explicar a confirmação manual.

Termos essenciais:

- Checkout: etapa de finalizar compra.
- Pix QR Code: pagamento rápido e barato, mas sem backend exige conferência manual.
- Pix Copia e Cola: útil quando o cliente está no celular e não consegue escanear a própria tela.
- Link de pagamento: cobrança por URL, mais formal, geralmente com taxas.
- Checkout/cartão: mais conveniência e parcelamento, mas maior custo e risco de chargeback.
- Status: nesta aula é teoria operacional, não automação.

Frase útil:

"No Lovable desenhamos a experiência. Nesta versão gratuita, o Pix e o comprovante resolvem a prática sem fingir integração."

### 3. Plataformas

Explique sem alongar:

- PagBank/PagSeguro: referência brasileira para link, checkout e meios populares.
- Mercado Pago: muito usado com Pix, QR Code, plugins e checkout.
- Stripe: forte em Payment Links, checkout e assinaturas.

Ponto-chave:

"Para a aula, usamos Pix/QR como solução viável. As plataformas entram como próximos níveis quando a loja precisar de checkout, cartão, parcelamento, links reais ou automação."

### 4. Entrega

Explique os modelos:

- Produto físico: frete, embalagem, prazo, rastreio e troca.
- Produto digital: link, e-mail, acesso, licença e suporte.
- Serviço: agendamento, confirmação e remarcação.
- Assinatura: cobrança recorrente, acesso e cancelamento.

Frase útil:

"Entrega é parte da promessa de venda. Se o prazo ou acesso não está claro, a confiança cai."

### 5. Pós-venda

Pontos essenciais:

- Rastreamento reduz ansiedade.
- Política de troca aumenta confiança.
- Suporte evita reclamação.
- Avaliação e recompra fecham o ciclo.

## Atividade final

Cada aluno deve criar no Lovable uma central de pedido sem backend com:

1. resumo do pedido;
2. Pix QR Code ilustrativo;
3. Pix Copia e Cola;
4. instrução para enviar comprovante;
5. status explicados apenas como teoria;
6. entrega ou acesso digital;
7. suporte, troca e avaliação;
8. Prompt Mestre final.

## Critérios de avaliação

- O Pix/QR Code está bem explicado para o cliente.
- O projeto não coleta cartão diretamente.
- O aluno deixa claro que status não é automático nesta versão.
- A entrega é compatível com o tipo de produto.
- O pós-venda está claro.
- O prompt final é específico e aplicável no Lovable.
