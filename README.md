# DrivenPass

DrivenPass é um aplicativo de gerenciamento de dados confidenciais projetado para fornecer funcionalidades de criar, acessar e excluir informações de contas de usuários, credenciais, notas seguras e cartões. O projeto visa garantir a segurança dos dados e a privacidade dos usuários.

<hr/>

## Tecnologias:

![Static Badge](https://img.shields.io/badge/nestjs-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)\
![Static Badge](https://img.shields.io/badge/Prisma-3982CE?style=for-the-badge&logo=Prisma&logoColor=white)

- **Development Tools**:\
  ![Static Badge](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)\
  ![Static Badge](https://img.shields.io/badge/prettier-1A2C34?style=for-the-badge&logo=prettier&logoColor=F7BA3E)\
  ![Static Badge](https://img.shields.io/badge/eslint-3A33D1?style=for-the-badge&logo=eslint&logoColor=white)
  
- **Cryptography Libraries**:\
  ![Static Badge](https://img.shields.io/badge/bcrypt-f0772b?style=for-the-badge&logo=jest&logoColor=white)\
  ![Static Badge](https://img.shields.io/badge/cryptr-ffca28?style=for-the-badge&logo=jest&logoColor=white)
     
- **Automated Testing**:\
  ![Static Badge](https://img.shields.io/badge/Jest-C21325?style=for-the-badge&logo=jest&logoColor=white)\
  ![Static Badge](https://img.shields.io/badge/Supertest-5849be?style=for-the-badge&logo=jest&logoColor=white)

<hr/>

### Principais recursos:

- Registro e login de usuários;
- Exclusão de usuário e todas as informações registradas;
- Registro, busca e deleção de credenciais;
- Registro, busca e deleção de notas;
- Registro, busca e deleção de cartões;

Obs: O projeto ainda conta com testes automatizados e documentação descrevendo os recursos.

<hr/>

### Como utilizar:
- Clone o repositório: git clone https://github.com/FellipeLimaT/drivenpass_nest.git
- Digite o seguinte comando na raíz do projeto:

  ```
  npm i
  ```
- Crie um arquivo .env;
- Crie um banco de dados no PostgreSQL;
- O seu arquivo .env deverá ficar da seguinte forma:

```
DATABASE_URL=postgres://SEUUSUARIO:SUASENHA@localhost:5432/SEUBANCODEDADOS
JWT_SECRET=CHAVE_SECRETA_EXEMPLO_#$1234abcd
CRYPTR_SECRET=CHAVE_SECRETA_EXEMPLO_#$1234abcd
```

### Para executar o projeto:

###### Desenvolvimento:

```
npm run start
```

###### Modo de visualização:
```
npm run start:dev
```

###### Modo de produção:
```
npm run start:prod
```

### Para testar o projeto:

###### Testes e2e:

```
npm run test:e2e
```

###### Testes de cobertura:
```
npm run test:cov
```

