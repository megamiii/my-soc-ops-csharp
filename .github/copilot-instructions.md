# Project Guidelines

## Development Checklist
**Mandatory before committing or deploying:**
- [ ] **Lint**: Run `dotnet build SocOps/SocOps.csproj` to check for code analysis warnings/errors
- [ ] **Build**: Run `dotnet build SocOps/SocOps.csproj` to ensure successful compilation
- [ ] **Test**: Run `dotnet test` (when unit tests are implemented)

## Code Style
Follow C# and Blazor best practices with nullable reference types and implicit usings enabled. Reference existing components in `Components/` for Blazor patterns and naming conventions.

Linting rules enforced via .editorconfig and Microsoft.CodeAnalysis.NetAnalyzers:
- Unused variables (CS0168, CS0219) treated as errors
- Async methods without await (CS1998) treated as errors
- Accessibility modifiers required on all members
- Readonly fields preferred
- Use 'var' when type is apparent

## Architecture
Blazor WebAssembly application implementing a social bingo game. Core architecture includes:
- UI components in `Components/` (BingoBoard, GameScreen, etc.)
- Game logic services in `Services/` (BingoGameService, BingoLogicService)
- Data models in `Models/` and question data in `Data/`

## Build and Test
- Build: `dotnet build SocOps/SocOps.csproj`
- Run dev server: `dotnet run --project SocOps/SocOps.csproj`
- No automated tests currently implemented

## Conventions
- Use custom CSS utility classes from `wwwroot/css/app.css` for consistent styling
- Follow frontend design guidelines in `.github/instructions/frontend-design.instructions.md` to create distinctive, non-generic UI aesthetics
- Reference `workshop/` guides for development workflows and best practices