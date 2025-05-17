
# Sistema de Cadastro e Login de Usuários (Node.js)

Este projeto é um sistema simples de **cadastro e autenticação de usuários** utilizando JavaScript puro com Node.js. Ele inclui testes automatizados com Jest para garantir o correto funcionamento das funcionalidades.

---

## 📁 Estrutura do Projeto

```
.
├── src
│   ├── repositories
│   │   └── userRepository.js       # Camada de repositório (simula banco de dados)
│   └── services
│       └── userService.js          # Camada de serviço (regras de negócio)
├── testes
│   └── userService.test.js         # Testes automatizados com Jest
├── package.json
└── README.md
```

---

## 🚀 Funcionalidades

- ✅ Cadastro de usuário com validação de campos obrigatórios
- ✅ Verificação de e-mail já cadastrado
- ✅ Login com e-mail e senha
- ✅ Testes unitários cobrindo todos os cenários

---

## 🧪 Testes

Os testes foram desenvolvidos com **Jest**. Eles validam:

- Cadastro com dados válidos
- Erro ao cadastrar com e-mail repetido
- Login com credenciais corretas
- Erro de login com senha incorreta
- Validação de campos obrigatórios no cadastro

---

## ▶️ Como executar o projeto

### 1. Clone o repositório

```bash
git clone <url-do-repo>
cd <nome-da-pasta>
```

### 2. Instale as dependências

```bash
npm install
```

### 3. Execute os testes

```bash
npm test
```

> Certifique-se de ter o Jest instalado (adicione como dependência de desenvolvimento):

```bash
npm install --save-dev jest
```

Adicione também o script no seu `package.json`:

```json
"scripts": {
  "test": "jest"
}
```

---

## 📌 Observações

- Este projeto **não utiliza banco de dados real**, apenas um `Map()` em memória.
- Para fins didáticos, o "token" retornado no login é apenas uma string `'fake-token'`.

---

## 📚 Tecnologias

- Node.js
- JavaScript
- Jest (para testes)

---

## 👨‍💻 Autor

Feito por Pedro — projeto para fins acadêmicos e práticos. 🚀
