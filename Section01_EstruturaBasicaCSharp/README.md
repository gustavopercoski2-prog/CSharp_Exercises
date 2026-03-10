## Primeiro programa básico em C#

O clássico "Hello World", usando o formato básico mais antigo. O objetivo foi entender a estrutura da linguagem e como exibir uma mensagem no console.

### Código

```csharp
using System;

namespace PrimeiroProjeto
{
    internal class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("Hello World!");
        }
    }
}
```

### Conceitos aprendidos

* **namespace**: serve pra organizar o código dentro do projeto
* **class**: é onde o código do programa fica
* **Main**: é o ponto de início do programa
* **Console.WriteLine()**: mostra uma mensagem no console

---