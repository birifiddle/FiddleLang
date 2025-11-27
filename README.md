# Compilador — Trabalho de Teoria da Computação e Compiladores

Este projeto implementa um compilador completo utilizando **ANTLR4**, baseado em uma linguagem criada pelo grupo.  
O compilador realiza análise léxica, sintática e semântica, além de gerar código alvo e validar tipos, escopos e estruturas exigidas no enunciado.

---

## 🎯 Objetivos do Projeto
Desenvolver um compilador funcional contendo:

- Gramática completa ANTLR sem recursão à esquerda e sem produções vazias  
- 3 tipos de variáveis  
- Estrutura `if ... else`  
- Pelo menos duas estruturas de repetição (`while`, `do...while`, `for`)  
- Expressões matemáticas com precedência correta  
- Atribuições  
- Comandos `scanf` e `printf`  
- Aceitar números decimais  
- Ignorar espaços, tabs e quebra de linha  
- Exibir erros detalhados  
- Confirmar quando o código está correto  
- **Extra:** verificação de tipos, escopo e geração de código (Java ou C)

---

## 📁 Estrutura da Linguagem Criada
A linguagem possui:

- **Tipos**: `int`, `float`, `string`
- **Declarações**:
  ```txt
  int x;
  float y;
  string nome;
