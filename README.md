# Sobre o projeto
 Trata-se de um desafio do bootcamp DevSuperior no qual criamos um sistema de eventos e cidades. 
 Neste projeto fazemos algumas validações e implementamos o servidor de autenticação e o servidor de  recursos.
 
## Modelo conceitual:
<div>
 <img src="https://user-images.githubusercontent.com/85883895/197557641-aa696c9e-ba2a-4795-ae6a-0bd1f6cf74e8.png" width="500px" height="250px" /> <br/>
 <img src="https://user-images.githubusercontent.com/85883895/197558084-57d8bf15-e524-4b13-ae4d-6e266d63db7c.png" width="500px" height="300px" />
</div>

## Rotas:
Neste sistema, somente as rotas de leitura (GET) de eventos e cidades são públicas (não precisa de login). 
Usuários CLIENT podem também inserir (POST) novos eventos. Os demais acessos são permitidos apenas a usuários ADMIN.

## Validações da entidade City:
- Nome não pode ser vazio

## Validações da entidade Event:
- Nome não pode ser vazio
- Data não pode ser passada
- Cidade não pode ser nula

## Competências adquiridas:
- Modelo de dados de usuários e perfis
- Validação com Bean Validation
- Annotations
- Customizando a resposta HTTP
- Autenticação e autorização
- Spring Security
- OAuth 2.0
- Token JWT
- Autorização de rotas por perfil


