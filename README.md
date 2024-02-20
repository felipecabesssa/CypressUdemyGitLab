# Testes automatizados com Cypress - Intermediário

### Informações e Observações

- Docker - com ele rodando execute o seguinte comando: docker run --publish 80:80 --publish 22:22 --hostname localhost wlsf82/gitlab-ce

- Repo professor - (https://github.com/wlsf82/cypress-intermediario-v2/tree/main)
- Documentação oficial Cypress (https://docs.cypress.io/)
- Usr, Senha e Access token - arquivo cypress.env.json 

- 1 - Setup, repositório, readme
chave SSH ja configurada, mas salva no local: c/Users/p_991125/.ssh/id_ed25519

## Inicializando o Cypress

No terminal de linha de comando, na raiz do projeto, execute o comando `npx cypress open` (este comando irá abrir a Cypress App, a qual vai te guiar na criação do projeto de testes _end-to-end_ (_E2E_).

1. Clique no botão para a criação de um projeto de testes _end-to-end_ (_E2E Testing_)
2. Aceite os arquivos de configuração clicando no botão _Continue_
3. Selecione o navegador Electron e clique no botão _Start E2E Testing in Electron_
4. Crie um primeiro arquivo de teste clicando na opção _Create new emtpy spec_
5. Nomeie o arquivo como `login.cy.js`; clique no botão _Create spec_; e então, confirme clicando no botão _Ok, run the spec_
6. Após a execução do arquivo recém criado, feche o navegador Electron.

### Aulas - Commits

- Aula 6 - setup do projeto 
