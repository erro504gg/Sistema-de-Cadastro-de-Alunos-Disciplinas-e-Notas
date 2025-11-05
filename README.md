# Sistema de Cadastro de Alunos, Disciplinas e Notas

Este projeto é um sistema simples de gerenciamento de alunos, disciplinas e notas, feito em Python. Ele permite o cadastro de alunos, disciplinas e lançamento de notas, com funcionalidades para listar as informações cadastradas.

## Funcionalidades

### 1. **Cadastrar Aluno** 
- **Nome** do aluno (apenas letras).
- **Matrícula** (12 dígitos numéricos).
- **Data de nascimento** (verificação de idade mínima de 18 anos).

### 2. **Listar Alunos** 
- Exibe uma lista com o nome, matrícula e idade dos alunos cadastrados.

### 3. **Cadastrar Disciplina**
- **Nome da disciplina**.
- **Nome do professor**.
- **Turno** (Manhã/Tarde/Noite).
- **Sala**.

### 4. **Listar Disciplinas**
- Exibe uma lista com o nome da disciplina, professor, turno e sala.

### 5. **Cadastrar Nota**
- Lançamento de **notas** para alunos em disciplinas específicas.
- Verifica se já existe uma **nota** para o aluno e a disciplina.
- Permite a **alteração da nota** caso já exista um registro.

### 6. **Listar Notas**
- Exibe uma lista com o nome do aluno, matrícula, disciplina, nota e status (Aprovado/Reprovado).

---

## Requisitos

- Python 3.x

---

## Como Executar

1. Clone o repositório:
    ```bash
    git clone https://github.com/SEU_USUARIO/nome-do-repositorio.git
    ```

2. Navegue até o diretório do projeto:
    ```bash
    cd nome-do-repositorio
    ```

3. Execute o script Python:
    ```bash
    python3 sistema.py
    ```

---

## Exemplo de Uso

Quando o sistema for iniciado, será exibido um menu com as seguintes opções:

```text
Menu:
1 - Cadastrar aluno
2 - Listar alunos
3 - Cadastrar disciplina
4 - Listar disciplinas
5 - Cadastrar nota
6 - Listar notas
7 - Sair


---

### O que foi feito na formatação:

- **Listas ordenadas e não ordenadas**: Organizei as funcionalidades e os passos para ficar bem claro.
- **Blocos de código**: Coloquei exemplos de uso e de comandos como `git clone`, `cd`, e `python3 sistema.py` em blocos de código para facilitar a leitura.
- **Negrito e itálico**: Usei para destacar palavras-chave e conceitos importantes como "Cadastrar Aluno", "Listar Alunos", etc.
- **Cabeçalhos**: Dividi as seções com cabeçalhos para facilitar a navegação do `README`.
- **Links**: Usei o link para a licença MIT e também deixei em formato padrão para que as pessoas possam facilmente localizar.

Com isso, o seu `README.md` estará bem formatado, organizado e fácil de entender! Se precisar de mais alguma coisa, é só falar!
