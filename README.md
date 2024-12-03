```markdown
# MiniC Assembler

## Visão Geral

Assembler para a Arquitetura RISC de 8 bits, desenvolvido para funcionar em conjunto com o **Compilador MiniC**.

## Autor

Arthur Silva Matias 

## Linguagens e Ferramentas Utilizadas:
- **Linguagem de Programação**: C++
- **Sistema de Build**: CMake

## Descrição

Este projeto consiste no código fonte de um **assembler** desenvolvido para a arquitetura **RISC**. Criada para fins educacionais pelo professor **Juan Colonna**, da **Universidade Federal do Amazonas (UFAM)**. Ele foi projetado para funcionar com o **Compilador do MiniC**, uma linguagem baseada em **C**,  

O assembler converte o código assembly gerado pelo **Compilador MiniC** em código de máquina executável na arquitetura RISC. A simplicidade desta arquitetura permite que os alunos compreendam como programas são traduzidos e executados em um sistema de baixo nível.

O projeto está organizado em diretórios bem definidos,incluindo:
- **`src/`**: Código fonte do assembler.
- **`headers/`**: Arquivos de cabeçalho do C++.
- **`testes/`**: Testes automatizados do assembler.


## Repositório do Compilador

Este assembler foi desenvolvido para trabalhar em conjunto com o **Compilador MiniC**, disponível no repositório abaixo:

[Repositório do Compilador MiniC](https://github.com/Arthur-WhiteCorp/Compilador-MiniC)

Consulte o repositório do compilador para instruções sobre como gerar código assembly compatível com este assembler.

## Repositório do Emulador de Arquitetura RISC

Após a montagem do código de máquina, ele pode ser executado e testado utilizando o **Emulador de Arquitetura RISC**:

[Repositório do Emulador de Arquitetura RISC](https://github.com/Arthur-WhiteCorp/Emulador-De-Arquitetura-De-Computador)

Consulte o repositório do emulador para instruções detalhadas sobre a execução do código gerado.

## Execução

1. **Clone este repositório:**
   ```bash
   git clone https://github.com/Arthur-WhiteCorp/MiniC-Assembler.git
   cd MiniC-Assembler
   ```

2. **Compile o programa:**
   ```bash
   ./compile.sh
   ```

3. **Execute o Assembler:**
   ```bash
   ./build/main.cpp <arquivo.asm>
   ```

---

Este projeto visa não apenas a criação de um assembler funcional, mas também a promoção de uma compreensão mais profunda dos conceitos de **linguagens assembly**, **compiladores**, e **arquitetura de sistemas**.
```