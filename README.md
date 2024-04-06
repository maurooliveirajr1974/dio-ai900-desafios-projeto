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
