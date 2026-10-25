# 🎲 Sorteador Web Full-Stack (`sorteador`)

![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-Express-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![MariaDB](https://img.shields.io/badge/MariaDB-MySQL-003545?style=for-the-badge&logo=mariadb&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-emerald?style=for-the-badge)

Aplicação web interativa para realização e persistência de **sorteios numéricos dinâmicos**, composta por interface front-end responsiva (`HTML5`, `CSS3`, `JavaScript`) e integração com API **Node.js (Express)** e banco de dados relacional **MySQL / MariaDB**.

---

## ✨ Funcionalidades

- 🎯 **Sorteio Dinâmico:** Geração de números aleatórios com validação de intervalos.
- 💾 **Persistência em Banco de Dados:** Armazenamento do histórico de sorteios via MySQL/MariaDB (`banco_sorteador.sql`).
- 🌐 **Interface Leve e Responsiva:** Construída com HTML5, CSS3 customizado (`style.css`) e JavaScript puro (`script.js`).
- 🔌 **API REST com Express & CORS:** Back-end preparado para comunicação assíncrona com o cliente web.

---

## 📂 Estrutura do Projeto

| Arquivo | Descrição |
| :--- | :--- |
| `index.html` | Interface principal da aplicação de sorteio. |
| `style.css` | Estilização visual e layout responsivo. |
| `script.js` | Lógica de sorteio no cliente e integração com o back-end. |
| `banco_sorteador.sql` | Dump SQL (MariaDB/MySQL) para criação do banco `numlist` e tabelas. |
| `package.json` | Dependências do servidor Node.js (`express`, `mysql2`, `cors`, `dotenv`, `body-parser`). |

---

## 🚀 Como Executar Localmente

### 1. Clonar o repositório
```bash
git clone https://github.com/mizaelsouto/sorteador.git
cd sorteador
```

### 2. Configurar o Banco de Dados (Opcional para persistência)
Importe o arquivo `banco_sorteador.sql` na sua instância local do MySQL ou MariaDB:
```bash
mysql -u root -p < banco_sorteador.sql
```

### 3. Instalar dependências e iniciar
```bash
npm install
npm start
```
Para uso rápido apenas da interface front-end, basta abrir o arquivo `index.html` diretamente no navegador.

---

## 📄 Licença

Distribuído sob a licença **MIT**. Veja o arquivo [LICENSE](./LICENSE) para mais detalhes.
