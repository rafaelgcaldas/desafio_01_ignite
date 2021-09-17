# Desafio 01 - Conceitos do React

### Sobre o desafio

O desafio consiste em criar uma aplicação para treinar o que foi abordado até agora (Capítulo 1) no ReactJS.
Essa será uma aplicação onde o principal objetivo é uma pequena aplicação de atividades a fazer, para treinar um pouco mais sobre manipulação do estado no React.

- Adicionar uma nova tarefa
- Remover uma tarefa
- Marcar e desmarcar uma tarefa como concluída

### Template da aplicação
https://github.com/rocketseat-education/ignite-template-reactjs-conceitos-do-react

 ### Para inicializar a aplicação
 
 ```bash
yarn start
```

### O que foi editado na aplicação?
- src/components/TaskList.tsx;

Esse é o componente responsável por todas as funcionalidades da aplicação, é um componente simples, mas onde foi colocado em prática várias partes da manipulação do estado.

Funcionalidades criadas:
- **handleCreateNewTask**: Deve ser possível adicionar uma nova task no estado de `tasks`, com os campos `id` que deve ser gerado de forma aleatória, `title` que deve ser um texto e `isComplete` que deve iniciar como false.
- **handleToggleTaskCompletion:** Deve alterar o status de `isComplete` para uma task com um ID específico que é recebido por parâmetro.
- **handleRemoveTask:** Deve receber um ID por parâmetro e remover a task que contém esse ID do estado.


### Como a aplicação ficou no final

![todo](https://user-images.githubusercontent.com/26827923/133711681-9544bbec-d89b-4c13-a22d-1b283fb253a8.png)
