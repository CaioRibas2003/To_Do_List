# To_Do_List
Projeto de lista de tarefas, com HTML, CSS e JavaScript

## Funcionalidades

- **Adicionar Tarefas:** Crie tarefas com título, descrição, data de vencimento e nível de urgência (baixa, média ou alta).
- **Visualização por Urgência:** As tarefas são organizadas em três colunas (Alta Urgência, Média Urgência, Baixa Urgência).
- **Destacando Prazo de Tarefas:**
  - Tarefas atrasadas são destacadas em vermelho.
  - Tarefas com prazo em até 2 dias são destacadas em laranja.
  - Tarefas dentro do prazo são destacadas em verde.
- **Legenda Visual:** Uma legenda indica o significado das cores das tarefas.
- **Visualizar Descrição:** Clique em "Ver descrição" para abrir um modal com os detalhes da tarefa.
- **Excluir Tarefas:** Remova tarefas individualmente.
- **Persistência Local:** As tarefas são salvas no navegador usando localStorage.
- **Interface Intuitiva:** Layout limpo e responsivo, com separação clara das tarefas por urgência.

## Como Usar

1. Digite o título e a descrição da tarefa.
2. Escolha a data de vencimento e o nível de urgência.
3. Clique em "Adicionar" para criar a tarefa.
4. Visualize, exclua ou veja a descrição das tarefas diretamente nas colunas apropriadas.
5. As tarefas permanecem salvas mesmo ao fechar o navegador.

## Estrutura dos Arquivos

- `index.html`: Estrutura da página e elementos principais da interface.
- `style.css`: Estilos, cores de legendas e responsividade.
- `script.js`: Lógica para adicionar, renderizar, excluir tarefas, abrir modal e salvar dados localmente.

## Demonstração

Acesse o projeto localmente ou publique os arquivos em um servidor web para testar.

---
Projeto desenvolvido para praticar manipulação de DOM, armazenamento local e lógica de organização de tarefas.
