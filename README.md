# Blazor Essencial para Estudantes: Cria as Tuas Primeiras Apps Web em C#


## Sobre o projecto

Repositório que acompanha o e‑book **Blazor para Iniciantes**, fornecendo o código‑fonte de todos os exemplos, exercícios e capítulos. O objectivo é permitir que estudantes e autodidactas pratiquem cada conceito à medida que lêem.

## Estrutura

```
📂 src/            # Projectos Blazor por capítulo
📂 solutions/      # Soluções completas dos exercícios (Cap. 16)
📂 assets/         # Imagens, modelos ONNX, scripts SQL
📄 README.md       # Este ficheiro
```

### Pasta `src/`

| Capítulo | Projecto | Descrição |
|----------|----------|-----------|
| 01‑06 | `NovaBasics` | Fundamentos de componentes, routing e formulários |
| 07 | `StateDemo` | Cascading, Fluxor e SignalR |
| 08 | `AuthDemo` | Identity + Google OAuth |
| … | … | … |

*(Ver índice completo no e‑book ou em `docs/Índice.md`)*

## Requisitos

* [.NET 8 SDK](https://dotnet.microsoft.com/) ou superior  
* Node.js 18+ (para exemplos de interop JS)  
* VS Code ou Visual Studio 2022 (com extensão C# Dev Kit)  
* Opcional: Docker 24+ para exemplos de deployment

## Como correr um exemplo

```bash
cd src/StateDemo
dotnet run
```
Abra o browser em <https://localhost:5001>.

## Exercícios

Cada pasta de capítulo contém ficheiros `README_EXERCISE.md` com instruções. Tente resolver antes de ver as soluções em `solutions/`.

## Contribuir

1. *Fork* o repositório  
2. Crie uma *branch*: `git checkout -b feature/minha‑ideia`  
3. *Commit* das alterações: `git commit -m "Adiciona exemplo X"`  
4. *Push*: `git push origin feature/minha‑ideia`  
5. Abra um **Pull Request**

Sinta‑se livre para abrir *issues* com dúvidas, correcções ou melhoramentos.

## Licença

Este material é licenciado sob **MIT License** — consulte o ficheiro `LICENSE`.

## Agradecimentos

À comunidade .NET e a todos os que contribuem com *packages*, exemplos e *feedback* que tornam Blazor melhor a cada versão.

