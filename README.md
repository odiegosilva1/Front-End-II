
# Projeto de Final de Módulo: Implementação de Login com localStorage

Este projeto consiste na criação de uma interface web para um sistema de recados utilizando HTML, JavaScript e a funcionalidade do localStorage para armazenar a sessão do usuário.

## Objetivo

O objetivo deste projeto é implementar a página de login dos usuários cadastrados na API de Recados. A página permite que os usuários autentiquem-se com suas credenciais e, em caso de sucesso, redireciona-os para a tela da lista de recados. Além disso, utiliza o localStorage para armazenar a sessão do usuário logado.

## Estrutura do Código

O código-fonte do projeto contém um arquivo HTML básico que cria a estrutura da página de login. Nele, são apresentados os campos de formulário para username/email e senha, juntamente com botões para realizar o login e acessar a página de cadastro (ainda não implementada).

## Funcionalidades Principais

- Verificação dos campos de login antes do envio, exibindo alertas caso estejam vazios.
- Utilização do localStorage para armazenar a sessão do usuário após o login.
- Redirecionamento para a página de lista de recados em caso de login bem-sucedido.

## Implementação do Login

A lógica de login utilizada no código é uma simulação (`mockLogin`) que verifica se o username é "exemplo" e a senha é "senha". Esta lógica deve ser substituída por chamadas reais à API de Recados para autenticar os usuários.

## Como Utilizar

Para testar a página de login, basta abrir o arquivo HTML em um navegador compatível e preencher os campos com as credenciais corretas.

## Próximos Passos

- Implementação da página de cadastro.
- Conexão real com a API de Recados para autenticação de usuários.

## Notas Importantes

- Este projeto é uma implementação básica para entender o funcionamento do localStorage e a lógica de login. Na prática, é essencial implementar medidas de segurança robustas e integrar com um backend seguro.

---

**Observação**: Substituir a lógica de exemplo por um mecanismo real de autenticação e comunicação com a API de Recados.
