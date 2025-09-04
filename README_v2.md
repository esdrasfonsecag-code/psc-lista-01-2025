# 🖥️ Atividade ADS – Programa em Portugol

> Projeto realizado como atividade do curso de **ADS**  
> Professor: Daniel Henrique Matos de Paiva  

---

## 📖 Descrição
Este projeto contém um programa desenvolvido em **Portugol**, que realiza a leitura de informações do usuário: **nome**, **idade** e **altura**, e exibe essas informações de forma organizada no console.  

✨ **Objetivo:** praticar **entrada e saída de dados**, **uso de variáveis**, **concatenação de mensagens** e lógica básica de programação.

---

## 📂 Conteúdo do Repositório

| Arquivo | Linguagem | Descrição |
|---------|-----------|-----------|
| `meu_programa.portugol` | 🟣 Portugol | Lê nome, idade e altura e mostra na tela |

---

## ⚙️ Como Rodar

1️⃣ Abra o **Portugol Studio**  
2️⃣ Crie um novo arquivo e cole **todo este código**:

```portugol
programa {
  funcao inicio() {
    
    cadeia nome
    real altura
    inteiro idade

    escreva("Digite sua idade: ")
    leia(idade)

    escreva("Digite sua altura (use ponto): ")
    leia(altura)  

    escreva("Digite o seu nome completo: ")
    leia(nome)

    escreva("\nOlá mundo! Seu nome é ", nome, ", você tem ", idade, " anos e mede ", altura, " metros.")
  }
}
```
▶️ Iniciar execução clicando em Executar

⌨️ Preencha os dados no console: digite sua idade, altura e nome
