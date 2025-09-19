# 🧺 Sistema de Controle de Secagem de Lavanderia

Este projeto tem como objetivo substituir o controle manual em papel pelo **registro digital de roupas em processo de secagem**, permitindo maior organização, agilidade e geração de relatórios.  

O sistema registra informações como:
- 📅 Data  
- ⏰ Hora de início  
- ⚖️ Peso (Kg)  
- 👕 Tipo de roupa  
- 👤 Operador  
- 🌀 Secadora utilizada  
- 📌 Status (em andamento, concluído ou cancelado)  

Além disso, o sistema gera **histórico de processos** e exportação para **planilhas Excel mensais**.

---

## ⚙️ Funcionalidades

- Registrar roupas em processo de secagem e lavagem
- Acompanhar status em tempo real (tela principal)  
- Finalizar ou cancelar operações  
- Visualizar histórico filtrando por data  
- Cadastro e gerenciamento de operadores  
- Exportação de relatórios mensais em **Excel**  
- Interface simples, pensada para **usuários leigos em informática**  
- Suporte a execução em **tela cheia/kiosk mode** (ideal para totens)  

---

## 🛠️ Ferramentas Utilizadas

- **PHP 8.x** → Backend e CRUD  
- **MySQL/MariaDB** (via **XAMPP**) → Banco de dados  
- **phpMyAdmin** → Gerenciamento inicial do banco  
- **Bootstrap 5** → Estilização e responsividade  
- **JavaScript (Vanilla/ES6)** → Interatividade e mobilidade na interface  
- **Python (opcional)** → Exportação de relatórios em Excel  
- **XAMPP** → Ambiente de desenvolvimento local (Apache + MySQL)  

---

## 🖥️ Instalação e Configuração

### 1. Pré-requisitos
- [XAMPP](https://www.apachefriends.org/index.html) instalado no computador  
- Navegador atualizado (Chrome recomendado)  

### 2. Instalar o projeto
1. Clone o repositório ou baixe o ZIP:
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
