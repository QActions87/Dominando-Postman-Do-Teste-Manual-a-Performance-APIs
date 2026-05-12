# 🎯Postman: Do Teste Manual à Performance APIs📝
[![Cypress](https://api.devicons.dev.br/icon?icons=Linux%2CPostman%2CJavaScript%2CVSCode&size=48&theme=light&perline=30)](https://devicons.dev.br/)
#

## 1ª Projeto - Postman: Teste Manual de API Rest
 - [**Postman: Teste Manual de API Rest — I**](https://medium.com/@atom.freedom/postman-teste-manual-de-api-rest-i-6deffb6da5e1)

Veremos um **cenário CRUD Manual no Postman**, com **os 4 principais métodos do protocolo HTTP** neste projeto **Testes Manuais em API Rest com Postman**e **dicas de boas práticas**. Além de um primeiro contato com a **documentação Swagger ** da API que trabalharemos (**FakeRESTApi**), nesta 1ª parte veremos:

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

 - **Análise do Swagger da API**;
 - Conceito de **Endpoint** e como funciona;
 - **CRUD**;
 - Como diferenciar: **URI, URL, URN, Endpoint, Base URL e Path**;
 - Postman: **Criação de colections esubdiretórios** para **organizar o projeto de testes**;
 - **Criação de variáveis no enviroments**;
 - Motaremos a 1º requisição do projeto, usando a **variável de ambiente e o path**;
 - Começando a escrever o teste com a **1ª asserção do status code**;
 - **2ª asserção** será sobre o **formato mais externo dos dados**, que esperaremos que seja um **Array**;

**Obs.:** Verificar se a estrutura mais externa é um array é a 1º etapa da asserção. Pois, a 2ª ficará para o **Teste de Contrato**, que trarei no **próximo artigo**. 

Por fim, faremos um teste falso negativo, onde testaremos uma expectativa diferente da real, para que o teste falhe, provando que a asserção está realmente funcionando, sendo eficaz, inclusive, em uma situação em que deve falhar.

#
 - [**Postman: Teste Manual de API Rest — III**](https://medium.com/@atom.freedom/postman-teste-manual-de-api-rest-iii-928702ecd6f1)

**Veremos:**
 - **Teste de Contrato**;
 - O que é um **Contrato**;
 - **Modelo do Schema** esperado no **Swagger**;
 - Porque é importante para um QA conhecer o Teste de Contrato na validação do Schema;
 - Anatomia do Teste de Contrato (o que validamos?);
 - **XML e XSD** (O **Contrato de Dados**);
 - XML: Bem formado vs Válido;
 - Exemplo prático de XML bem formado e inválido;
 - Porque é importante fazer Testes de Contrato;
 - **Como Validar Schema**;
 - **Bibliotecas para validação de Schema** (tv4 e ajv);
 - Entederemos o **Fluxo de um response**.
