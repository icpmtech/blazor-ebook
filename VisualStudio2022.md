Usar o Visual Studio 2022

1. Clonar e abrir o repositório

File → Open → Folder… e selecciona a raiz do projecto (blazor‑ebook).

O Visual Studio detecta automaticamente as soluções; aceita a sugestão para gerar os .sln.



2. Seleccionar o capítulo a experimentar

No Solution Explorer expande src/ e clicar‑direito → Set as Startup Project no exemplo desejado (ex.: StateDemo).



3. Gestor de Pacotes NuGet

Se aparecerem avisos de pacotes, abre Tools → NuGet Package Manager → Manage NuGet Packages for Solution e clica Restore.



4. Executar com Hot Reload

Prime F5 (Debug) ou Ctrl+F5 (Run) – o browser abre em https://localhost:5001/.

Qualquer alteração em .razor, .cs ou .css é aplicada em tempo‑real via Hot Reload.



5. Debugging

Coloca breakpoints em C# ou em código JavaScript (janela Sources do DevTools).

Usa Diagnostic Tools (menu Debug → Windows) para memória, CPU e eventos.



6. Múltiplos projectos simultâneos

Para comparar exemplos, abre Solution Properties → Multiple startup projects, marca Start nos projectos pretendidos.



7. Contêineres e MAUI

Docker: instale o Visual Studio Container Tools e marca Enable Docker Support no wizard Publish.

MAUI Blazor: necessitas do Mobile Development with .NET workload; selecciona em Debug Target o dispositivo Android, iOS (Hot Restart) ou Windows.



8. Publicar

Right‑click → Publish para criar perfil Folder, Azure App Service ou Docker Container Registry.

Siga os passos guiados; o VS gera YAML ou ficheiros de pipeline quando aplicável.




> Dica: se preferires Visual Studio Code, abre a pasta, aceita a recomendação para instalar a extensão C# Dev Kit e executa dotnet watch run no terminal.




