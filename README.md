# 📝 Blog Pessoal

## 🌟 Visão Geral

Este projeto é um blog pessoal desenvolvido com React, que permite aos usuários criar, visualizar, editar e excluir postagens. Os usuários também podem se cadastrar, fazer login e interagir com as postagens de outros usuários.

## ✨ Funcionalidades

*   **🔑 Autenticação de Usuário:**
    *   Cadastro de novos usuários.
    *   Login com usuários existentes.
    *   Manutenção do estado de login em toda a aplicação.

*   **✍️ Postagens:**
    *   Criação de novas postagens.
    *   Visualização de todas as postagens em um feed.
    *   Edição de postagens existentes.
    *   Exclusão de postagens.

*   **🏷️ Temas:**
    *   Criação de novos temas.
    *   Visualização de todos os temas.
    *   Edição de temas existentes.
    *   Exclusão de temas.
    *   Associação de postagens a temas.

*   **👤 Perfil:**
    *   Visualização do perfil do usuário.
    *   Visualização das postagens do usuário.

## 🚀 Tecnologias Utilizadas

*   **Frontend:**
    *   [React](https://reactjs.org/)
    *   [Vite](https://vitejs.dev/)
    *   [TypeScript](https://www.typescriptlang.org/)
    *   [Tailwind CSS](https://tailwindcss.com/)
    *   [Axios](https://axios-http.com/)
    *   [React Router DOM](https://reactrouter.com/)
    *   [Phosphor Icons](https://phosphoricons.com/)
    *   [React Toastify](https://fkhadra.github.io/react-toastify/introduction)

## ▶️ Como Executar o Projeto

1.  **Clone o repositório:**
    ```bash
    git clone https://github.com/seu-usuario/blog-pessoal-react.git
    ```

2.  **Instale as dependências:**
    ```bash
    cd blog-pessoal-react
    npm install
    ```

3.  **Inicie o servidor de desenvolvimento:**
    ```bash
    npm run dev
    ```

4.  **Abra o navegador e acesse:**
    ```
    http://localhost:5173/
    ```

## 📁 Estrutura do Projeto

```
/src
|-- /assets
|-- /components
|   |-- /footer
|   |-- /navbar
|   |-- /postagem
|   |-- /tema
|-- /contexts
|-- /models
|-- /pages
|   |-- /cadastro
|   |-- /home
|   |-- /login
|   |-- /perfil
|-- /services
|-- /utils
|-- App.css
|-- App.tsx
|-- index.css
|-- main.tsx
```

*   **`src/assets`**: Contém arquivos de mídia, como imagens e ícones. 🖼️
*   **`src/components`**: Contém componentes React reutilizáveis. 🧩
*   **`src/contexts`**: Contém os contextos da aplicação, como o de autenticação. 🌐
*   **`src/models`**: Contém as definições de tipo para os modelos de dados. 📦
*   **`src/pages`**: Contém os componentes de página da aplicação. 📄
*   **`src/services`**: Contém os serviços responsáveis pela comunicação com a API. 📡
*   **`src/utils`**: Contém funções utilitárias. 🛠️
