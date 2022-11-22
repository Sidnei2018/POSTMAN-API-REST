# POSTMAN-API-REST

## Testes manuais com Postman - API-REST 🚀

## Teste manual GET

Utilizo a seguinte Url para acesso à API: (https://jsonplaceholder.typicode.com/users)<br><br>
1- Definir a solicitação HTTP para GET<br>
2- No campo URL de solicitação, inserir o link acima<br>
3- Clicar em Enviar<br>
4- Deve ser exibido 200 Mensagem OK<br>
5- Devem haver 10 resultados de usuários no corpo, o que indica que o teste foi executado com sucesso<br>

![solicitacao-GET](https://user-images.githubusercontent.com/28484134/203321672-ac433b55-9847-4c72-a1d8-1f762e9d39ee.jpg)


## Teste manual POST<br><br>

1- Defina uma nova aba<br>
2- Defina sua solicitação HTTP para POST<br>
3- Insira o mesmo link no URL de solicitação: https://jsonplaceholder.typicode.com/users<br>
4- Mude para a guia Corpo (BODY)<br>
5- Mude a opcao abaixo para raw e tipo de arquivo JSON<br>
6- Após clicar em Enviar, o usuário de id11 deve ser inserido á lista<br>

![solicitacao-POST](https://user-images.githubusercontent.com/28484134/203322085-7c447201-4fe8-4231-8fd9-538bc3d6a2d1.jpg)


## Teste parametrizado<br><br>

1- Defina a solicitação HTTP para GET<br>
2- Insira este link: https://jsonplaceholder.typicode.com/users<br>
3- Substitua a primeira parte do link por um parâmetro como {{url}}<br>
4- URL de solicitação agora deve ser {{url}}/users<br>
5- Clique no ícone de olho(visualizar)<br>
6- Clique em editar para definir a variável para um ambiente global que pode ser usado em todas as coleções<br>
7- Clique em enviar<br>

![Parametrizacao-POST](https://user-images.githubusercontent.com/28484134/203324113-c6cf5b42-80f7-42af-a3b7-d1cf8341c5da.jpg)


## Testes com Scripts manuais<br><br>

1- Mude para a guia de “Testes” (TESTS)<br>
2- No lado direito estão os códigos de trecho para serem inseridos<br>
3- Na seção de snippets, clique em “Código de status: Código é 200”<br>
4- Insira outros snippets para testar em conjunto<br>
5- Se forem bem sucedidos uma mensagem será apresentada (PASS) ou (FAILED)<br>

![manual-API](https://user-images.githubusercontent.com/28484134/203325297-c9097b77-f367-4e57-87bf-4bdbdf2c3a7f.jpg)








