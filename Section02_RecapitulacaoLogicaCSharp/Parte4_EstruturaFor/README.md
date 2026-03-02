# 🔁 Exercícios: Estruturas de Repetição (for)

![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-5C2D91?style=for-the-badge&logo=.net&logoColor=white)
![Lógica de Programação](https://img.shields.io/badge/Lógica_de_Programação-000000?style=for-the-badge&logo=visualstudiocode&logoColor=white)

Diretório reservado para a resolução de 7 exercícios de lógica usando a estrutura de repetição `for`, do curso **[C# COMPLETO Programação Orientada a Objetos + Projetos](https://www.udemy.com/course/programacao-orientada-a-objetos-csharp/)**, ministrado pelo professor **Nelio Alves** na plataforma **Udemy**.

📌 **Foco:** Estruturas de repetição com quantidade determinada de passos (laço `for`).  
📊 **Progresso:** 🚧 1/7 concluídos.

---

## 🛠️ Conhecimentos Desenvolvidos

*(Em andamento...)*

---

## 📋 Resumo dos Exercícios

*(Em andamento...)*

---

## 💻 Soluções e Códigos

*(Clique nos títulos abaixo para exibir o enunciado, o código-fonte e o resultado no terminal)*

---

<details>
<summary><strong>Exercício 01: Ímpares</strong></summary>

### 📷 Enunciado:
![Enunciado do Exercício](./assets/Exercicio01_Impares.png)

### 💻 Código:
```csharp
namespace OddNumbers {
    class Program {
        static void Main(string[] args) {

            int x = int.Parse(Console.ReadLine()!);

            for (int i = 1; i <= x; i++) {
                if (i % 2 != 0) {
                    Console.WriteLine(i);
                }
            }
        }
    }
}
```

### 🖥️ Saída no Terminal:
![Resultado no Terminal](./assets/Terminal_Exercicio01_Impares.png)

</details>