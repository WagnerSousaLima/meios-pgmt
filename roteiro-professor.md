# Roteiro do Professor: Aulas 6 e 7

Tema: configuração conceitual e prática de meios de pagamento online seguros, links de pagamento, QR Codes, plataformas como PagBank/PagSeguro, Mercado Pago e Stripe, modelos de entrega física e digital, logística, rastreamento e pós-venda.

Este roteiro acompanha os slides do `index.html`. Os slides são para os alunos. Este arquivo é para condução da aula.

## Intenção pedagógica

Nas aulas anteriores, os alunos criaram e evoluíram uma loja no Lovable. Agora o projeto precisa completar a jornada real do e-commerce:

1. cliente escolhe produto;
2. entende preço e frete;
3. paga com segurança;
4. recebe confirmação;
5. acompanha entrega ou acesso digital;
6. tem suporte, troca, reembolso ou pós-venda.

O ponto mais importante: não ensinar o aluno a "inventar um sistema de pagamento" inseguro. A aula deve mostrar que projetos iniciantes usam plataformas especializadas para processar pagamentos e que o Lovable pode representar o fluxo, orientar o cliente e integrar por link, QR Code ou simulação didática.

## Objetivos

- Revisar a loja Lovable criada nas aulas anteriores.
- Explicar meios de pagamento online com vocabulário acessível.
- Diferenciar Pix manual, link de pagamento, QR Code, checkout hospedado, plugin e API.
- Mostrar por que não se deve coletar cartão diretamente no app.
- Comparar usos de PagBank/PagSeguro, Mercado Pago e Stripe.
- Relacionar status de pagamento com próximas ações.
- Ensinar modelos de entrega física, digital, serviço e assinatura.
- Planejar frete, rastreamento, troca, devolução e pós-venda.
- Finalizar com um Prompt Mestre para criar o módulo final no Lovable.

## Condução sugerida

Tempo total: 2 aulas.

- Retomada do projeto Lovable: 10 min.
- Vocabulário e segurança de pagamento: 20 min.
- Links, QR Code e plataformas: 30 min.
- Aplicação no Lovable: 20 min.
- Modelos de entrega e frete: 30 min.
- Rastreamento, troca e pós-venda: 20 min.
- Atividade final individual: 30 min.

Todas as atividades são individuais.

## Slide 1: Pagamento e entrega fecham a venda

Fala sugerida:

"Uma loja bonita ainda não é uma loja completa. Se o cliente não consegue pagar com segurança e não entende como vai receber, a venda quebra no momento mais importante."

Aprofundamento:

Mostre que pagamento e entrega são partes da promessa comercial. O botão "comprar" só funciona bem quando o cliente acredita no caminho depois dele.

## Slide 2: Retomada do projeto

Fala sugerida:

"Até aqui, o projeto já tem produto, oferta, marketplace e gestão. Agora vamos colocar a parte que transforma intenção em pedido: pagamento e entrega."

Pergunta:

"Na sua loja atual, o que acontece depois que o cliente decide comprar?"

Se muitos alunos responderem "manda WhatsApp", conecte com a aula:

"Ótimo. Mesmo no WhatsApp, ainda precisamos de link de pagamento, confirmação, prazo, entrega e pós-venda."

## Slide 3: Vocabulário de pagamento

Explique os termos com exemplos:

- Checkout: a etapa de finalização da compra.
- Link de pagamento: uma cobrança pronta em uma página externa.
- QR Code: um caminho escaneável para pagamento.
- PSP: plataforma que processa pagamento.
- Webhook: aviso automático de mudança de status.
- Conciliação: conferir pedido, pagamento, taxa e repasse.
- Chargeback: contestação de pagamento.
- Reembolso: devolução do dinheiro.

Fala sugerida:

"Não precisamos decorar palavra difícil. Precisamos saber que decisão ela muda."

## Slide 4: Regra de segurança

Fala sugerida:

"A regra de ouro da aula: projeto iniciante não coleta cartão direto. O aluno pode criar a experiência, mas o pagamento real deve acontecer em plataforma segura."

Aprofundamento:

Explique que coletar dados de cartão envolve requisitos técnicos e de segurança muito mais altos. Para aula e pequenos projetos, o mais adequado é redirecionar para checkout hospedado, link de pagamento, plugin confiável ou integração bem feita.

Frase útil:

"No Lovable, a gente desenha o fluxo e orienta o cliente. Quem processa dinheiro é a plataforma de pagamento."

## Slide 5: Escada de maturidade

Fala sugerida:

"Nem todo mundo precisa começar no nível API. O importante é escolher o nível certo para o estágio do negócio."

Explique:

- Pix manual: simples, mas com conferência manual.
- Link de pagamento: ótimo para começar.
- QR Code: prático para Pix e presencial.
- Plugin: bom para lojas em plataformas prontas.
- API: melhor quando há volume e necessidade de automação.

## Slide 6: Link, QR ou checkout

Fala sugerida:

"O formato do pagamento depende da situação de compra."

Exemplos:

- Venda pelo WhatsApp: link de pagamento.
- Venda presencial: QR Code.
- Loja com catálogo: checkout hospedado.
- Sistema mais avançado: API com webhooks.

Pergunta:

"Para o produto de vocês, o cliente compra mais por impulso, comparação, orçamento ou recorrência?"

## Slide 7: PagBank / PagSeguro

Fala sugerida:

"O PagBank oferece checkout e link de pagamento, permitindo enviar o cliente para uma página segura. Isso tira do projeto a responsabilidade de lidar diretamente com dados sensíveis."

Ponto didático:

Explique o fluxo:

1. loja define pedido;
2. checkout ou link é gerado;
3. cliente paga no ambiente da plataforma;
4. status retorna ou é consultado;
5. loja prepara entrega.

