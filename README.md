# 🔮 AI Chat + GitHub Tool (Next.js + Vercel AI SDK)

Este projeto é um exemplo de integração entre um chat com IA usando o **Vercel AI SDK** e chamadas públicas à API do GitHub utilizando **tool calling**. Ideal para quem quer explorar o poder de agentes inteligentes e extensíveis com Next.js.

---

## ✨ Funcionalidades

- Chat com inteligência artificial
- Integração com a API pública do GitHub
- Tool calling para executar ações com base nas mensagens
- Implementação com `pnpm`, `TypeScript` e `Next.js`

---

## 🚀 Tecnologias

- [Next.js](https://nextjs.org/)
- [Vercel AI SDK](https://sdk.vercel.ai/)
- [OpenRouter](https://openrouter.ai/)
- [TypeScript](https://www.typescriptlang.org/)
- [pnpm](https://pnpm.io/)

---

## 📦 Instalação

Antes de tudo, certifique-se de ter o `pnpm` instalado:

```bash
npm install -g pnpm
```

Clone o projeto e instale as dependências:

```bash
git clone https://github.com/seu-usuario/seu-repo.git
cd seu-repo
pnpm install
```

---

## 🔐 Variáveis de Ambiente

Crie um arquivo `.env.local` na raiz do projeto e adicione:

```env
OPENROUTER_API_KEY=sua_chave_openrouter
```

Você pode obter uma chave em:  
👉 https://openrouter.ai

---

## 🏃 Como Rodar o Projeto

Ambiente de desenvolvimento:

```bash
pnpm dev
```

Abra no navegador:  
👉 http://localhost:3000

Build de produção:

```bash
pnpm build
pnpm start
```

---

## 🛠 Scripts Disponíveis

```bash
pnpm dev       # Inicia o ambiente de desenvolvimento
pnpm build     # Compila a aplicação para produção
pnpm start     # Executa a aplicação compilada
```

---

## 🧠 Exemplo de Uso

Digite no chat algo como:

```
Me diga o nome e a bio do usuário "vercel" no GitHub.
```

A IA irá reconhecer o comando, chamar a função do GitHub com o nome do usuário e retornar os dados públicos do perfil.

---

## 🧪 Tool Calling

O **Tool Calling** permite que a IA execute funções do servidor com base no conteúdo das mensagens do usuário. Neste projeto, o `tool` cadastrado permite:

- Buscar informações públicas de um usuário do GitHub
- Executar chamadas HTTP para a API pública do GitHub (`https://api.github.com/users/{username}`)

---

## 🧾 Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

## 👨‍💻 Autor

Feito com ❤️ por Riad Younes(https://github.com/riadyounes)
