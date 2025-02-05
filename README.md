# Planejador Diário

Este é um projeto de um Planejador Diário desenvolvido com React e Vite. O objetivo deste projeto é ajudar os usuários a organizar suas tarefas diárias de forma eficiente.

## Estrutura do Projeto

A estrutura do projeto é organizada da seguinte forma:

.eslintrc.cjs
.gitattributes
.gitignore
index.html
package.json
public/
src/
    App.jsx
    assets/
    Components/
        Header/
            Header.jsx
            Index.scss
        Modals/
            DeleteModal.jsx
            EditModal.jsx
            Index.scss
        NewTask/
            NewTask.jsx
        ReviseTask/
            Index.scss
            ReviseTask.jsx
        TaskList/
            Index.scss
            TaskList.jsx
        ViewTasks/
            ViewTasks.jsx
    global.scss
    Index.scss
    main.jsx
    view/
        Index.scss
        Login.jsx
vite.config.js

## Funcionalidades

- **Login**: Tela de login onde o usuário pode acessar o sistema com seu CPF.
- **Header**: Componente de cabeçalho com menu de navegação.
- **Lista de Tarefas**: Exibe a lista de tarefas do usuário, permitindo adicionar, editar, visualizar e deletar tarefas.
- **Modais**: Modais para confirmação de exclusão e edição de tarefas.
- **Nova Tarefa**: Componente para adicionar novas tarefas.
- **Revisar Tarefa**: Componente para editar tarefas existentes.

## Estilos

Os estilos são organizados em arquivos SCSS, com um arquivo global (`global.scss`) que define as variáveis de cores e fontes utilizadas no projeto.

## Scripts Disponíveis

No diretório do projeto, você pode executar:

### `npm run dev`

Executa o aplicativo no modo de desenvolvimento.\
Abra [http://localhost:3000](http://localhost:3000) para visualizá-lo no navegador.

### `npm run build`

Compila o aplicativo para produção na pasta `dist`.

### `npm run lint`

Executa o ESLint para verificar problemas de linting no código.

### `npm run preview`

Visualiza a versão de produção do aplicativo.

## Dependências

- React
- React DOM
- React Router DOM
- Vite
- ESLint
- Sass

## Como Contribuir

1. Faça um fork do projeto.
2. Crie uma branch para sua feature (`git checkout -b feature/nova-feature`).
3. Commit suas mudanças (`git commit -m 'Adiciona nova feature'`).
4. Faça um push para a branch (`git push origin feature/nova-feature`).
5. Abra um Pull Request.