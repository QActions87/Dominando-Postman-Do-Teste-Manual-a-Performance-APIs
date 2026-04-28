# 🎯Postman: Do Teste Manual à Performance APIs📝
[![Cypress](https://api.devicons.dev.br/icon?icons=Linux%2CPostman%2CJavaScript%2CVSCode&size=48&theme=light&perline=30)](https://devicons.dev.br/)
#

## 1ª Projeto: Postman: Teste Manual de API Rest
 - [**Postman: Teste Manual de API Rest — I**](https://medium.com/@atom.freedom/postman-teste-manual-de-api-rest-i-6deffb6da5e1)

Veremos **Testes Manuais em API Rest com Postman**. Além de um primeiro contato com a documentação Swagger da **API que trabalharemos** (**FakeRESTApi**), nesta 1ª parte veremos:

 - Formas de **passar parâmetros para a API**:
   - Parâmetro **Path**;
   - Parâmetro **Query**;
   - Parâmetro **Body**.
 - A importância da ferramenta **cURL** e da **flag -H** no parâmetro **Body**.
 - Anatomia de uma **Requisição HTTP**.
   - Camada **General**;
   - **Header**;
   - **Camada de Envio de Dados**;
   - **Resonse**(Resposta).
 - **Fundamentos do JSON** para QA

#
 - [**Postman: Teste Manual de API Rest — II**](https://medium.com/@atom.freedom/postman-teste-manual-de-api-rest-ii-6ee8e92c17f4)

**Veremos:**

 - 𝐀𝐧á𝐥𝐢𝐬𝐞 𝐝𝐨 𝐒𝐰𝐚𝐠𝐠𝐞𝐫 da API;
 - Conceito de 𝐄𝐧𝐝𝐩𝐨𝐢𝐧𝐭 e como funciona;
 - 𝐂𝐑𝐔𝐃;
 - Como diferenciar: 𝐔𝐑𝐈, 𝐔𝐑𝐋, 𝐔𝐑𝐍, Endpoint, 𝐁𝐚𝐬𝐞 𝐔𝐑𝐋 𝐞 𝐏𝐚𝐭𝐡;
 - Postman: 𝐂𝐫𝐢𝐚çã𝐨 𝐝𝐞 𝐜𝐨𝐥𝐞𝐜𝐭𝐢𝐨𝐧𝐬 e subdiretórios para 𝐨𝐫𝐠𝐚𝐧𝐢𝐳𝐚𝐫 𝐨 𝐩𝐫𝐨𝐣𝐞𝐭𝐨 𝐝𝐞 𝐭𝐞𝐬𝐭𝐞𝐬;
 - 𝐂𝐫𝐢𝐚çã𝐨 𝐝𝐞 𝐯𝐚𝐫𝐢á𝐯𝐞𝐢𝐬 𝐧𝐨 𝐞𝐧𝐯𝐢𝐫𝐨𝐦𝐞𝐧𝐭𝐬;
 - Motaremos a 1º 𝐫𝐞𝐪𝐮𝐢𝐬𝐢çã𝐨 𝐝𝐨 𝐩𝐫𝐨𝐣𝐞𝐭𝐨, usando a 1º 𝐫𝐞𝐪𝐮𝐢𝐬𝐢çã𝐨 𝐝𝐨 𝐩𝐫𝐨𝐣𝐞𝐭𝐨1º 𝐫𝐞𝐪𝐮𝐢𝐬𝐢çã𝐨 𝐝𝐨 𝐩𝐫𝐨𝐣𝐞𝐭𝐨;
 - Começando a escrever o teste com a 1ª 𝐚𝐬𝐬𝐞𝐫çã𝐨 𝐝𝐨 𝐬𝐭𝐚𝐭𝐮𝐬 𝐜𝐨𝐝𝐞;
 - 2ª asserção será sobre o formato mais externo dos dados, que esperaremos que seja um𝐀𝐫𝐫𝐚𝐲;

𝐎𝐛𝐬.: Verificar se a estrutura mais externa é um array é a 1º etapa da asserção. Pois, a 2ª ficará para o Teste de Contrato, que trarei no próximo artigo. 

Por fim, faremos um teste falso negativo, em que testaremos uma expectativa diferente da real, para que o teste falhe, provando que a asserção está realmente funcionando, sendo eficaz, inclusive, em uma situação em que deve falhar.
