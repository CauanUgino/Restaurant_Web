# 🍔 Ugino Hamburgueria

Um sistema web completo e moderno desenvolvido em **Django**, voltado para a gestão e interação de uma hamburgueria artesanal.  
O projeto traz páginas elegantes e funcionais, incluindo cardápio dinâmico, sistema de login e cadastro, carrinho de compras e uma área de **feedback interativa** — tudo com foco em **experiência do usuário (UX)** e **design responsivo**.

---

## 🚀 Funcionalidades Principais

- 🧾 **Cardápio Dinâmico:** Listagem dos produtos por categoria com imagens e preços.
- 🛒 **Carrinho de Compras:** Adicione itens rapidamente com feedback visual.
- 💬 **Sistema de Feedback:** Clientes podem avaliar a experiência com notas e comentários.
- 🖼️ **Upload de Imagens:** O cliente pode enviar uma foto da experiência (selfie ou prato).
- ⭐ **Avaliação Interativa:** Sistema de estrelas animadas com feedback textual.
- 🔐 **Login e Cadastro de Usuários:** Interface moderna e funcional.
- 📱 **Design Responsivo:** Totalmente adaptado para desktop e dispositivos móveis.
- 🧠 **UX aprimorada:** Uso de animações, confirmação com SweetAlert2 e foco em usabilidade.

---

## 🧑‍💻 Tecnologias Utilizadas

| Categoria | Tecnologia |
|------------|-------------|
| **Backend** | [Django 4.x](https://www.djangoproject.com/) |
| **Frontend** | HTML5, CSS3, Bootstrap 5, JavaScript (ES6) |
| **Banco de Dados** | SQLite (padrão do Django) |
| **UI/UX Enhancements** | SweetAlert2, animações CSS e interação dinâmica |
| **Gerenciamento de Mídia** | Upload e exibição via `MEDIA_URL` configurado no Django |

---

## 🏗️ Estrutura do Projeto

```bash
Ugino-Hamburgueria/
│
├── new__Base_App/
│   ├── migrations/
│   ├── static/
│   ├── templates/
│   │   ├── base.html
│   │   ├── menu.html
│   │   ├── feedback.html
│   │   ├── login.html
│   │   └── about.html
│   ├── views.py
│   ├── models.py
│   ├── urls.py
│   └── forms.py
│
├── manage.py
├── db.sqlite3
└── README.md
