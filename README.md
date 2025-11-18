# Blazer Memory Game

Blazer Memory Game is a simple web-based memory card game built with Blazor WebAssembly.

## Features

- Flip cards to find matching pairs
- Tracks the number of moves taken
- Responsive UI with interactive gameplay
- Built using C# and Blazor WebAssembly

## How to Play

1. Click on a card to flip it.
2. Flip another card to try to find a matching pair.
3. If the cards match, they remain face up. If not, they flip back over.
4. Continue until all pairs are matched.
5. The game displays the number of moves taken and a congratulatory message upon completion.

## Project Structure

- `MemoryGame/Pages/Memory.razor` - Main game logic and UI
- `MemoryGame/Layout/MainLayout.razor` - Application layout
- `MemoryGame/wwwroot/` - Static assets and styles

## Getting Started

1. Clone the repository.
2. Open the solution in Visual Studio or VS Code.
3. Run the application using the built-in development server.

## Requirements

- .NET 7.0 SDK or later

## License

This project is for educational purposes.

## Build

dotnet build

## Run

dotnet run --project MemoryGame