# ServerRestTesting
Repository dedicated to a ServerRest Automated Testing project


<div align="center">
  


<img src="https://media.giphy.com/media/JszKEk8vNGtCXehi7w/giphy.gif" >
</div>

## Introdução:

Esse Readme é referente ao projeto para aperfeiçoamento de conhecimento em automação de testes em API's. Neste repositório você encontrará os resultados dos trabalhos realizados durante esse período e é possível encontrar os seguintes arquivos: `Plano de Testes - ServeRest API` , `Relatório de Testes - ServeRest API` e a pasta `Testes` que tem os arquivos dos testes realizados.

> Status: ✔️ Finalizado

## Pré requisitos:

Para ter acesso aos arquivos deste repositório você precisará:

> - [Github](https://github.com/)
> - [Git](https://git-scm.com/downloads)
> - [NodeJS](https://nodejs.org/en/download/)
> - Newman
> - Navegador Web 

## Acesso:
Há duas formas de acesar o material desse repositório, por meio do download e do clone do github. 
- Para acessar por download, você deve:

1️⃣ Acessar o repositório no [GitHub](https://github.com/analuizanasc/ServerRestTesting.git)

2️⃣ Clicar no botão verde `Code` (canto superior direito)

3️⃣ Clicar em `Download Zip`

- Se escolher acessar por meio do clone, você deve:

1️⃣ Acessar o [repositório
](https://github.com/analuizanasc/ServerRestTesting.git) no GitHub

2️⃣ Clicar no botão verde `Code` (canto superior direito)

3️⃣ Copiar o [link HTTPS](https://github.com/analuizanasc/ServerRestTesting.git)

4️⃣ Após isso crie uma pasta em seu computador;

5️⃣ Em qualquer lugar da tela, clique com o botão direito no mouse e selecione Git Bash Here;

6️⃣ Digite `git clone` e o link que você copiou e pressione `enter` no teclado.

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)


# 📄 `Plano de Testes - ServeRest API`: 

Este é o arquivo do Plano de testes elaborado para a ServeRest API. Um plano de teste deve ser utilizado como guia para a execução e controle das atividades de teste, essencial para ofertar um produto de qualidade ao cliente, evitando o mínimo de problemas na fase de produção. Neste documento é possível encontrar as seguintes informações:

- Introdução	
- Objetivos	
- Escopo	
- Mapa Mental Da Api
- Estratégia De Teste	
- Recursos Humanos
- Prioridades	
- Suíte De Teste	
- Observações Complementares	

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

# 📄 `Relatório de Testes - ServeRest API`: 
Este é o arquivo do Relatório de testes da ServeRest API. O relatório sintetiza as informações obtidas durante a fase de testes e as analisa. Neste documento é possível encontrar as seguintes informações:

- Introdução
- Escopo
- Resumo Dos Resultados Dos Testes
- Cobertura De Teste
- Relatório De Incidente
- Análise Dos Resultados
- Sugestões De Melhorias
- Referência Bibliográfica

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

# 📁 Pasta `Testes`:
Nesta pasta está os arquivos dos testes executados na ferramenta Postman e o dois arquivos do Dashboard do Newman, um com uma iteração e outro com 4 iterações. O Newman é uma ferramenta que permite executar os testes do Postamn por linha de comando e roda sobre o NodeJs. 

É possível ter acesso ao Dashboard do Newman de duas formas:

1️⃣ Abrir o arquivo HTML no seu navegador web 

2️⃣ Seguir os passos abaixo:

- Para a instalar o NodeJS, você pode seguir o tutorial abaixo:

[Clique Aqui - Tutorial de instalação do NodeJS](https://www.youtube.com/watch?v=-cLzUD0TQY0&ab_channel=M%C3%A3onoC%C3%B3digo)

- Para a instalar o Newman, digite no prompt de comando: 

1️⃣ `npm install -g newman`

2️⃣ pressione `enter`

Em seguida, digite:

1️⃣ `npm install -g newman-reporter-html`

2️⃣ pressione `enter`

3️⃣ `npm install -g newman-reporter-html`

4️⃣ pressione `enter`

- Para gerar o Dashboard é necessário rodar os arquivos json que estão dentro dessa pasta. Assim, no prompt de comando, digite:

1️⃣ `cd CaminhoDaPasta`

2️⃣ pressione `enter`

3️⃣ `newman run SuaColecao.json -e SeuAmbiente.json -n 2 -r htmlextra`

4️⃣ pressione `enter`

⚠️ Atenção! 
- CaminhoDaPasta é o caminho onde a pasta se encontra no seu computador. Exemplo: C:\Users\Ana\Testes
- SuaColecao.json é o nome do arquivo da coleção do postman
- SeuAmbiente.json é o nome do arquivo do ambiente do postman

Após esses passos será criado uma pasta chamada `Newman` no mesmo local que você indicou e dentro dela se encontra o arquivo HTML que você pode abrir no seu navegador web.

### 🖊️ Se liga!

Caso queira, você poderá importar os arquivos json para o Postman da seguinte maneira: 

1️⃣ No postman, clique em `file` e em seguida `import` ou pressione `CTRL + O`

2️⃣ Selecione os arquivos json

Para rodar o testes da coleção:  

1️⃣ Selcione a coleção

2️⃣ Clique em `Run`

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

