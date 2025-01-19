# Azure Inteligência Artificial(IA) - Liguage Studio: Configuração do Resource e testes
Objetivo criar a configuração e realizar de usabilidade.

Dê aos seus aplicativos a capacidade de ouvir, entender e até mesmo falar com seus clientes com recursos como fala para texto e texto para fala.

### Ferramentas utilizadas:
- Portal Azure: https://portal.azure.com
- Portal Laguage Studio: laguage.cognitive.azure.com
- Portal Speech: https://speech.microsoft.com/portal

### Pontos Importantes:
- Caso esteja realizando apenas um prática de estudo, no final excluir tudo que foi construído nesse laboratório. Desta forma, minimiza o risco de ser cobrado algum valor. Lembre-se você está em um ambiente real de produção.
- Documentação:
    + https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/06-text-analysis.html
    + https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/09-speech.html

### Resumo (Passo-a-passo):

- Entrar no ambiente Azure

### Detalhamento (Passo-a-passo):

01 - Após logar no portal Azure. Iremos criar um ``` Create a resource  ```, selecionar ``` AI + Machine Learning  ``` e escolher a opção ``` Language service  ```.
![image](https://github.com/user-attachments/assets/a4ed19b3-b179-4cd1-8589-308ab6917407)

02 - Após clicar no botão para clicar no botão ``` Create  ``` da opção de serviço: ``` Language service  ```. Apresentara uma nova tela com as opções de serviço e caso queira adicionar outros também permitirá. No nosso caso, mantém as opções padrão de serviço, pois é o suficiente. Então clicamos no botão ``` Continue tp create your resource  ```.
![image](https://github.com/user-attachments/assets/dd8cb228-9a2a-477f-8bea-53d2dfe229b5)

03 - Iniciar a configuração criando o repositório onde será salvo nosso projeto, modelo, laboratório. Fique a vontade para chamar do melhor padrão para sua necessidade.
   * Subscription: é a conta que você está logado. É como se você a sua empresa. Repositótorio geral de tudo que é criado, a Pasta principal. Já vem preenchido de padrão, Esse padrão é criado automaticamente quando realiza o cadastro. Mas pode ser criado outras opções.
   * Resource group: é uma sub-repositório do "Subscription".
Imagina uma gaveteiro onde o gaveteiro inteiro é Subscriptiom e uma gaveta desse gaveteiro é o Resource group.
   * Region: basicamente, quer dizer em qual servidor da Microsoft você quer salvar(Brasil, USA etc). Acredito que também determina a moeda que será cobrado por utilizar esse serviço.
   * Name: nome do seu projeto, modelo (Deve ser único)
   * Pricing tier: O método de cobrança. Nesse nosso caso vamos selecionar a opção Free por 3 dias.
   * Check box: "By checking this box I certify that I have reviewed and acknowledge the terms in the Responsible AI Notice". Deve marcar, pois precisa aceitar os termos e condições.
   ![image](https://github.com/user-attachments/assets/48731618-f04f-47d5-ba3c-a3186f12b07b)

04 - Demais Abas: vamos manter o padrão, pois estamos realizando uma configuração basica e iremos excluir esse modelo no final. Então, click no botão ``` Review + create ``` para validar as configurações e depois click novamente no botão ``` Create ``` 
   * Networking: configuração de privacidade do seu modelo(Publico/Privado)
   * Identity: usar o controle de acesso
   * Tags: muito usado para criar filtros. Por exemplo: Quero fazer rateio para lançamento de custo por Departamento, então, cria as tags por departamento. Conforme sua necessidade.
   ![image](https://github.com/user-attachments/assets/1b88a9bd-dc97-4ee0-ac4f-31d3b765a92c)


