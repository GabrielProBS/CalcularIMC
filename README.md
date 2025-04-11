Neste documento encontra-se as instruções e funcionalidades do programa da Calculadora de IMC para mobile. Também haverá o vídeo com os mesmos fins:

  Primeiro, foi necessário instalar o Node.js para poder executar os comandos no terminal com fins de fazer uma conexão com o expo e, enfim, poder programar para o dispositivo mobile.
Deve considerar também a versão do Node.js, pois para que execute corretamente, a versão tinha que ser a mais recente.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

  Na pasta "src/components" há os seguintes arquivos:
    
    -App.js (interno): Um arquivo vazio, pois o código está no App.js externo (fora da pasta "src/components").
    -FormIMC.js: É o programa que irá calcular o IMC do cliente com base no peso(kg) e na altura(cm).
    -Result.js: É o programa de saída, ou seja, vai aparecer o resultado que é o IMC do cliente.
    -Title.js: Um arquivo reservado para exibir o título.
    
  *Obs.: Todos os arquivos citados acima (menos o "App.js (interno)") apresentam estilização.*

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

  Continuando na composição do programa, há outro arquivo "App.js" que é fora da pasta "src/components", nele há a base do app (como se fosse o body do HTML), onde foi exportado os arquivos
"FormIMC.js", "Result.js" e "Title.js" para aparecer na interface do app (há estilização para o container).

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Link do video: 
