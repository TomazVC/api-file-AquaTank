# AquaTank Sensor Data API

Bem-vindo ao repositório da API responsável pelos dados dos sensores do AquaTank. Esta API é projetada para fornecer informações sobre os sensores do AquaTank, possibilitando a monitoração e análise dos dados coletados.

## Pré-requisitos

Antes de começar, certifique-se de ter o Node.js instalado em seu sistema. Caso ainda não tenha, você pode baixá-lo [aqui]([link](https://nodejs.org/en)).

## Configuração

1. Baixe a pasta do repositório.
2. Abra a pasta no Visual Studio Code (VSCode).
3. No VSCode, abra o terminal.
4. Execute o comando `npm install` para instalar as dependências necessárias.

## Executando a API

Após a conclusão da instalação das dependências, siga estes passos para colocar a API no ar:

1. No terminal do VSCode, execute o comando `node script js`.
2. A API estará agora disponível para acesso em [http://localhost:3000](http://localhost:3000).

Vale lembrar, para acessar os dados de um sensor específico, basta digitar as seguintes iniciais seguidas de uma barra ("/") no fim do "http", como mostrado no exemplo:
* Exemplo para acessar os dados de temperatura: http://localhost:3000/t
* t: Temperatura
* h: Umidade
* l: Luminosidade
* c: CO2
* v: TVOC
* b: Boia

O gráfico de O2 é mostrado diretamente na sessão de dashboard do site. Um código executa a conversão dos valores de CO2 que entram e retornam o valor correspondente em O2.

---

Agora você pode começar a utilizar a API para obter e analisar os dados dos sensores do AquaTank. Divirta-se!
