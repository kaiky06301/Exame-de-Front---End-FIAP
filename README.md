# Exame-de-Front---End-FIAP


# Visualizador de Baralho

Aplicação web desenvolvida para avaliação de Front-end utilizando Next.js.

## Stack Tecnológica

- Next.js 14
- React 18
- TypeScript
- CSS Modules

## Configuração do Projeto

### 1. Instalação de Dependências

Execute o comando abaixo para instalar todas as dependências necessárias:

```bash
npm install
```

### 2. Variáveis de Ambiente

Crie um arquivo `.env.local` na raiz do projeto com a seguinte configuração:

```env
AUTH_PASSWORD=sua_senha_aqui
```

### 3. Executar em Desenvolvimento

Para iniciar o servidor de desenvolvimento:

```bash
npm run dev
```

O aplicativo estará disponível em `http://localhost:3000`

### 4. Build para Produção

Para gerar uma build otimizada:

```bash
npm run build
npm start
```

## Funcionalidades

- Sistema de autenticação com validação de senha
- Exibição completa do baralho de cartas
- Filtro por naipe das cartas
- Embaralhamento de cartas
- Persistência do estado no localStorage
- Interface responsiva

## Deploy na Vercel

Link do deploy: (em breve)

Para fazer o deploy na Vercel, certifique-se de configurar a variável de ambiente `AUTH_PASSWORD` nas configurações do projeto.
