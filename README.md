# FitBot

## Descrição do Projeto

FitBot é um chatbot de treinamento físico desenvolvido para ajudar as pessoas a se exercitarem de maneira eficaz e segura. O FitBot é capaz de criar um cronograma de exercícios personalizado com base nas necessidades individuais do usuário. Ele pode perguntar sobre os dias em que o usuário pretende se exercitar, o IMC do usuário e se o usuário tem algum problema físico. Com base nessas informações, o FitBot cria um cronograma de exercícios personalizado. Além disso, o FitBot pode explicar cada exercício em detalhes, se o usuário desejar.

## Como Usar

Para usar o FitBot, siga os passos abaixo:
**Crie um ambiente virtual Python (venv)**: 
Navegue até o diretório do seu projeto e crie o ambiente virtual. Substitua `myenv` pelo nome que você deseja dar ao seu ambiente virtual:

```bash
python3 -m venv myenv
```

**Ative o ambiente virtual:** 
O comando para ativar o ambiente virtual depende do sistema operacional:

No Windows:
```bash
.\myenv\Scripts\activate
```
No Unix ou MacOS:
```bash
source myenv/bin/activate
```

***Instale as dependências necessárias:**
O FitBot requer algumas bibliotecas Python, que você pode instalar usando o gerenciador de pacotes pip. 
Abra o terminal e digite os seguintes comandos:

```bash
pip install tkinter
pip install ttkbootstrap
pip install google-generativeai
```

**Configure a chave da API do Google:** Você precisará de uma chave da API do Google para usar o modelo generativo da Google. Substitua GOOGLE_API_KEY no código pelo valor da sua chave da API.

**Execute o código:** Salve o código em um arquivo Python (por exemplo, fitbot.py) e execute-o a partir do terminal com o comando python fitbot.py. Isso abrirá a janela de chat do FitBot.

**Use o FitBot:** No campo de entrada na parte inferior da janela, você pode digitar suas respostas para as perguntas do FitBot e pressionar o botão ‘Enviar’ para enviar sua mensagem. As respostas do FitBot aparecerão na área de texto acima.
Contribuições
## Contribuições:
Para o projeto são bem-vindas. Sinta-se à vontade para abrir uma issue ou fazer um pull request.
