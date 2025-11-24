# Count;Tem - gestor de finanças local e offline

Count;Tem é um aplicativo desktop (Electron) para registrar e consultar
transações financeiras simples (despesas/receitas). Funciona totalmente
offline, com todos os dados armazenados localmente no computador do
usuário, garantindo privacidade e segurança.

## Recursos principais

-   Aplicação desktop em Electron.
-   API interna em Express para operações de CRUD de transações.
-   Armazenamento local em `%UserProfile%/Documents/CountTem/data`.
-   Relatórios mensais em CSV.
-   Funciona sem internet.

## Segurança e privacidade

-   Nenhuma informação é enviada para servidores externos.
-   Todo o armazenamento é local.
-   Servidor interno roda apenas em `localhost`.

## Tecnologias

-   Electron (desktop)
-   Node.js + Express (API)
-   JSON/LJSON como persistência

## Desenvolvimento

``` bash
npm install
npm run start
```

## Build

``` bash
npm run build
```

## Estrutura

-   main.js --- inicialização do Electron
-   server.js --- API local
-   public/ --- interface do usuário
-   data/ --- arquivos de transações

## Licença

MIT
