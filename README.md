# FiddleLang — Compilador em ANTLR4

Este projeto implementa um compilador completo para a linguagem **FiddleLang**, desenvolvido utilizando **ANTLR4** como parte do trabalho de Teoria da Computação e Compiladores.

O compilador faz análise léxica, sintática, semântica e validação de tipos, além de permitir geração de código alvo.

---

## 🎯 Objetivos do Projeto

- Definir e implementar a gramática da linguagem FiddleLang  
- Criar o analisador léxico e sintático usando ANTLR4  
- Implementar verificações semânticas:
  - Tipos
  - Escopo
  - Uso de variáveis declaradas
  - Operações válidas para cada tipo  
- Implementar estruturas obrigatórias:
  - 3 tipos de variáveis (`int`, `float`, `string`)
  - `if ... else`
  - Repetições: `while`, `do ... while`, `for`
  - Precedência correta em expressões
  - Atribuições
  - `scanf` e `printf`
  - Aceitar números decimais
  - Ignorar tabs, espaços e quebras de linha
- Exibir erros quando existirem  
- Informar quando o código está correto  
- **Extra:** Geração de código em Java ou C  

---

## 🧩 Estrutura da Linguagem FiddleLang

### • Declaração de variáveis
```txt
int x;
float y;
string nome;
