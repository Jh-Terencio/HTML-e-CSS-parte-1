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
        * Serve para informar qual versão do html estamos usando
     * ```html 
        <html lang="pt-br">
       ```
        *  A ideia do uso dele é normatizar e indicar os tipos de dados pra quem tiver interesse, se não houver esse atributo plugins, google tradutor ou buscadores irão ter dificuldades em detectar o idioma do texto apresentado
     * ```html 
        <meta charset="UTF-8">
       ```
        * A tag meta serve para passar as informações para o navegador. Já a propriedade charset é um dicionário que possui todas as linguagens. Um exemplo é que no inglês não temos acento nem "Ç", esse dicionário uni a maioria das linguas permitindo a existência de diversos caracteres
     * ```html 
        <title>Aprendendo HTML e CSS</title>
       ```
        * Permite escolher o nome da página
