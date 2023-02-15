# HTML e CSS
<hr>

#### 1° tópico: O que significa cada linha quando você cria um arquivo HTML?
  * Você programador já deve ter percebido que quando você cria um novo arquivo HTML, ele gera automaticamente uma estrutura básica para que você tenha um início de código. 
  Mas você ja parou pra pensar o que cada uma dessa linha significam? Nesse começo irei mostrar pra você o significado dela.
  * Ao digitar um ponto de exclamação "!" em um arquivo html esse seguinte código é gerado automaticamente:
    ```html
    <!DOCTYPE html> 
     <html lang="pt-br"> 
      <head>
        <meta charset="UTF-8">  
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Aprendendo HTML e CSS</title> 
      </head>
       <body>
     
       </body>
    </html>
    ```
   * Mas o que cada linha significa?
     * ```html 
        <!DOCTYPE html>
       ```
        * Serve para informar qual versão do html estamos usando.
     * ```html 
        <html lang="pt-br">
       ```
        *  A ideia do uso dele é normatizar e indicar os tipos de dados pra quem tiver interesse, se não houver esse atributo plugins, google tradutor ou buscadores irão ter dificuldades em detectar o idioma do texto apresentado.
     * ```html 
        <meta charset="UTF-8">
       ```
        * A tag meta serve para passar as informações para o navegador. Já a propriedade charset é um dicionário que possui todas as linguagens. Um exemplo é que no inglês não temos acento nem "Ç", esse dicionário uni a maioria das linguas permitindo a existência de diversos caracteres e que os demais usuários vejam o site com o dicionário correto.
     * ```html 
        <title>Aprendendo HTML e CSS</title>
       ```
        * Permite escolher o nome da página.
     * ```html 
        <head></head>
       ```
        * Informações que passamos pro navegador.
     * ```html 
        <body></body>
       ```
        * Informações que quermos exibir na página.
<hr>

#### 2° tópico: Formas de estilização ####
  * Ao escrever um código HTML, conforme você vai desenvolvendo as tags elas vão ficando de um formato padrão do HTML, mas temos uma maneira de estilizar para assim seu projeto ficar do jeito que você quiser.
  * Para isso utilizamos o CSS (Cascading Style Sheet, ou Folha de Estilo em Cascatas) que são basicamente linhas de códigos que atribuem algumas características as tags.
  * Dentro do CSS temos 3 tipos de estilização: 
    * CSS Inline: Na linha em que temos a nossa tag, adicionamos a propriedade do CSS. O CSS inline é usado para dar estilo a um elemento HTML específico. Para este estilo de CSS< você somente vai precisar adicionar o atributo style para cada tag HTML, sem usar os seletores. Este tipo de CSS não é realmente recomendado, já que cada tag HTML precisa ser estilizada de maneira individual.
    
      ```html 
        <p style="font-size: 20px; color: aqua;"><em>Nossa missão é: <strong>"Proporcionar auto-estima e qualidade de vida aos clientes".</strong></em></p>
      ```
    * tag style: Nessa modo criamos uma tag style dentro da tag <head> e adicionamos as propriedades que cada tag terá. Nesse exemplo todas as tags <p> terão seu texto alinhado ao centro da página. 
    
      ```html
       <head>
          <meta charset="UTF-8"> 
          <meta http-equiv="X-UA-Compatible" content="IE=edge">
          <meta name="viewport" content="width=device-width, initial-scale=1.0">
          <title>Aprendendo HTML e CSS</title> 
          <style>
              p {
                  text-align: center;
              }
          </style>
      </head>
      ```
    * Criando um arquivo CSS: 
     
      ```html
       <head>
          <meta charset="UTF-8"> 
          <meta http-equiv="X-UA-Compatible" content="IE=edge">
          <meta name="viewport" content="width=device-width, initial-scale=1.0">
          <title>Aprendendo HTML e CSS</title> 
          <link rel="stylesheet" href="style.css"> <!-- Essa tag puxa todas as característica que estarão no arquivo CSS pro HTML-->
      </head>
      ```
