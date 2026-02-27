# 📱 Mobile Todo App

Um aplicativo de lista de tarefas simples e elegante desenvolvido com React Native e Expo, desenvolvido durante o curso **Fundamentos de React Native** da **Percípio**.

## 🚀 Funcionalidades

- ✅ Adicionar novas tarefas
- ✅ Marcar tarefas como concluídas
- ✅ Excluir tarefas
- ✅ Contador de tarefas totais e concluídas
- ✅ Interface moderna e responsiva
- ✅ Desenvolvido em TypeScript

## 📋 Pré-requisitos

- Node.js (v14 ou superior)
- npm ou yarn
- Expo CLI
- Expo Go app (para testar em dispositivo físico)

## 🔧 Instalação

1. Clone o repositório:
```bash
git clone <url-do-repositorio>
cd mobile-todo-app
```

2. Instale as dependências:
```bash
npm install
```

## ▶️ Executando o Projeto

### Método 1: Desenvolvimento Normal

```bash
npx expo start
```

Após iniciar o servidor de desenvolvimento:

- Pressione `a` para abrir no emulador Android
- Pressione `i` para abrir no simulador iOS
- Escaneie o QR code com o app Expo Go para testar em dispositivo físico

## 📱 Como Usar

1. **Adicionar Tarefa**: Digite o texto da tarefa no campo de entrada e pressione "Adicionar"
2. **Marcar como Concluída**: Toque na tarefa para alternar entre concluída/não concluída
3. **Excluir Tarefa**: Toque no botão "×" vermelho ao lado da tarefa

## 🛠️ Tecnologias Utilizadas

- [React Native](https://reactnative.dev/)
- [Expo](https://expo.dev/)
- [TypeScript](https://www.typescriptlang.org/)

## 📁 Estrutura do Projeto

```
mobile-todo-app/
├── App.tsx                 # Componente principal do aplicativo
├── app.json               # Configuração do Expo
├── package.json           # Dependências do projeto
├── tsconfig.json          # Configuração do TypeScript
└── assets/               # Ícones e imagens
    ├── icon.png
    ├── splash-icon.png
    └── ...
```

## 🎨 Design

O aplicativo apresenta:
- Cabeçalho com cor de destaque (#2c3e50)
- Cards modernos para cada tarefa
- Animações visuais ao marcar tarefas
- Design responsivo e minimalista
- Interface intuitiva e amigável

---

**Nota**: Este é um projeto educacional criado para demonstrar o desenvolvimento de aplicativos móveis com React Native e Expo.
