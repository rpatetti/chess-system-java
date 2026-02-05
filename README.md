# Chess System Java

Projeto de jogo de xadrez em Java executado via console, desenvolvido como parte do curso de Java do professor Nelio Alves. O objetivo é praticar programação orientada a objetos, tratamento de exceções e arquitetura em camadas.

## Índice

- Sobre o projeto
- Tecnologias
- Pré-requisitos
- Como executar
- Como jogar
- Estrutura do projeto
- Conceitos praticados
- Próximos passos
- Autor

## Sobre o projeto

Este projeto implementa um jogo de xadrez completo no terminal, permitindo que dois jogadores disputem uma partida localmente. O sistema valida movimentos, trata erros de entrada e aplica regras especiais como roque, en passant e promoção de peão.

<img width="1592" height="1701" alt="chess-system-design" src="https://github.com/user-attachments/assets/88d0b171-6f3c-494f-9561-e0f67dc798f1" />

## Tecnologias

- Java (versão recomendada: 8 ou superior)
- IDE à sua escolha (Eclipse, IntelliJ IDEA, VS Code, etc.)

## Pré-requisitos

- JDK 8+ instalado
- Git instalado (opcional, para clonar o repositório)
- Um terminal (cmd, PowerShell, bash, etc.)

## Como executar

```bash
# Clonar o repositório
git clone git@github.com:rpatetti/chess-system-java.git
cd chess-system-java

# Compilar os arquivos (se estiver compilando via terminal)
javac -cp src -d bin src/application/Program.java

# Executar o jogo
cd bin
java application.Program
