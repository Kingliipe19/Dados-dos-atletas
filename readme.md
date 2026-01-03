# 🏅 Dados de Atletas – Ginástica Artística

![JavaScript](https://img.shields.io/badge/language-JavaScript-yellow)

## 📌 Descrição do Projeto

Este projeto é uma aplicação desenvolvida em **JavaScript** que utiliza **Programação Orientada a Objetos (POO)** para representar atletas de uma competição de ginástica artística.

A aplicação é capaz de receber informações de um atleta e calcular automaticamente:
- Categoria
- IMC (Índice de Massa Corporal)
- Média válida das notas

Além disso, exibe todas as informações de forma organizada no **console**.

Este projeto é a continuação e evolução do projeto **Notas de Atletas**, agora aplicando conceitos de **classes, métodos e encapsulamento**.

---

## 🧠 Regras de Negócio

### 📍 Categoria por idade
- **Infantil**: 9 a 11 anos  
- **Juvenil**: 12 e 13 anos  
- **Intermediário**: 14 e 15 anos  
- **Adulto**: 16 a 30 anos  
- **Sem categoria**: demais idades  

### 📍 Cálculo do IMC
IMC = peso / (altura × altura)



### 📍 Cálculo da Média Válida
- O atleta recebe **5 notas**
- A **maior** e a **menor** nota são descartadas
- A média é calculada com base nas **3 notas centrais**

---

## ⚙️ Funcionalidades

A aplicação permite:

- Criar um atleta através da classe `Atleta`
- Calcular automaticamente:
  - Categoria
  - IMC
  - Média válida
- Retornar informações do atleta por meio de métodos específicos
- Exibir os dados completos no console

---

## 🧪 Tecnologias Utilizadas

- **JavaScript (ES6+)**
- **Node.js** ou console do navegador
- **Git e GitHub** para versionamento

---

## 📂 Estrutura do Projeto

dados-atletas/
│
├── dados-atletas.js
└── README.md



---

## ▶️ Como Executar o Projeto

### Opção 1: Usando Node.js

1. Certifique-se de ter o **Node.js** instalado  
   👉 https://nodejs.org/

2. Clone este repositório:
bash
git clone https://github.com/seu-usuario/dados-atletas.git
Acesse a pasta do projeto:

bash
Copiar código
cd dados-atletas
Execute o arquivo JavaScript:

bash
Copiar código
node dados-atletas.js
O resultado será exibido no console

### Opção 2: Console do Navegador
Abra o navegador (Chrome, Edge ou Firefox)

Pressione F12 e vá até a aba Console

Copie todo o código do arquivo dados-atletas.js

Cole no console e pressione Enter

## 📊 Exemplo de Saída no Console
text
Copiar código
Nome: Cesar Abascal
Idade: 30
Peso: 80
Altura: 1.7
Notas: 10,9.34,8.42,10,7.88
Categoria: Adulto
IMC: 27.68166089965398
Média válida: 9.253333333333332
