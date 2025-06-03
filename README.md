## 🌤️ Projeto: Consulta de Clima com UiPath

Este projeto em UiPath realiza a consulta da previsão do tempo utilizando a API do OpenWeatherMap. Ele lê o nome de uma cidade, faz uma requisição HTTP para a API e exibe informações como temperatura atual e descrição do clima em uma mensagem pop-up.

🔗 API utilizada: [OpenWeatherMap](https://openweathermap.org/api)

### 🧪 Tecnologias e Recursos
- UiPath Studio
- Atividades WebAPI (HTTP Request)
- Manipulação de JSON
- OpenWeatherMap API

### 📌 Objetivos do projeto
- Aprender integração com APIs REST
- Trabalhar com JSON em automações
- Desenvolver automações práticas e informativas

---

## 🚀 Como usar

1. Clone ou baixe este repositório.  
2. Abra o arquivo no UiPath Studio.  
3. Execute o fluxo e insira o nome da cidade quando solicitado.  
4. A automação fará uma requisição à API do OpenWeatherMap.  
5. Uma mensagem pop-up exibirá a temperatura atual, descrição do clima e outras informações relevantes.

---

## 📦 Estrutura do projeto

- `Main.xaml` — fluxo principal que realiza a consulta, manipula o JSON e exibe as informações.  
- `README.md` — documentação do projeto.  

---

## 🛠️ Requisitos

- UiPath Studio versão 2020.10 ou superior  
- Conexão com internet para acessar a API  
- **Chave válida da API do OpenWeatherMap**  

> ⚠️ **Importante:** No fluxo do UiPath, coloque a chave de API no campo `appid` dentro da atividade **HTTP Request** para garantir o funcionamento correto da consulta.
> 
