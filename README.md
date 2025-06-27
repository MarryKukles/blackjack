# 🃏 Blackjack - 21 | Jogo de Cartas em Java

Este projeto foi desenvolvido como parte da **A3 - Trabalho Prático** do Centro Universitário de Belo Horizonte, com o objetivo de implementar um jogo de cartas utilizando Java e o padrão de projeto **MVC (Model-View-Controller)**, de forma simplificada.

---

## 🎮 Sobre o jogo

O Blackjack, também conhecido como 21, é um jogo de cartas onde o objetivo é ter uma mão com valor mais próximo de 21 do que o dealer, sem ultrapassar esse número.

Este projeto conta com:

* **Interface gráfica** simples utilizando **Swing**
* Botões de interação: `Hit`, `Stay` e `Restart`
* Lógica do jogo implementada no padrão **MVC simplificado**
* Feedback visual de vitória, derrota ou empate

---

## 🛠️ Estrutura do projeto

| Camada                       | Responsabilidade                                                                                                                                                                                |
| ---------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Model (Modelo)**           | A classe `BlackJack` mantém o estado do jogo (baralho, mãos, pontuações) e implementa a lógica principal (distribuição de cartas, cálculo de pontos, regras do Blackjack).                      |
| **View (Visão)**             | A interface gráfica é construída com `JFrame`, `JPanel` e `JButton`. O método `paintComponent(Graphics g)` na classe `gamePanel` desenha os elementos do jogo na tela, como cartas e mensagens. |
| **Controller (Controlador)** | Os botões (`hitButton`, `stayButton`, `restartButton`) controlam as interações do usuário, chamando métodos da classe `BlackJack` para atualizar o estado do jogo.                              |

> ⚠️ **Observação:** O projeto adota o padrão MVC de forma simplificada, com uma separação básica entre lógica, interface e controle. Isso facilita a leitura, manutenção e futuras melhorias.

---

## ✨ Tecnologias utilizadas

* Java
* Swing (para a interface gráfica)

---

## 💡 Possíveis melhorias futuras

* Adicionar animações para as cartas
* Implementar sons do jogo
* Suporte a múltiplos jogadores

## 🚀 Como rodar

1️⃣ **Clone o repositório:**

```bash
git clone https://github.com/MarryKukles/blackjack.git
```

2️⃣ **Compile o projeto:**

```bash
javac *.java
```

3️⃣ **Execute o jogo:**

```bash
java Main
```

---

📌 **Desenvolvido como trabalho acadêmico com fins educativos.**
