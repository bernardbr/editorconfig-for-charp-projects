# EditorConfig for C# Projects

This repository contains a suggested [EditorConfig](https://editorconfig.org/) configuration file specifically tailored for C# projects. The configuration includes settings to help maintain consistent code style across different editors and IDEs, along with guidelines that promote clean code practices.

## Overview

The provided `.editorconfig` file is designed to:

- **Enforce Consistent Formatting:**
  Configure indentation, end-of-line characters, maximum line length, and encoding for various file types (code, XML, JSON, etc.).

- **Apply .NET Coding Style Guidelines:**
  Set rules for using auto-properties, simplified expressions, null propagation, and more.

- **Define Naming Conventions:**
  Specify naming rules for private/internal fields and constants to ensure consistency across your codebase.

- **Include ReSharper Directives:**
  Add additional formatting and spacing rules for teams using ReSharper or Rider, such as:
  - Preserving attribute arrangement.
  - Enforcing the use of braces in control structures.
  - Managing spacing around operators, commas, and semicolons.
  - Controlling blank lines around namespaces and between type members.

- **Treat Nullability Strictly:**
  Configure the compiler to treat various nullability warnings as errors, ensuring more robust and null-safe code.

## Features

- **Global Settings:**
  - Uses spaces for indentation.
  - Trims trailing whitespace and ensures files end with a newline.
  - Sets the maximum line length to 120 characters.

- **File Specific Configurations:**
  - Code files (`*.cs, *.csx, *.vb, *.vbx`) use 4 spaces for indentation.
  - XML project and configuration files use 2 spaces.
  - JSON files also use 2 spaces.

- **.NET Code Style and Naming Conventions:**
  - Preferences for `is null` checks, simplified boolean expressions, and string interpolation.
  - Explicit access modifiers required for all members.
  - Sorted `using` directives with System namespaces appearing first.
  - Naming rules for private/internal fields (`_camelCase`) and constants (UPPERCASE).

- **C# Specific Rules:**
  - Recommendations for using `var` where appropriate.
  - Guidance on using expression-bodied members, pattern matching, inline variable declarations, and throw expressions.
  - Preferred order of modifiers to enhance code readability.

- **ReSharper Settings:**
  - Enforces consistent attribute arrangement, brace usage, and spacing around operators, commas, semicolons, and parentheses.
  - Defines blank line rules for namespaces and between type members.

- **Nullability Treatment:**
  - Treats various compiler warnings related to nullability as errors, encouraging safer code practices.

## How to Use

1. **Copy the File:**
   Simply place the provided `.editorconfig` file at the root of your C# project or solution repository.

2. **Editor/IDE Integration:**
   Most modern editors (e.g., Visual Studio, Visual Studio Code, Rider) support EditorConfig out of the box or via plugins. Once the file is present, your editor will automatically adopt these settings.

3. **Customize as Needed:**
   While this configuration is a suggestion based on best practices, feel free to modify any rules to better suit your team’s coding conventions.

## Contributing

Contributions and improvements to this configuration are welcome! If you have suggestions or notice any issues, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.

## References

- [EditorConfig Documentation](https://editorconfig.org/)
- [ReSharper EditorConfig Index](https://www.jetbrains.com/help/resharper/EditorConfig_Index.html)
- [.NET Coding Conventions](https://docs.microsoft.com/en-us/dotnet/csharp/fundamentals/coding-style/coding-conventions)

---
❤️ Made with love!

💻 Happy coding!
