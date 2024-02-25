# Análise de sentimentos com Language Studio no Azure AI👾

### Olá pessoal! Irei fazer um breve resumo de como criar uma IA para análise de textos e conversão de fala em texto. Espero que este material ajude vocês e deixe mais claro o caminho a se seguir para a criação da IA.

Antes de tudo, gostaria de falar meu aprendizado durante o conteúdo. A criação da IA é bem tranquila, os testes são bem legais e interessantes, nos mostrando de diversas maneiras de que forma a IA nos ajuda no dia a dia e como ela esta inserida no nosso dia a dia sem nem mesmo percebermos. A análise é rápida e seus resultados pode se dizer "precisos", nos mostrando por exemplo o resultado da análise de sentimentos de um texto de insatisfação(ou não) com um serviço. **Agora bora para os resumos!😉**

## Análise de sentimento com Azure Language🤖
### 1️⃣ Crie um novo recurso no azure, clicando em **+ criar um recurso**

![criar recurso](https://github.com/R-JoiceAraujo/AI-Language/blob/main/inputs/criar-recurso-de-texto.png?raw=true)

▪Clique em **Continuar a criação do seu recurso**

### 2️⃣ Na página criar idioma, preencha as seguintes informações:
![criar idioma](https://github.com/R-JoiceAraujo/AI-Language/blob/main/inputs/criar-idioma.png?raw=true)

* Assinatura : sua assinatura do Azure .
* Grupo de recursos : Selecione ou crie um grupo de recursos com um nome de sua escolha
* Região : Para custos mais baixos,selecione Leste dos EUA.
* Nome : Insira um nome de sua escolha .
* Nível de preços : Selecione o plano Free FO
* Ao marcar esta caixa, confirmo que li e compreendi todos os termos abaixo : Selecionado ✅.
**Examinar + Criar**,  quando terminar de examinar clique em **Criar** para criar seu serviço e aguarde a criação⏳.


### 3️⃣Em outra guia do navegador, abra o [Language Studio](https://language.cognitive.azure.com/?azure-portal=true).

![Recurso Language](https://github.com/R-JoiceAraujo/AI-Language/blob/main/inputs/selecionar-recurso-language.png?raw=true)

* Faça login com sua conta do Azure que está localizado o serviço que acabou de criar .
* Em Seguida, clique em **Select a resource** e coloque as seguintes configurações:
▪ Diretório do Azure : diretório padrão, o diretório que você está usando;

▪ Assinatura do Azure : selecione a assinatura que você está usando;

▪ Tipo de recurso : Idioma;

▪ Nome do recurso : selecione o recurso de serviço de idioma que você acabou de criar na plataforma da **Azure**;

▪ **Clique em Finalizar .**

### 4️⃣ Na página inicial do Language Studio, selecione **Classificar texto** e em seguida selecione a atividade **Analisar sentimentos e extrair opiniões** .

![pagina inicial](https://github.com/R-JoiceAraujo/AI-Language/blob/main/inputs/pagina-inicial-classifica%C3%A7%C3%A3o-de-texto.png?raw=true)

### 5️⃣ A Aplicação será aberta conforme a imagem a baixo :
![analise de sentimento](https://github.com/R-JoiceAraujo/AI-Language/blob/main/inputs/analisedesentimento.png?raw=true)

* Selecione o idioma de sua escolha;

* Verifique se seu recurso está aparecendo;

* Digite a frase que deseja realizar o teste ou faça upload da mesma em um bloco de notas;

* Marque a opção de aviso; 

* Clique em iniciar .

### 6️⃣ Resultado da Análise de sentimento:
![resultado da análise](https://github.com/R-JoiceAraujo/AI-Language/blob/main/inputs/resultado-analisedesentimento.png?raw=true)

### 

## Estudio de fala
### 1️⃣ Crie um novo recurso no [Speech Studio](https://speech.microsoft.com/portal), com as seguintes instruções:

* Faça login com sua conta Azure;

* Selecione **Configurações⚙** e depois clique em **Crie um recurso**. Configure-o com as seguintes configurações:

![criar recurso de fala](https://github.com/R-JoiceAraujo/AI-Language/blob/main/inputs/criarumrecursodefala.png?raw=true)

▪ Nome do novo recurso : Insira um nome exclusivo.

▪ Assinatura : sua assinatura do Azure.

▪ Região : Selecione uma região suportada .

▪ Nível de preços : FO gratuito (se disponível, caso contrário, selecione Standard S0).

▪  Grupo de recursos : selecione ou crie um grupo de recursos com um nome exclusivo .


* Selecione Criar recurso. Aguarde até que o recurso seja criado e selecione **Usar recurso**. Volte a página inicial.

### Explore a fala em texto no Speech Studio

#### 1️⃣ Selecione https://aka.ms/mslearn-speech-files para baixar o speech.zip. Abra a sua pasta e coloque para extrair speech.zip.

#### 2️⃣ Na página Introdução à fala, **Conversão de fala em texto**, localize conversão de Fala em tempo real para texto . Selecione **Experimente a fala em tempo real para texto** . Como mostrado na imagem.
![conversão de fala em texto](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/media/recognize-synthesize-speech/try-out-speech-to-text.png)

#### 3️⃣Em Escolher arquivos de áudio , selecione **Procurar arquivos** e navegue até a pasta onde você salvou o arquivo. **Use o aúdio que desejar**.

![página de fala](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/media/recognize-synthesize-speech/browse-files-speech.png)

#### 4️⃣ O serviço Speech transcreve e exibe o texto em tempo real. Se você tiver áudio em seu computador, poderá ouvir a gravação enquanto o texto é transcrito.

### 5️⃣Revise a saída, que deve ter reconhecido e transcrito com êxito o áudio em texto





#### Está pronta sua IA de análise de sentimento com Language Studio e estudio de fala com Speech Studio,espero que tenham gostado do conteúdo e aqui em baixo estará o material de apoio.

* **Sites usados:**

[Language Studio](https://language.cognitive.azure.com/home)

[Speech Studio](https://speech.microsoft.com/portal)

[Azure](https://portal.azure.com/#home)

## BOM ESTUDO A TODOS🙂
