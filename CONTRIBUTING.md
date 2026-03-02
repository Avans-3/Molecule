# Contributing to Molecule

Thank you for considering contributing to the Molecule project! Here are some guidelines to help you get started.

## Code Style Guidelines for C# 12 and .NET 8.0
- Follow [Microsoft's C# coding conventions](https://docs.microsoft.com/en-us/dotnet/standard/design-guidelines/coding-conventions) for consistency.
- Prefer using properties instead of public fields.
- Utilize async programming where appropriate, leveraging `async` and `await` keywords.
- Write unit tests for all new features and bug fixes.
- Use expression-bodied members where applicable to simplify code.
- Make use of records for immutable data structures.

## Development Setup Instructions
1. **Prerequisites**: Ensure you have the following installed on your machine:
   - [.NET SDK 8.0](https://dotnet.microsoft.com/download/dotnet/8.0)
   - An IDE like [Visual Studio](https://visualstudio.microsoft.com/) or [VS Code](https://code.visualstudio.com/)

2. **Clone the Repository**:
   ```bash
   git clone https://github.com/Avans-3/Molecule.git
   cd Molecule
   ```

3. **Restore Dependencies**:
   ```bash
   dotnet restore
   ```

4. **Build the Project**:
   ```bash
   dotnet build
   ```

5. **Run Tests**:
   ```bash
   dotnet test
   ```

## Pull Request Guidelines
- Ensure that your pull request includes tests for any new features or bug fixes.
- Provide a clear description of the changes made in the pull request.
- Link any relevant issues being addressed by the pull request.
- Keep pull requests focused on a single topic or issue.

## Commit Message Conventions
- Use the present tense (e.g., "Add feature" instead of "Added feature").
- Start the commit message with a short summary (50 characters or less), followed by a more detailed description if necessary.
- Reference issues in your commit messages (e.g., "Fixes #42").

## Issue Reporting Requirements
- For bugs, provide steps to reproduce, the expected behavior, and what actually happened.
- For feature requests, explain the use case and the benefits of the proposed feature.
- Label issues appropriately (e.g., bug, enhancement).

Thank you for contributing to the Molecule project! Your help is greatly appreciated!