- Construindo uma imagem no docker

    Ao personalizar o arquivo "DockerFile", vamos acessar a pasta com onde criou o arquivo.

    

    Na barra de informações onde esta o caminho , você colocara, a seguinte instrução CMD. Ele abrira o nosso prompt de comando do windowns.
    
    ![docker2](https://user-images.githubusercontent.com/105161714/235471011-f0e78ccb-2a39-4ece-9f18-88f98d88ffa0.PNG)

    Feito o seguinte o primeiro comando para construir a nossa build é o seguinte.
    
    
    ![docker3](https://user-images.githubusercontent.com/105161714/235471181-d62cbd9a-0706-49e6-b965-efaba916c343.PNG)

    - OBS: Sempre que criarmos uma imagem temos que passar o nome da imagem, e uma tag.

    - Explicação do comando abaixo: 
        - docker => Usamos sempre que execultarmos algo relacionando ao Doker.
        - build => Quando queremos execultar a construção de uma imagem.
        - -t => seria para abranger o nome de nossa tag.
        - NomeImagem => Seria o nome da imagem ao qual esta subindo.
        - TagDaImagem => Uma breve descrição sobre a imagem como exemplo se ela e uma versão latest.
        - . => seria aonde ele encontria o nosso arquivo. Lembrando que . se refere se estiver na mesma pasta, se caso não estiver adicione o caminho da pasta on de esta o arquivo DockerFile.

       - docker build -t "nomeDaImagem:TagDaImagem" .


    - A final da instalação termos o seguinte resultado:
    
    ![docker1](https://user-images.githubusercontent.com/105161714/235471297-ec0915a6-2515-40a5-8a87-998b2f7d2756.PNG)
    
    - E teremos a nossa imagem no docker também !
    
    - ![docker4](https://user-images.githubusercontent.com/105161714/235471704-7e19c019-5043-4214-b9e0-2d4de94afe13.PNG)

