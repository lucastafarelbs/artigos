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
  Generators é o recurso que nos permite pausar e continuar a execução de
  funções assíncronas, de acordo com nossa necessidade, na prática, é o que
  nos permite executar funções assíncronas "como se fossem" executadas de maneira
  síncrona

### Quando utilizar generators?
  //essa parte precisa melhorar
  O uso de generators pode ser aplicado, quando vamos executar uma função que
  DEPENDE da resposta de outra e só encadear não é o suficiente.


### Como utilizar?
  // yield e yield


  // Exemplo do meu code

### Nem tudo são flores :S
  Utilizar generators prejuda muito a velocidade de execução do nosso código.
  Por que ?
  Existe vantagem em utilizar generators?

### Conclusão

## Referências
[strongloop.com](https://strongloop.com/strongblog/how-to-generators-node-js-yield-use-cases/)
