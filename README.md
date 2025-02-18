# 🗺️ PlacePicker - Encontre e Explore Lugares Incríveis!

O Place Picker é um aplicativo web intuitivo e fácil de usar, desenvolvido em React, que permite aos usuários criar e gerenciar suas listas personalizadas de lugares que desejam visitar ou já visitaram. Com funcionalidades como ordenação por proximidade (utilizando a API de geolocalização do navegador) e interface amigável, o Place Picker torna o planejamento de viagens e a recordação de lugares especiais uma experiência prazerosa.

## 📸 Capturas de Tela

![image](https://github.com/user-attachments/assets/d5633d16-3785-4596-8663-084dd265d9cf)
![image](https://github.com/user-attachments/assets/666bdf41-7f48-480d-b1c5-634ea3078e6c)
![image](https://github.com/user-attachments/assets/1f7001dc-80ef-4d70-a0aa-7189574d6042)


## 🚀 Tecnologias Utilizadas

**Frontend:**

*   React.js: [https://react.dev/](https://react.dev/)
*   Vite: [https://vitejs.dev/](https://vitejs.dev/)
*   CSS: [https://www.w3schools.com/css/](https://www.w3schools.com/css/)
*   JavaScript: [https://www.w3schools.com/js/](https://www.w3schools.com/js/) 
*   LocalStorage: [https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage](https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage)
*   React Router (se usado): [https://reactrouter.com/en/main](https://reactrouter.com/en/main)
*   gh-pages: [https://github.com/tschaub/gh-pages](https://github.com/tschaub/gh-pages)
*   vite-plugin-pages: [https://github.com/vitejs/vite/tree/main/packages/plugin-pages](https://github.com/vitejs/vite/tree/main/packages/plugin-pages)

**Backend (se aplicável):**

*   Node.js

## ⚙️ Funcionalidades

✔️ **Adicionar locais:** Clique em um local na lista de locais disponíveis para adicioná-lo à sua lista de desejos.

✔️ **Remover locais:** Clique em um local na sua lista de desejos para removê-lo.

✔️ **Ordenar por proximidade:** Os locais são automaticamente ordenados por proximidade com base na sua localização (requer permissão do usuário para acesso à geolocalização).

✔️ **Persistência de dados:** Seus lugares favoritos são salvos e podem ser acessados em qualquer dispositivo (via LocalStorage ou Backend, especifique qual).

## 🔧 Como Executar o Projeto

**Frontend:**

1.  Clone este repositório: `git clone https://github.com/PedroJCAlmeida/portfolio-place-picker`
2.  Acesse o diretório do projeto: `cd placePickerReact`
3.  Instale as dependências: `npm install`
4.  Inicie o projeto: `npm run dev`

**Backend (se aplicável):**

1.  Acesse o diretório do backend.
2.  Instale as dependências: `npm install`
3.  Inicie o servidor: `npm run start` (ou o comando específico para o seu backend).

## 📂 Estrutura do Projeto

/backend
│── /data        # Lista de Lugares e Listas Seleciondas Utilizador 
│── /images      # Imagens
│── /app.js      # Lista  

/src  
│── /assets      # Logo
│── /components  # Componentes reutilizáveis(AvailablePlaces, DeleteConfirmation, Error, Modal, Places, ProgressBar)
│── /loc.js      # Funções auxiliares (Calcular distancia e ordernar por distância conforme geolocalização )
│── /http.js    # Funções auxiliares (Funções de requisição HTTP (POST, DELETE, GET e PUT)
│── App.jsx     # Componente principal
│── main.jsx    # Ponto de entrada do React
│── index.html  # Arquivo HTML principal
│── vite.config.js # Configuração do Vite
│── package.json  # Arquivo de configuração do projeto


## 📬 Contacto

Caso tenha alguma dúvida ou sugestão, entre em contato:

📧 <pedrojoaocarvalhoalmeida@gmail.com>

🔗 LinkedIn: [http://linkedin.com/in/pedro-j-c-almeida](http://linkedin.com/in/pedro-j-c-almeida)

## Contribua!

Contribuições são sempre bem-vindas! Para contribuir, siga estas etapas:

1.  Fork o repositório.
2.  Crie um branch para sua feature (`git checkout -b feature/nome-da-feature`).
3.  Faça commit das suas mudanças (`git commit -am 'Adiciona nova feature'`).
4.  Faça push para o branch (`git push origin feature/nome-da-feature`).
5.  Abra um Pull Request.

## Experimente agora!

Clique aqui para acessar o aplicativo: [https://pedrojcalmeida.github.io/portfolio-place-picker/](https://pedrojcalmeida.github.io/portfolio-place-picker/)
