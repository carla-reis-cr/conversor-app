# Conversor de Moedas

**Conversor de Moedas** é um app desenvolvido em **React Native** (com Expo), que permite converter valores entre diferentes moedas em tempo real. O projeto foi inspirado em um tutorial do YouTube (DevClub | Programação) ([link](https://www.youtube.com/watch?v=a8YvzTXft9c&ab_channel=DevClub%7CPrograma%C3%A7%C3%A3o)).

---

## Tecnologias Utilizadas

- **React Native** com **Expo**
- Hooks (useState, useEffect)
- Consumo de API de câmbio num endpoint público [ExchangeRate-API](https://www.exchangerate-api.com)
- Componentes reutilizáveis (botão, input, seletor de moeda)

---

## Funcionalidades

- 👍 Digite o valor a ser convertido.
- 🌍 Selecione a moeda de origem e destino.
- 🔄 Exibição do valor convertido conforme as taxas obtidas em tempo real.
- ⏳ Indicadores de carregamento enquanto os dados da API são buscados.
- Tratamento de erros em caso de falha na requisição.

---

## Prévia do App

[Clique aqui para abrir no **Expo Snack**](https://snack.expo.dev/@creis/github.com-carla-reis-cr-conversor-app)

![Preview do App](./assets/preview.gif)

---

## Como Rodar Localmente

1. Clone o repositório:
   ```bash
   git clone https://github.com/creis/cr-conversor-app.git
   cd cr-conversor-app
   ```
2. Instale as dependências:

   ```bash
   yarn install
   # ou npm install
   ```

3. Execute com o Expo:

   ```bash
   npx expo start
   ```

4. Escolha rodar no simulador Android/iOS ou escaneie o QR com o app Expo Go no seu celular.

## Sobre o Tutorial

Este projeto foi desenvolvido guiado por um tutorial do canal DevClub | Programação, que ensina como:

- Criar um app em React Native com Expo.
- Utilizar hooks como useState e useEffect.
- Consumir APIs e lidar com estados como loading e erro.
- Construir uma interface simples e intuitiva.

Mais informações e conteudo dos conceitos no [Notion](https://devclub.notion.site/85-Desenvolvendo-seu-primeiro-App-Mobile-1df3f245f933804997c1c08395506fc2)

## Próximos Passos (O que pode ser incrementado)

- Adicionar múltiplas taxas e gráficos de histórico de câmbio.
- Salvar conversões favoritas / históricos.
- Estilização mais elaborada (themes, dark mode).
- Publicar nas lojas: App Store ou Google Play (via Expo build ou EAS).

## Licença

Feito com ❤️ por Carla Reis (creis).
Licença MIT – sinta-se à vontade para forkar, customizar e aprender!
