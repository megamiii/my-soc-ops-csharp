<div align="center">

# 🎯 Soc Ops - Social Bingo Game

[![.NET](https://img.shields.io/badge/.NET-10.0-512BD4?style=for-the-badge&logo=dotnet)](https://dotnet.microsoft.com/)
[![Blazor](https://img.shields.io/badge/Blazor-WebAssembly-512BD4?style=for-the-badge&logo=blazor)](https://blazor.net/)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)
[![Play Game](https://img.shields.io/badge/🎮_Play_Now-FF6B35?style=for-the-badge)](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/)

*Break the ice at your next team mixer! Find colleagues who match fun questions and score a bingo!*

[🌐 Play the Game](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/) • [📚 Lab Guide](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/) • [🚀 Quick Start](#-quick-start)

![Soc Ops Game Preview](https://via.placeholder.com/800x400/512BD4/FFFFFF?text=Soc+Ops+Social+Bingo+Game)

</div>

---

## 🎉 What is Soc Ops?

Soc Ops is an interactive **social bingo game** designed for team building and networking events. Players answer fun, thought-provoking questions to mark squares on their bingo cards. The first to get 5 in a row wins!

### ✨ Key Features

- 🎯 **Interactive Bingo Gameplay** - Click squares to answer questions and mark your card
- 👥 **Team Building Focus** - Questions designed to spark conversations and connections
- 📱 **Responsive Design** - Works perfectly on desktop, tablet, and mobile
- 🎨 **Customizable Themes** - Multiple visual themes and question sets
- ⚡ **Blazor WebAssembly** - Fast, client-side performance with .NET

### 🎮 How to Play

1. **Start a Game** - Choose your theme and begin
2. **Answer Questions** - Click any square to reveal and answer a question
3. **Mark Squares** - Correct answers mark your bingo card
4. **Get 5 in a Row** - Horizontal, vertical, or diagonal wins!
5. **Celebrate** - Share your victory and connect with winners

---

## 🛠️ VS Code GitHub Copilot Agent Lab

This repository also serves as a comprehensive **hands-on workshop** for learning VS Code's Agent Mode with GitHub Copilot. Transform this simple bingo app into something amazing using AI-powered development!

### 📚 Workshop Modules

| # | Module | Duration | What You'll Learn |
|---|--------|----------|-------------------|
| [**00**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=00-overview) | Overview & Setup | 15 min | Agent Mode fundamentals |
| [**01**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=01-setup) | Context Engineering | 15 min | Teaching AI about your codebase |
| [**02**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=02-design) | Design-First Development | 15 min | AI-assisted UI/UX creation |
| [**03**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=03-quiz-master) | Custom Quiz Master | 10 min | Building specialized AI agents |
| [**04**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=04-multi-agent) | Multi-Agent Development | 20 min | Advanced AI collaboration |

> 💡 **Pro Tip**: Lab guides are available in [`workshop/`](workshop/) for offline reading.

---

## 🚀 Quick Start

### Prerequisites
- [.NET 10 SDK](https://dotnet.microsoft.com/download/dotnet/10.0) or higher
- VS Code with GitHub Copilot (for workshop)

### Run Locally

```bash
# Clone the repository
git clone https://github.com/megamiii/my-soc-ops-csharp.git
cd my-soc-ops-csharp

# Run the game
cd SocOps
dotnet run
```

Visit `http://localhost:5166` to play!

### 🐳 Docker Alternative

```bash
docker run -p 8080:80 dotnet-presentations/vscode-github-copilot-agent-lab:latest
```

---

## 🎨 Customization

### Adding New Questions
Edit `SocOps/Data/Questions.cs` to add your own question sets:

```csharp
public static readonly Question[] CustomQuestions = new[]
{
    new Question("What's your favorite icebreaker question?"),
    new Question("What's the most interesting project you've worked on?"),
    // Add more...
};
```

### Theming
Customize colors and styles in `SocOps/wwwroot/css/app.css` using the built-in utility classes.

---

## 🤝 Contributing

We welcome contributions! Whether it's new question sets, themes, or improvements:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

See [CONTRIBUTING.md](CONTRIBUTING.md) for detailed guidelines.

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

<div align="center">

**Made with ❤️ using .NET, Blazor, and GitHub Copilot**

[⭐ Star this repo](https://github.com/megamiii/my-soc-ops-csharp) if you found it helpful!

</div>
