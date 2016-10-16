# Artigo sobre generators

## Explanação sobre o problema
    No Node.js® os eventos são executados iniciados a cada iteração do loop de eventos,
  e são executados assincronamente nos manipuladores de evento, esse comportamento
  torna as execuções mais performáticas, otimiza o processamento e causa no usuário a
  sensação de que tudo está acontecendo "ao mesmo tempo", [mais informações podem ser
  encontradas aqui](https://www.tutorialspoint.com/nodejs/nodejs_event_loop.htm).

    Porém, em certas ocasiões é necessário tratar de maneira específica o
  comportamento de determinada função, para esses casos, podemos lançar mão dos
  generators, que nos permitem definir comportamentos específcos nas iterações do
  loop de eventos.

### O que são generators?

### Quando utilizar generators?

### Como Utilizar?

## Referências
[strongloop.com](https://strongloop.com/strongblog/how-to-generators-node-js-yield-use-cases/)
