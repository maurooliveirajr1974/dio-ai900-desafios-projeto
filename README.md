
# Project Title

A brief description of what this project does and who it's for

# dio-ai900-desafios-projeto
DIO - Desafios de Projeto do Microsoft Azure AI-900 - AI Fundamentals

### Desafio Módulo - 02 - Trabalhando com Machine Learning na Prática no Azure ML

**Branch: desafio-modulo-02**

Para realizar este desafio eu segui a página do mesmo desafio que existe no Microsoft Learn:

https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/01-machine-learning.html

1) Criei um novo recurso do Azure Machine Learning com chamado "desafio-ai900-lab01-ml" com asconfigurações sugeridas.
2) Acessei o Machine Learning Studio
3) Criei um novo trabalho de ML automatizado chamado "mslearn-bike-automl" com as configurações sugeridas
4) Implantei modelo treinado chamado "mslearn-bike-rental"
5) Testado o endpoint "predict-rentals" 

### Desafio Módulo - 03 - Reconhecimento Facial e transformação de imagens em Dados no Azure ML

**Branch: desafio-modulo-03**

Para realizar este desafio eu segui as instruções da página do desafio no Microsoft Learn:

https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/03-image-analysis.html

1) Criei um novo recurso do Azure Cognitive Services  chamado "desafio-ai900-visao" .

2) Acessei o portal do Vision Studio

3) Acessei o link https://aka.ms/mslearn-images-for-analysis e fiz o download do arquivo image-analysis.zip

4) Escolhi a imagem **store-camera-4.jpg** porque ela tem 3 pessoas (dois adultos e uma criança) que formam uma família dentro de uma mercearia. Queria ver se o algoritmo conseguiria detectar essas pessoas e também os objetos (que os produtos do supermercado que possuem vários formatos e cores).

5) Subi a foto no analizador de imagens do Vision na opção **Add captions to images**.
Resultado: o algoritmo detectou apenas "A man and woman in a grocery store".

6) Salvei o resultado da detecção no arquivo **resultado-add-captions-to-images.json**.

7) Em seguida escolhi a opção **Dense captioning** e subi a mesma foto **store-camera-4.jpg** e pedi para fazer a deteção da imagem. 
Resultado: O algoritmo detectou muito mais elementos na foto (todas as 3 peossas e vários objetos e produtos da mercearia, como eu esperava):
- A man and woman in a grocery store
- A man holding a bunch of peanuts
- A woman holding a phone
- A girl in a purple hat
- A man and woman standing in a grocery store
- A person holding a phone in front of a shelf of avocados
- A man with long hair smiling
- A hand holding a bunch of garlic
- A shelf with bottles of food
- A close-up of a woman holding a phone

8) Salvei o resultado da detecção nos arquivos **resultado-add-captions-to-images.json** e **store-camera-4-com-as-deteccoes-vision-estudio.png**.

### Desafio Módulo - 04 - Análise de Sentimentos com Language Studio no Azure AI

**Branch: desafio-modulo-04**

Para realizar este desafio eu segui as instruções da página do desafio no Microsoft Learn:

https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/06-text-analysis.html

1) Criei um novo recurso do Azure Cognitive Services  chamado ***desafio-ai900-analise-sentimentos***.

2) Acessei o portal do *Language Studio* no link https://language.cognitive.azure.com

3) Criei um novo recurso de linguagem

4) Selecionei a opção **Analyze sentiment and opinions**. Escolhi o idiona Português (Brasil)

5) Digitei o a frase: *"Eu estou muito animado para finalizar o Bootcamp da DIO e conquistar a minha Certificação AI-900 Azure AI Fundanentals!"* e executei a Análise.

6) O resultado foi:
**Positive**
Confidence: **95.00%**

**95.00% POSITIVE** 4.00% NEUTRAL 1.00% NEGATIVE

7) Achei muito interessante essa análise de sentimentos do texto. Muitas possibilidades!! Pensei em algo voltado para análise da Pirâmide de Maslow (Hierarquia das Necessidades):

https://pt.wikipedia.org/wiki/Hierarquia_de_necessidades_de_Maslow

### Desafio Módulo - 05 - Análise de Sentimentos com Language Studio no Azure AI

**Branch: desafio-modulo-05**

Para realizar este desafio eu segui as instruções da página do desafio no Microsoft Learn:

https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/11-ai-search.html

1) Criei um novo recurso Azure AI Search.

2) Criei um novo recurso Azure AI Services.

3) Criei um novo Contâiner.

4) Baixei e descompactei o arquivo reviews.zip.   Dentro da branch eles estão em */desafio-modulo-05/reviews*

5) Carreguei os arquivos no Contâiner criado para o desafio.

6) Importei os dados para o meu Azure AI Search.

7) Acessei o coffee Indexer e pesquisei pela "love". Ele me retornou em formato JSON os resultados das avaliações dos clientes "adoram meu café e o serviço prestado". 
Ex:   *"content": "\n\n\nReview: My favorite part about going to Fourth Coffee is the atmosphere. **I love** the warm lights and plants. It’s a **great place to go get a cup of coffee while working on your next business idea or with friends at school.** It’s also right next to the University hub, which makes it so easy to access for students. It just gets so busy on the weekends! I wish it was not so crowded. Since they started **offering amazing breakfast sandwiches**, I wouldn’t try to go get a coffee Saturday morning.  \nDate: September 1, 2018\nLocation: Los Angeles, California \nimage1.png\n\n\n\nimage2.png\n\n\n\n"* 

Esse recurso do Azure AI Search é fantástico! Fiquei imaginando se eu tivesse um negócio e tivesse que analisar todas as avaliações dos meus clientes no Google, por exemplo e ter que pesquisar todos os posts desses mesmos clientes nas minhas redes sociais. Este recurso seria e extrema importância para a apuração dos dados de uma forma rápida e inteligente.

8) O arquivo JSON com o resultado da pesquisa está na branch em */desafio-modulo-05/results*

### Desafio Módulo - 05 - Parte 2 - Explorando os Recursos de IA Generativa com Copilot e OpenAI

**Branch: desafio-modulo-05-parte-02**

Para realizar este desafio eu segui as instruções da página do desafio no Microsoft Learn:

https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/10-document-intelligence.html

1) Criei um novo recurso Azure AI - Document Intelligence Studio.

2) Acessei o link https://aka.ms/mslearn-receipt e fiz o download de uma amostra de documento (recibo de compras) para análise (receipt.jpg). Dentro da branch ele está em */desafio-modulo-05-parte-02/inputs*

3) Subi a imagem para o recurso do Document Intelligence Studio que criei para esse desafio.

4) Após executar a análise do documento o algoritmo conseguiu detectar todos os elementos do recibo com uma acurácia de até **99,50%**:
Todos os prints de tela com as evidências após o teste e também os arquivos JSON e Python gerados pelo Document Intelligence Studio estão na branch em */desafio-modulo-05-parte-02/output*
