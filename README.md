<p align="center">
  <img src=".github/assets/header.png">
</p>

> 👨‍🚀 **Repo com o propósito de estudos**

# **Executar com node**
1º - npx tsc src/index.ts  --> Transpilar para JS
2º - node ./build/index.js --> executar o TS 

# **Automatizar a execução**
1º - npx tsc --init --> criar o TSCONFIG.JSON
2º - Procurar no site https://www.typescriptslang.org/tsconfig quais as opções de alteração dentro do arquivo TSCONFIG.JSON
3º - target --> Versão do ts que irá ser usado
4º - rootDir: --> apontar para src o diretório de entrada
5º - outDir: --> apontar para build irá gerar os arquivos de saída
6º - Alterar o arquivo package.json
7º -  "start": "npx tsc && node build/index.js", --> configurar o pnx para executar a transpilação com npx e a compilação com node
8º -  npm run start --> rodar index.js

# **Melhorar a Automatização para execução**
1º - npm install ts-node-dev -D -> instalar um servidor node local que entende TS -D(desenvolvedor)
2º - "start:dev": "ts-node-dev --respawn --transpile-only src/index.ts", --> configurar arquivo package.json
3º - npm run start:dev --> executar

# 🅰️ Sobre este repositório

Fiz esse repositório para estudos, o objetivo é ter exemplos práticos das principais competências para se trabalhar com `Angular`

### 📦 Componentização

| #   |     | sub competência     | 🔗                                                                                                                                                                                                                  |
| --- | --- | ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1   | 🅰️  | web components      | [![Material de Apoio](https://img.shields.io/badge/Ver%20Material-E94D5F?style=for-the-badge)](https://github.com/felipeAguiarCode/angular-playground/tree/main/C1%20-%20Web%20Components)                          |
| 2   | 🅰️  | typescript angular  | [![Material de Apoio](https://img.shields.io/badge/Ver%20Material-E94D5F?style=for-the-badge)](https://github.com/felipeAguiarCode/angular-playground/tree/main/C2%20-%20Typescript%20para%20Angular)               |
| 3   | 🅰️  | componentes angular | [![Material de Apoio](https://img.shields.io/badge/Ver%20Material-E94D5F?style=for-the-badge)](https://github.com/felipeAguiarCode/angular-playground/tree/main/C5%20-%20Trabalhando%20com%20componentes%20Angular) |
| 4   | 🅰️  | life cycle hooks    | [![Material de Apoio](https://img.shields.io/badge/Ver%20Material-E94D5F?style=for-the-badge)](https://github.com/felipeAguiarCode/angular-playground/tree/main/C6%20-%20Life%20Cycle%20Hooks)                      |

### 📦 Organização e serviços

| #   |     | sub competência  | 🔗                                                                                                                                                                                              |
| --- | --- | ---------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 5   | 🅰️  | diretivas        | [![Material de Apoio](https://img.shields.io/badge/Ver%20Material-E94D5F?style=for-the-badge)](https://github.com/felipeAguiarCode/angular-playground/tree/main/C7%20-%20Diretivas)             |
| 6   | 🅰️  | modulos          | [![Material de Apoio](https://img.shields.io/badge/Ver%20Material-E94D5F?style=for-the-badge)](https://github.com/felipeAguiarCode/angular-playground/tree/main/C8%20-%20Modulos/modulo-proj)   |
| 7   | 🅰️  | rotas            | [![Material de Apoio](https://img.shields.io/badge/Ver%20Material-E94D5F?style=for-the-badge)](https://github.com/felipeAguiarCode/angular-playground/tree/main/C9%20-%20Rotas/rotas)           |
| 8   | 🅰️  | services e Pipes | [![Material de Apoio](https://img.shields.io/badge/Ver%20Material-E94D5F?style=for-the-badge)](https://github.com/felipeAguiarCode/angular-playground/tree/main/C10%20-%20Services%20e%20Pipes) |
| 9   | 🅰️  | guards           | [![Material de Apoio](https://img.shields.io/badge/Ver%20Material-E94D5F?style=for-the-badge)](https://github.com/felipeAguiarCode/angular-playground/tree/main/C11%20-%20Guards)               |

