1. Scanner
    To build: javac -d build/ lox/*.java
    To execute: java -cp build/ lox.Lox
2. GenerateAst is a tool script to generate all Expression classes
    javac -d build/ src/tool/GenerateAst.java
    java -cp build/ tool.GenerateAst src/lox
