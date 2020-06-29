# TCC 2020 - Teste de Software com Cypress

Realização de teste E2E utilizando Cypress na plataforma Overleaf.

- [`Cypress`](https://www.cypress.io/): Framework para realização de testes.

### Fluxo de execução:

- Acessar a página do Overleaf
- Fazer login
- Criar um projeto a partir de um Template
- No campo de busca, digitar "INATEL\_TCC"
- Abrir o template "Modelo INATEL TCC GRADUACAO"
- Clicar em "Open as Template"
- Fazer o upload de uma figura através da opção: "Url Externa"
- Acessar o arquivo "02-introducao.tex"
- Inserir um texto nesse arquivo. Esse é um código LaTex que renderiza a figura importada da URL Externa. 
- Ao ter o projeto compilado, fazer o download do PDF
- Regressar ao menu inicial e excluir o projeto 

# Executando

Com o terminal aberto na pasta, execute o comando:

> Lembre-se de inserir as suas credenciais (usuário e senha) de acesso ao site Overleaf no arquivo "[Overleaf.spec.js]".

```bash
npm run cypress-tcc
```

Aguarde até que o Cypress seja carregado.