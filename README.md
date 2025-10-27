# rocketseat_T-todo_-mobile
Esse é o primeiro desafio da formação React Native 2022, onde você vai construir uma aplicação de lista de tarefas (to-do list).
O objetivo é praticar conceitos fundamentais do React Native, como estados, imutabilidade, listas, propriedades e componentização.

Apesar de simples, a aplicação envolve funcionalidades essenciais que serão muito úteis em projetos futuros: criar, concluir e remover tarefas, além de acompanhar o progresso de conclusão.

Instruções
Estrutura, regras e requisitos do projeto

1. Estrutura inicial
Crie um projeto no React Native utilizando Expo com Typescript.

Estruture a aplicação com pelo menos dois componentes principais:

Input + botão para adicionar novas tarefas.
Lista de tarefas exibindo cada item criado.
2. Funcionalidades obrigatórias
➕ Adicionar tarefa
O usuário deve digitar a descrição da tarefa em um campo de input.

Ao clicar no botão de “+”, a tarefa deve ser adicionada à lista.

Cada nova tarefa deve aparecer imediatamente na interface, com:

Texto da descrição.
Um círculo indicando se está concluída ou não.
Um botão de lixeira para excluir.
✅ Marcar e desmarcar tarefa
Ao clicar no círculo ao lado da tarefa, o estado dela deve alternar entre:

Pendente (círculo vazio, texto normal).
Concluída (círculo marcado, texto riscado com estilo line-through).
🗑️ Remover tarefa
O usuário deve poder excluir qualquer tarefa da lista clicando no botão de lixeira.
Após a remoção, a lista deve ser atualizada automaticamente.
📊 Contadores
Na parte superior da lista, devem aparecer dois indicadores:

Criadas: quantidade total de tarefas adicionadas.
Concluídas: quantidade de tarefas finalizadas.
Esses números devem atualizar em tempo real conforme o usuário adiciona, conclui ou remove tarefas.

3. Estados e manipulação
Use estados do React para armazenar a lista de tarefas.
Cada tarefa deve ser representada por um objeto com pelo menos id, descrição e status de concluído.
Utilize métodos de array como map, filter e reduce para atualizar os estados corretamente.
4. Interface (baseada no layout do Figma)
Tela inicial deve exibir:

O logo.

O input para adicionar tarefas.

Os contadores de tarefas.

A lista ou, caso não haja tarefas, uma mensagem de estado vazio:

"Você ainda não tem tarefas cadastradas. Crie tarefas e organize seus itens a fazer".

Estilizar:

Concluídas → texto riscado e cor diferenciada.
Pendentes → texto normal e círculo vazio.
Botão de excluir → ícone de lixeira.
5. Desenvolvendo o projeto
Para desenvolver esse projeto, recomendamos utilizar as principais ferramentas que utilizamos durante o desenvolvimento do primeiro módulo da formação.

Caso você tenha alguma dificuldade você pode ir no nosso 
fórum
 e deixar sua dúvida por lá!

Após terminar o desafio, caso você queira, você pode tentar dar o próximo passo e deixar a aplicação com a sua cara. Tente mudar o layout, cores, ou até adicionar novas funcionalidades para ir além 🚀

6. Entrega
Após concluir o desafio, você deve enviar a URL do seu código no Github.

Além disso, que tal fazer um post no LinkedIn compartilhando o seu aprendizado e contando como foi a experiência?

É uma excelente forma de demonstrar seus conhecimentos e atrair novas oportunidades!

Obs: Se você se sentir à vontade, pode postar um print do resultado final e nos marcar! Vai ser incrível acompanhar a sua evolução! 💜

Feito com 💜 por Rocketseat 👋
