# BAT PASS APP

Aplicativo mobile para geração de senhas seguras, inspirado no universo do Batman. Desenvolvido em React Native com Expo.

## Funcionalidades

- Geração de senhas aleatórias e seguras.
- Interface customizada com tema escuro e elementos visuais do Batman.
- Botão para copiar a senha gerada para a área de transferência.
- Layout responsivo e adaptado para dispositivos móveis.

## Estrutura do Projeto

```
bat-pass-app/
├── App.tsx                # Ponto de entrada do app
├── index.ts               # Registro do componente raiz
├── app.json               # Configurações do Expo
├── package.json           # Dependências e scripts
├── tsconfig.json          # Configuração do TypeScript
├── declarations.d.ts      # Tipos para importação de imagens
├── assets/                # Imagens e ícones do app
├── src/
│   ├── components/        # Componentes reutilizáveis
│   │   ├── BatButton/     # Botão de gerar/copy senha
│   │   ├── BatLogo/       # Logo e título do app
│   │   ├── BatTextInput/  # Campo de exibição da senha
│   │   └── Menu/          # (Em desenvolvimento)
│   ├── screens/
│   │   └── Home/          # Tela principal do app
│   └── services/
│       └── passwordService.ts # Função de geração de senha
```

## Principais Componentes

- [`BatLogo`](bat-pass-app/src/components/BatLogo/BatLogo.tsx): Exibe o título e o logo do app.
- [`BatButton`](bat-pass-app/src/components/BatButton/BatButton.tsx): Botões para gerar e copiar senha, além do campo de exibição.
- [`BatTextInput`](bat-pass-app/src/components/BatTextInput/BatTextInput.tsx): Campo de texto somente leitura para mostrar a senha gerada.
- [`passwordService`](bat-pass-app/src/services/passwordService.ts): Função responsável por gerar a senha aleatória.

## Como rodar o projeto

1. Instale as dependências:
   ```sh
   npm install
   ```
2. Inicie o projeto com o Expo:
   ```sh
   npm start
   ```
3. Use o aplicativo Expo Go no seu dispositivo ou um emulador para visualizar o app.

## Dependências principais

- [React Native](https://reactnative.dev/)
- [Expo](https://expo.dev/)
- [expo-clipboard](https://docs.expo.dev/versions/latest/sdk/clipboard/)

## Screenshots

![Logo do App](bat-pass-app/assets/bat-logo.png)

## Licença

Este projeto é apenas para fins educacionais.

---
