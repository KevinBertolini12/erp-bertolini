# 📦 Bertolini ERP — Sistema de Gestão Empresarial & PDV Desktop

> Sistema ERP / PDV desktop desenvolvido em Python com arquitetura offline-first, focado em controle de produtos, estoque em tempo real, vendas (caixa), relatórios e dashboard gerencial.

---

## 📌 Sobre o Projeto

O **Bertolini ERP** é uma aplicação desktop completa desenvolvida para simplificar a gestão operacional de micro e pequenas empresas. Integrando uma interface gráfica moderna e responsiva em PySide6 a um motor de backend rápido e seguro, o sistema oferece controle total de inventário, caixa e vendas diárias.

### 🚀 Funcionalidades Implementadas

- **📦 Produtos:** Cadastro, edição, exclusão, SKU opcional e controle de estoque em tempo real.
- **📊 Estoque:** Ajustes manuais (entrada/saída), histórico de movimentações e integração automática com vendas.
- **🧾 PDV / Caixa:** Busca rápida por nome ou SKU, adição ao carrinho via Enter, controle de quantidade e atualização automática do estoque.
- **📈 Dashboard Gerencial:** Total de produtos, estoque total, alerta de estoque baixo e gráfico de movimentação dos últimos dias.
- **📑 Relatórios:** Resumo geral e movimentações por período com base para relatórios financeiros.
- **🏭 Fornecedores:** Cadastro e listagem estruturados para vínculo futuro com produtos.

---

## 🧱 Stack Tecnológica

- **Linguagem:** Python 3.11+
- **Interface Desktop:** PySide6 (Qt)
- **API Local:** FastAPI
- **ORM & Banco de Dados:** SQLAlchemy (async), SQLite (modo local/offline), PostgreSQL (planejado)
- **Migrations:** Alembic
- **Arquitetura:** Offline-First

---

## 💻 Como Executar o Projeto Localmente

```bash
# Clonar o repositório
git clone https://github.com/KevinBertolini12/bertolini-erp.git

# Entrar na pasta do projeto
cd bertolini-erp

# Criar e ativar o ambiente virtual
python -m venv venv

# No Windows:
venv\Scripts\activate

# No Linux/Mac:
source venv/bin/activate

# Instalar as dependências
pip install -r requirements.txt

# Executar a aplicação
python main.py
```

---

## 🖥️ Screenshots

![Dashboard](docs/screenshots/dashboard.png)
![Produtos](docs/screenshots/products.png)
![PDV](docs/screenshots/pos.png)
![Relatórios](docs/screenshots/reports.png)

---


👨‍💻 Author:
Kevin Bertolini

Project developed as part of a professional transition and growth in the technology field.
