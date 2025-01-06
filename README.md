## Testes de requisição de APIs para plataforma JsonPlaceHolder

# Descritivo 🌸✨

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






---
# Testes Automatizados para a API JSONPlaceholder Este repositório contém testes automatizados para verificar a estrutura de dados e os status de resposta da API JSONPlaceholder. Os testes são realizados utilizando o Playwright e cobrem os seguintes cenários: - **Teste 1**: Valida a resposta do endpoint `/posts/1` para garantir que a resposta tenha o status 200 e que a estrutura do JSON esteja conforme esperado. - **Teste 2**: Valida a resposta do endpoint `/posts` para garantir que a resposta tenha o status 200, que o array não esteja vazio, e que cada item no array siga a estrutura correta. ### Como Rodar os Testes: 1. Clone o repositório. 2. Instale as dependências com `npm install`. 3. Execute os testes com `npx playwright test`. ### Objetivo: Esses testes têm como objetivo garantir a integridade da API, verificando que os dados retornados pelos endpoints estão corretos e seguem a estrutura esperada.

- Instale as dependências do **NodeJS** [aqui](https://nodejs.org/en) 💻
- Instale as dependências do **Playwright** com o comando npm:
  ```bash
  npm install
