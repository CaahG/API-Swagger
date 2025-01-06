## Testes de requisição de APIs para plataforma JsonPlaceHolder

# Resumo 🌸✨

Os testes propostos têm como objetivo validar o **status**, a **estrutura** e a **precisão** da resposta da API. Vamos garantir que tudo esteja perfeito! 💖

- **Parâmetros**:
  - **baseUrl**: `https://jsonplaceholder.typicode.com` 🌐
  - **Requisição**: `GET` 📩
  - **Endpoint 1**: `/posts` 📝
  - **Endpoint 2**: `/posts/1` 🖋️

---

# Teste 1 - "API Test - /posts/1 GET Response Structure and Status" 🌷💻

1. **Validação do status** da resposta para requisição `GET` no endpoint `/posts/1`. 🌟
2. **Validação da estrutura** da resposta e dos tipos de dados contidos. 📦

---

# Cenário 2 - "API Test - /posts GET Response Structure and Status" 🌸💬

1. **Validação do status** da resposta para requisição `GET` no endpoint `/posts`. ✅
2. **Validação da estrutura** da resposta e dos tipos de dados contidos em todos os objetos presentes. 💫

---

## Instruções do Teste 💅🏻💻

Os testes de interface do usuário Web contidos no repositório podem ser executados de duas maneiras diferentes. Vamos te mostrar como! 😘✨

### 1️⃣ **Execução Local** 💖

Siga os passos abaixo para rodar os testes no seu computador:

Os testes podem ser executados localmente seguindo os passos abaixo:

- Instale as dependências do NodeJS (https://nodejs.org/en)
- Instale as dependências do Playwright através do comando npm no terminal: `npm install`
- Clone o repositório de testes através do comando:

  ```bash
  git clone https://github.com/CaahG/jsonplaceholder---API.git
# Execute o comando de execução uma vez na pasta de arquivos:

```bash
npx playwright test

- Para executar todos os testes simultaneamente ou;

### Executar os testes

- Para executar todos os testes simultaneamente:

```bash
npx playwright test
