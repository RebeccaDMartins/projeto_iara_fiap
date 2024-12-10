# Projeto Iara Games - FIAP 1TWDOR 2024

A “BrasilAPI” foi integrada ao projeto para realizar a pesquisa de CEP. Essa API é uma solução brasileira que fornece informações completas e atualizadas de endereços a partir de um CEP informado. 

A funcionalidade da API dentro da Iara Games é permitir que os usuários adicionem seu CEP na página do usuário, na opção “Adicione sua Localização”. Essa informação será utilizada para personalizar a experiência do usuário na plataforma e habilitar operações futuras, como: planejamento de futuras entregas ou serviços e, principalmente, para complementar seu cadastro na plataforma.
A requisição da BrasilAPI foi realizada utilizando o Postman para simulação e teste inicial. Após testes de funcionalidade, foi desenvolvido um código no formato JavaScript para implementar a requisição em json, responsável por fazer a chamada do localizador de CEP pela plataforma. Após adicionada, foi feita uma ligação entre o HTML para receber o formato JavaScript, sendo possível realizar a ação principal da API.
A integração na aplicação foi realizada para que, ao inserir o CEP, o sistema retorne os dados correspondentes ao endereço de forma automática.