## Slide 8: Mercado Pago

Fala sugerida:

"Mercado Pago é forte no contexto brasileiro e latino-americano. Pode aparecer como link, Pix, QR Code, plugin ou integração por API."

Aprofundamento:

Explique que plugins são mais acessíveis para quem não programa; APIs entram quando existe necessidade de controle de status, notificações e automação.

## Slide 9: Stripe

Fala sugerida:

"Stripe é muito usado em produtos digitais, SaaS, assinaturas e operações internacionais. Payment Links e Checkout ajudam a criar pagamento sem construir tudo do zero."

Ponto didático:

Mostre que Payment Links são bons para começar e Checkout/API entram quando o fluxo precisa de mais controle.

## Slide 10: Matriz de decisão

Fala sugerida:

"Não existe melhor plataforma em abstrato. Existe melhor escolha para contexto, canal, risco, volume e experiência do cliente."

Atividade rápida:

Cada aluno escolhe uma linha da matriz mais parecida com o próprio produto e justifica.

## Slide 11: Lovable e pagamento

Fala sugerida:

"O que vamos construir no Lovable não é um processador de pagamento. É um módulo de checkout didático e seguro: resumo do pedido, escolha de meio, botão externo, QR ilustrativo e status."

Importante:

Reforce que QR Code e links reais devem vir da plataforma de pagamento. No projeto da aula, eles podem ser demonstrativos.

## Slide 12: Status de pagamento

Fala sugerida:

"Status de pagamento evita dois erros graves: entregar sem receber e abandonar cliente que tentou pagar e falhou."

Aprofundamento:

Explique cada status:

- Pendente: precisa orientar.
- Aprovado: pode preparar entrega.
- Recusado: oferecer outro meio.
- Expirado: gerar nova cobrança.
- Reembolsado: registrar e encerrar corretamente.

## Slide 13: Entrega

Fala sugerida:

"Entrega é parte da oferta. Se eu prometo rapidez, preciso ter logística. Se vendo digital, preciso liberar acesso. Se vendo serviço, preciso agendar."

Pergunta:

"O produto de vocês é físico, digital, serviço ou assinatura? Cada resposta muda o pós-pagamento."

## Slide 14: Modelos de entrega física

Explique:

- Retirada local: bom para negócio regional.
- Entrega própria: bom para proximidade, mas custa tempo.
- Correios: alcance nacional.
- Transportadora: útil para volume, peso ou prazos específicos.
- Fulfillment: quando a operação ganha escala.

Frase útil:

"Frete não é só entrega. Frete é custo, prazo, promessa e reputação."

## Slide 15: Entrega digital

Fala sugerida:

"Produto digital parece simples porque não tem caixa, mas tem outro tipo de risco: acesso, link quebrado, e-mail errado, licença, suporte."

Aprofundamento:

Mostre que produto digital deve ser liberado após pagamento confirmado e precisa de instrução clara.

## Slide 16: Estratégia de frete

Fala sugerida:

"Frete grátis nunca é grátis para a loja. Ele pode ser uma boa estratégia, mas precisa estar dentro do preço ou da margem."

Explique:

- Frete calculado pode assustar.
- Frete fixo simplifica, mas pode dar prejuízo.
- Frete grátis aumenta desejo, mas precisa ser pago pela margem.
- Frete grátis acima de valor mínimo pode elevar ticket médio.

## Slide 17: Rastreamento

Fala sugerida:

"O cliente ansioso pergunta menos quando a loja mostra o status antes dele perguntar."

Mostre o ciclo:

Pedido recebido -> em separação -> enviado -> em rota -> entregue -> pós-venda.

## Slide 18: Troca e logística reversa

Fala sugerida:

"Política de troca não é só defesa jurídica. Ela também vende, porque aumenta confiança."

Explique:

O cliente compra com menos medo quando entende o que acontece se algo der errado.

## Slide 19: Arquitetura final no Lovable

Fala sugerida:

"Agora a loja de vocês vira uma simulação completa: produto, pedido, pagamento, entrega e pós-venda."

Oriente:

O aluno deve criar componentes para cada etapa, sem coletar dados reais sensíveis.

## Slide 20: Prompt Engineering

Fala sugerida:

"Prompt bom aqui não pede: crie uma tela de pagamento bonita. Ele pede contexto, regras de segurança, estados, mensagens, entrega e critérios de qualidade."

Aprofundamento:

Prompt maduro é especificação de produto. Ele precisa dizer:

- o que o sistema deve mostrar;
- o que não pode fazer;
- quais estados existem;
- como o cliente será orientado;
- como o vendedor acompanha.

## Slide 21: Atividade final

Entrega individual:

1. Escolha do meio de pagamento.
2. Justificativa da escolha.
3. Fluxo de pagamento e status.
4. Política de segurança.
5. Modelo de entrega.
6. Estratégia de frete ou acesso digital.
7. Rastreamento e pós-venda.
8. Prompt Mestre para Lovable.

## Slide 22: Fechamento

Fala sugerida:

"Uma loja madura não termina no botão comprar. Ela recebe, confirma, entrega, acompanha e cuida do cliente depois."

Feche com:

"Vender online é prometer, receber, entregar e cuidar. O projeto final de vocês precisa mostrar esse caminho inteiro."

## Critérios de avaliação

- O aluno escolheu meio de pagamento adequado ao canal.
- O projeto evita coleta insegura de dados.
- O fluxo mostra status de pagamento.
- A entrega combina com o tipo de produto.
- O frete ou acesso digital está explicado.
- Existe rastreamento ou acompanhamento.
- O pós-venda inclui avaliação, suporte ou troca.
- O Prompt Mestre é claro, completo e aplicável no Lovable.

