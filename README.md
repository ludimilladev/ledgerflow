🇧🇷 Português | [🇺🇸 English](README.en.md)

# ledgerflow

Um serviço de processamento de transações construído com Node.js puro, criado para dominar os fundamentos da plataforma.


## Sobre

O ledgerflow recebe transações financeiras (depósitos, saques e transferências), valida, aplica regras de negócio e registra tudo em um ledger append-only (registro em que os dados só são adicionados, nunca alterados ou apagados).

O projeto é construído em fases. Cada fase foca em um conceito central do Node.js, usando módulos nativos sempre que possível.

## Como Começar

### Pré-requisitos

- Node.js (versão LTS)

### Instalação

```bash
git clone https://github.com/ludimilladev/ledgerflow.git
cd ledgerflow
npm install
```


Para desenvolvimento com reinício automático:

```bash
npm run dev
```

## Roadmap

- [x] Configuração do projeto
- [ ] Fase 1: CLI que processa arquivos grandes de transações com streams
- [ ] Fase 2: Servidor HTTP usando apenas o módulo nativo `http`
- [ ] Fase 3: Pipeline de transações orientado a eventos com `EventEmitter`
- [ ] Fase 4: Processamento em segundo plano com `worker_threads`
- [ ] Fase 5: Persistência, logs e encerramento gracioso (graceful shutdown)
- [ ] Fase 6: Testes automatizados com o test runner nativo