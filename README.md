# Candidate-Control

This project consists of Java applications to handle different tasks. It includes classes for a candidate selection process, a counter with validation, and a basic hello world application.

## Project Structure

The project is organized into different packages and classes for specific functionalities.

 - ├── src
 - │ └── candidatura
 - │ ├── contador
 - │ │ ├── Contador.java
 - │ │ └── ParametrosInvalidosException.java
 - │ ├── ProcessoSeletivo.java
 - │ └── App.java
 - ├── bin
 - ├── lib
 - └── README.md

## Prerequisites

- Java Development Kit (JDK) installed.
- An IDE or text editor (e.g., Visual Studio Code).

## Getting Started

1. **Clone the repository** (if applicable):
   ```
   git clone <repository-url>
2 -Open the project:

Open Visual Studio Code.
Open the project folder.

3 - Build the project:

Make sure your tasks.json in the .vscode folder has the following configuration:


{
    "version": "2.0.0",
    "tasks": [
        {
            "type": "java (build)",
            "paths": [
                "${workspace}"
            ],
            "isFullBuild": true,
            "group": {
                "kind": "build",
                "isDefault": true
            },
            "problemMatcher": [],
            "label": "java (build): Build Workspace",
            "detail": "$(tools) Build all the Java projects in workspace."
        }
    ]
}

4 -Run the applications:

 - Open the terminal in Visual Studio Code.
 - Navigate to the src directory.
 - Compile the necessary Java files:

    javac -d ../bin candidatura/contador/Contador.java candidatura/ProcessoSeletivo.java candidatura/App.java

- Run the compiled classes:


Contador Application

This application prompts the user for two parameters and prints numbers between them. If the first parameter is greater than the second, an exception is thrown.

Usage

 - Enter the first parameter.
 - Enter the second parameter.
 - The application prints the numbers between the first and second parameters.

Example

    Digite o primeiro parâmetro
    1
    Digite o segundo parâmetro
    5
    Imprimindo o número 0
    Imprimindo o número 1
    Imprimindo o número 2
    Imprimindo o número 3

## Processo Seletivo Application

This application simulates a candidate selection process based on salary expectations.

## Usage
1 - Analyze candidates based on their salary expectations.
2 -Select candidates based on a base salary.
3 - Print the list of selected candidates.
4 - Simulate contacting the selected candidates.

# Example

    Processo seletivo
    LIGAR PARA O CANDIDATO
    AGUARDANDO DEMAIS CANDIDATOS
    LIGAR PARA O CANDIDATO COM CONTRAPROPOSTA

    -- Seleção de candidatos --
    Candidato: Maria - valor: 1800.0
    Maria selecionado para a vaga!
...
## App

A simple application that prints "Hello, World!".

## Usage
Run the application to see the output.

