# 🛒 Projeto E-commerce (Django)

Este é um projeto de e-commerce desenvolvido em **Python + Django**, com funcionalidades como carrinho de compras via sessão, sistema de usuários, autenticação, perfis, produtos com variações e checkout.

---

## 🚀 Tecnologias utilizadas

- **Python 3**
- **Django 4+**
- **HTML / CSS / Bootstrap**
- **SQLite (desenvolvimento)**
- **Sessões para carrinho**
- **ModelForms e validação**
- **Git + GitHub**

---

## 📦 Funcionalidades principais

### 🛍️ Produtos
- Lista de produtos  
- Detalhes do produto  
- Imagens  
- Variações (ex: tamanho, cor, estoque)

### 🛒 Carrinho de compras
- Armazenado em sessão (`request.session`)  
- Adicionar / remover itens  
- Atualizar quantidades  
- Exibir resumo

### 👤 Usuários
- Cadastro  
- Login / Logout  
- Edição de perfil  
- Endereço  
- Senha opcional na edição

### 🧾 Pedidos
- Criação de pedidos  
- Associação com usuário logado  
- Página de pagamento

---

## 🔧 Instalação e execução

### 1. Clonar este repositório
```bash
git clone https://github.com/rafaellimaofc/projeto-e-commerce.git
cd projeto-e-commerce
```

### 2. Criar e ativar um ambiente virtual
```bash
python -m venv venv
venv\Scripts\activate  # Windows
```

### 3. Instalar dependências
```bash
pip install -r requirements.txt
```

### 4. Criar o arquivo .env  
Crie um arquivo `.env` na raiz baseado no arquivo `.env_exemplo`.

### 5. Rodar migrações
```bash
python manage.py migrate
```

### 6. Iniciar o servidor
```bash
python manage.py runserver
```

---

## 🗂️ Estrutura do projeto
```bash
ecommerce/
│-- core/
│-- produto/
│-- pedido/
│-- perfil/
│-- templates/
│-- static/
│-- manage.py
│-- .env
│-- requirements.txt
│-- .env_exemplo
```

---

## 🔐 Variáveis de ambiente
O arquivo `.env_exemplo` já está incluído no projeto.  
Copie para `.env` e personalize conforme necessário.

---

## 📄 Licença
Este projeto está sob a **Licença MIT**.  
Você pode usar, modificar e distribuir livremente.

---

## ✉️ Contato
Desenvolvido por **Rafael**.  
GitHub: https://github.com/rafaellimaofc
