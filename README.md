# \# Framework de Validação

# 

# Atividade 01 da disciplina \*\*Java II — Tópicos Avançados\*\*, da Pós-Graduação em Desenvolvimento Java.

# 

# Pequeno \*\*framework de validação\*\* construído com recursos avançados da linguagem Java. As regras de validação são declaradas por \*\*anotações personalizadas\*\* e processadas em tempo de execução via \*\*Reflection\*\*, evitando repetir as mesmas verificações em cada classe.

# 

# \## 🧠 Conceitos aplicados

# 

# \- Anotações personalizadas: `@NaoNulo`, `@Tamanho` e `@Positivo`

# \- Reflection para inspecionar classes, campos e anotações em tempo de execução

# \- Mecanismo genérico de validação com \*\*Generics\*\*

# \- Compreensão de \*\*Type Erasure\*\*

# \- \*\*Records\*\* para representar dados de forma concisa

# \- \*\*Sealed Classes\*\* para restringir a hierarquia de tipos

# \- \*\*Pattern Matching\*\* para verificações e conversões de tipo mais expressivas

# \- `BigDecimal` para valores monetários

# \- Objetos para representar o resultado da validação e as violações encontradas

# \- Testes automatizados com Maven e JUnit

# 

# \## 🔄 Fluxo da solução

# 

# ```text

# Objeto

# &#x20;  ↓

# Validador

# &#x20;  ↓

# Reflection

# &#x20;  ↓

# Anotações presentes nos campos

# &#x20;  ↓

# Regras de validação

# &#x20;  ↓

# Resultado da validação

# &#x20;  ↓

# Violações encontradas

# ```

# 

# \## 🛠️ Tecnologias

# 

# Java · Maven · JUnit · IntelliJ IDEA · Git · GitHub

# 

# \## 🗂️ Estrutura do projeto

# 

# ```text

# .

# ├── src/

# ├── pom.xml

# └── README.md

# ```

# 

# \## ▶️ Como executar

# 

# O projeto pode ser aberto no \*\*IntelliJ IDEA\*\* como projeto Maven, ou executado pelo Maven Wrapper.

# 

# Executar os testes:

# 

# ```bash

# \# Windows

# mvnw.cmd test

# 

# \# Linux / macOS

# ./mvnw test

# ```

# 

# Compilar o projeto:

# 

# ```bash

# \# Windows

# mvnw.cmd clean package

# 

# \# Linux / macOS

# ./mvnw clean package

# ```

# 

# Os diretórios `target/` e os arquivos da IDE não são versionados, conforme o `.gitignore`.

# 

# \## 🎯 Objetivo acadêmico

# 

# Demonstrar como o Java pode ser usado para criar componentes \*\*reutilizáveis e extensíveis\*\*, aplicando recursos do Java moderno em um caso prático.

# 

# Este repositório faz parte do portfólio acadêmico da Pós-Graduação em Desenvolvimento Java.

