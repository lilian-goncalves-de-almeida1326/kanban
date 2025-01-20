# kanban


Este é um projeto de Kanban simples utilizando a funcionalidade de **drag and drop**. A ideia é permitir que os usuários possam arranjar cartões de tarefas entre diferentes colunas de forma intuitiva.

## Funcionalidades

- **Drag and Drop**: Você pode arranjar os cartões entre as colunas ao arrastá-los e soltá-los.
- **Responsividade**: O layout é projetado para funcionar bem em diferentes tamanhos de tela.
- **Interação simples**: Os cartões podem ser movidos entre as colunas com um simples clique e arraste.

## Como usar

1. Clone o repositório para sua máquina:
    ```bash
    git clone https://github.com/seu-usuario/kanban-drag-drop.git
    ```

2. Abra o arquivo `index.html` em seu navegador.

## Estrutura de arquivos

O projeto possui os seguintes arquivos principais:

- `index.html`: A estrutura HTML da página.
- `style.css`: O estilo para o layout e aparência da interface.
- `script.js`: A lógica JavaScript que permite a funcionalidade de **drag and drop**.

## Tecnologias utilizadas

- **HTML**: Estrutura da página.
- **CSS**: Estilo da interface, incluindo o layout e o design das colunas e itens.
- **JavaScript**: Funcionalidade de **drag and drop** para os cartões dentro das colunas.

## Como funciona

### HTML
O HTML é responsável por estruturar a página, criando as colunas e cartões, com a funcionalidade de **drag and drop** sendo aplicada nos itens.

### CSS
O CSS define o layout das colunas e dos cartões. As colunas são dispostas em uma linha, com os cartões empilhados verticalmente. A classe `.dragging` é aplicada nos cartões que estão sendo arrastados, tornando-os semitransparentes.

### JavaScript
O JavaScript adiciona a funcionalidade de **drag and drop**. Quando um cartão é arrastado, ele é movido para uma nova posição na coluna com base na posição do mouse. A lógica considera a posição vertical do cartão de referência dentro da coluna e ajusta a posição do item arrastado.

### Funções principais:
- `dragstart` e `dragend`: Controlam a adição e remoção da classe `.dragging` nos cartões.
- `dragover`: Permite o movimento dos cartões dentro das colunas.
- `getNewPosition`: Calcula a nova posição do cartão dentro da coluna com base na posição do mouse.

## Exemplo de uso

1. Clique e segure em um cartão.
2. Arraste-o para outra coluna.
3. Solte o cartão para reordená-lo ou movê-lo para a nova coluna.

## Contribuição

Sinta-se à vontade para contribuir com melhorias no projeto, correções ou novos recursos! Basta abrir uma **issue** ou enviar um **pull request**.
