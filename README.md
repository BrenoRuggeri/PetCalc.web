# PetCalc Web 🐾

**PetCalc** é uma calculadora nutricional para pets que ajuda a estimar a quantidade ideal de ração com base em peso, idade, espécie, nível de atividade e condição fisiológica do animal.

O projeto nasceu inicialmente em **Java** e agora foi **refatorado para web**, utilizando **React**, **Tailwind CSS** e **JavaScript**. O frontend foi inicialmente gerado com **IA**, mas toda a **componentização, organização do código e reestilização** foram feitas manualmente, aplicando boas práticas de desenvolvimento web.

---

## 🌟 Funcionalidades

* Calcular a quantidade diária de ração para **cães e gatos**.
* Considerar **idade, peso, nível de atividade** e **condição fisiológica** (castrado, gestante ou lactante).
* Interface moderna, responsiva e intuitiva.
* Componentização completa com React e estilização usando Tailwind CSS.

---

## 🛠 Tecnologias utilizadas

* **React**
* **Tailwind CSS**
* **JavaScript** (lógica da calculadora)
* **HTML & CSS**
* **IA para prototipagem do frontend** (geração inicial de layout e CSS)

---

## 📁 Estrutura do projeto

```
petcalc-web/
├── public/                  # Arquivos públicos (index.html, favicon, etc.)
├── src/
│   ├── components/          # Componentes React reutilizáveis
│   ├── pages/               # Páginas da aplicação
│   ├── styles/              # Estilos adicionais
│   └── App.js               # Componente principal
├── package.json             # Dependências e scripts
└── README.md                # Documentação
```

---

## 🚀 Como rodar localmente

1. Clone o repositório:

```bash
git clone https://github.com/BrenoRuggeri/PetCal.java.git
```

2. Entre na pasta do projeto web:

```bash
cd petcalc-web
```

3. Instale as dependências:

```bash
npm install
```

4. Inicie o servidor de desenvolvimento:

```bash
npm start
```

O site estará disponível em `http://localhost:3000`.

---

## 🔗 Repositórios

* Projeto original em **Java**: [PetCal.java](https://github.com/BrenoRuggeri/PetCal.java)
* Projeto **web (React + Tailwind)**: Este repositório

## 💡 Observações

* Este projeto é um excelente exemplo de **migração de lógica de Java para JavaScript**, além do uso estratégico de **IA para prototipagem de frontend**.
* Foco em boas práticas de React: **componentização**, **reusabilidade** e **estilização modular**.

## 📝 Licença

MIT License © Breno Ruggeri
