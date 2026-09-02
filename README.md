# 🚗 TypeScript Tuning

> Simulador de oficina de tuning automotivo, feito em TypeScript puro e executado via terminal.

## 📋 Sobre o projeto

**TypeScript Tuning** é uma aplicação de linha de comando onde o usuário escolhe um carro entre opções pré-disponibilizadas e personaliza o veículo adicionando peças de **estética** e de **performance**. Ao final do processo, o sistema exibe um resumo completo do tuning realizado: todas as peças adicionadas, o ganho de potência total e demais estatísticas do carro.

O projeto foi desenvolvido como trabalho acadêmico, com foco em praticar lógica de programação, orientação a objetos e manipulação de dados em TypeScript, sem uso de frameworks externos.

## ✨ Funcionalidades

- 🚘 Seleção de um carro entre modelos pré-cadastrados
- 🎨 Catálogo de peças de **estética** (rodas, adesivos, pintura, etc.)
- 🏎️ Catálogo de peças de **performance** (motor, escape, turbo, suspensão, etc.)
- ➕ Adição de peças ao carro selecionado através de menus interativos
- 📊 Resumo final do tuning, com:
  - Lista de todas as peças instaladas
  - Ganho total de potência (cavalos/HP)
  - Outras estatísticas resultantes da customização

## 🛠️ Tecnologias

- **TypeScript** (100% do código)
- **Node.js** como ambiente de execução

## 📦 Pré-requisitos

Antes de rodar o projeto, você precisa ter instalado:

- [Node.js](https://nodejs.org/) (versão 18 ou superior recomendada)
- npm (instalado junto com o Node.js)

## 🚀 Como executar

```bash
# Clone o repositório
git clone <url-do-seu-repositorio>

# Entre na pasta do projeto
cd typescript-tuning

# Instale as dependências
npm install

# Execute o projeto
npm start
```

> 💡 Se o `package.json` ainda não tiver um script `start` configurado, você pode rodar diretamente com:
> ```bash
> npx ts-node src/index.ts
> ```
> ou compilar e depois executar:
> ```bash
> npx tsc
> node dist/index.js
> ```

## 🎮 Como usar

1. Ao iniciar o programa, escolha um dos carros disponíveis no menu inicial.
2. Navegue entre as categorias de peças: **estética** ou **performance**.
3. Selecione as peças desejadas para adicionar ao carro.
4. Repita o processo quantas vezes quiser, combinando diferentes peças.
5. Ao finalizar o tuning, veja o resumo completo: peças instaladas, ganho de potência e estatísticas finais do carro.

## 📁 Estrutura do projeto

```
typescript-tuning/
├── src/
│   ├── models/       # Classes/interfaces de Carro, Peça, etc.
│   ├── data/         # Dados pré-cadastrados de carros e peças
│   ├── menu/         # Lógica dos menus de interação no terminal
│   └── index.ts      # Ponto de entrada da aplicação
├── package.json
├── tsconfig.json
└── README.md
```

> ⚙️ Ajuste esta seção conforme a organização real das suas pastas e arquivos.

## 🎓 Contexto acadêmico

Projeto desenvolvido para a disciplina de **[nome da disciplina]**, do curso de **[nome do curso]**, na **[nome da instituição]**.

**Autor(a):** [Seu nome]

## 📄 Licença

Projeto acadêmico, sem fins comerciais.
