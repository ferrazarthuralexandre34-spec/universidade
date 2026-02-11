# Projeto universidade

Modelagem em Orientação á Objetos das Entidades Alunos, Cursos e turmas.

## Caso de uso

```mermaid
flowchart LR
    Usuario([Secretaria])

    UC1((Cadastrar Alunos))
    UC2((Editar Alunos))
    UC3((Transferir Aluno))

    Usuario --> UC1
    Usuario --> UC2
    Usuario --> UC3
```

## Diagrama de Clases

```mermaid
classDiagram
    class Aluno{
        - Nome
        - Email
        - CPF
        - Telefone
        - Endereço
        - Matricula
        + cadastrar()
        + editar()
        + Transferir()
    }
```

## Transferencia
- **VSCode**: IDE(Interface de Desenvolvimento).

- **Mermaid**: Linguagem para confecção de Diagramas em documentos MD (Mark Down).

- **Git Lens**: Interface gráfica para o versionamento .git integrada ao VSCode.