# 🏅 Notas de Atletas – Ginástica Artística

## 📌 Descrição do Projeto

Este projeto consiste em uma aplicação desenvolvida em **JavaScript** que calcula a **média válida** das notas de atletas em uma competição de ginástica artística.

Cada atleta é avaliado por **cinco jurados**, e a média final é calculada **desconsiderando a maior e a menor nota**, conforme as regras da competição.

O objetivo do projeto é praticar conceitos fundamentais de JavaScript, como:
- Manipulação de arrays
- Estruturas de repetição
- Funções
- Métodos nativos da linguagem

---

## 🧠 Regras de Avaliação

- Cada atleta recebe **5 notas**, variando de **1 a 10**
- A **maior** e a **menor nota** são descartadas
- A média final é calculada com base nas **3 notas restantes**

---

## ⚙️ Funcionalidades

A aplicação é capaz de:

- Receber uma lista de atletas com seus nomes e notas
- Ordenar as notas de cada atleta
- Eliminar automaticamente a maior e a menor nota
- Calcular a média válida
- Exibir no console:
  - Nome do atleta
  - Notas obtidas (ordenadas)
  - Média válida calculada

---

## 🧪 Tecnologias Utilizadas

- **JavaScript (ES6+)**
- **Node.js** ou console do navegador
- **Git e GitHub** para versionamento

---

## 📂 Estrutura do Projeto
notas-atletas/
│
├── notas-atletas.js
└── README.md
## ▶️ Como Executar o Projeto

### Opção 1: Usando Node.js

1. Certifique-se de ter o **Node.js** instalado  
   👉 https://nodejs.org/

2. Clone este repositório:
```bash
git clone https://github.com/seu-usuario/notas-atletas.git

3. Acesse a pasta do projeto:
bash
Copiar código
cd notas-atletas

4. Execute o arquivo JavaScript:
bash
Copiar código
node notas-atletas.js

5. O resultado será exibido diretamente no console

Exemplo de Saída
Atleta: Cesar Abascal
Notas Obtidas: 7.88,8.42,9.34,10,10
Média Válida: 9.253333333333334

