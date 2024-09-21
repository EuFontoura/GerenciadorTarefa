# Gerenciador de Lista de Tarefas

Este projeto é um simples gerenciador de lista de tarefas desenvolvido em Python. Ele permite ao usuário adicionar, visualizar, atualizar, completar e deletar tarefas concluídas de uma lista. O desenvolvimento deste projeto foi realizado com base no curso da **Rocketseat**.

## Índice

- [Introdução](#introdução)
- [Funcionalidades](#funcionalidades)
- [Instalação](#instalação)
- [Uso](#uso)
- [Exemplos](#exemplos)
- [Licença](#licença)

## Introdução

O Gerenciador de Lista de Tarefas é uma aplicação de linha de comando que permite a manipulação de tarefas de forma interativa. A aplicação foi projetada para ser simples e objetiva, permitindo adicionar tarefas, marcar como completas e gerenciar a lista de forma prática.

## Funcionalidades

- **Adicionar Tarefa**: Insere uma nova tarefa na lista.
- **Ver Tarefas**: Exibe a lista de tarefas e seus status (completa ou incompleta).
- **Atualizar Tarefa**: Permite renomear uma tarefa existente.
- **Completar Tarefa**: Marca uma tarefa como concluída.
- **Deletar Tarefas Completadas**: Remove todas as tarefas que já foram concluídas.
- **Menu Interativo**: Navegue entre as opções do menu para gerenciar suas tarefas.

## Instalação

1. Certifique-se de ter o Python instalado em seu sistema. Você pode verificar a instalação rodando o seguinte comando no terminal:

   ```bash
   python --version

2. Clone este repositório ou copie o código da aplicação para o seu ambiente de desenvolvimento.

3. Não há dependências externas, então basta executar o script diretamente:
   ```bash
   python gerenciador_de_tarefas.py
   ```

## Uso
Ao rodar o script, o menu interativo será exibido no terminal, permitindo que o usuário escolha entre as seguintes opções:

1. **Adicionar tarefa:** Insere uma nova tarefa na lista.
2. **Ver tarefas:** Exibe todas as tarefas adicionadas, com status de completa ou incompleta.
3. **Atualizar tarefa:** Renomeia uma tarefa existente selecionada pelo número.
4. **Completar tarefa:** Marca uma tarefa como concluída.
5. **Deletar tarefas completadas:** Remove todas as tarefas que foram completadas.
6. **Sair:** Encerra a aplicação.

## Exemplos

Aqui está um exemplo de como a aplicação funciona na prática:

```bash
Menu do Gerenciador de Lista de tarefas:
1. Adicionar tarefa
2. Ver tarefa
3. Atualizar tarefa
4. Completar tarefa
5. Deletar tarefas completadas
6. Sair

Digite a sua escolha: 1
Digite o nome da tarefa que deseja adicionar: Comprar pão
Tarefa Comprar pão foi adicionada com sucesso!

Menu do Gerenciador de Lista de tarefas:
1. Adicionar tarefa
2. Ver tarefa
3. Atualizar tarefa
4. Completar tarefa
5. Deletar tarefas completadas
6. Sair

Digite a sua escolha: 2

Lista de tarefas:
1. [ ] Comprar pão
```

## Licença

Este projeto foi desenvolvido para fins educativos e não possui uma licença específica. Sinta-se à vontade para modificar e distribuir conforme suas necessidades.

Projeto desenvolvido com base no curso da <a href="https://www.rocketseat.com.br/">Rocketseat.
