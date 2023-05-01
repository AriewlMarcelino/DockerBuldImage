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

- Subindo o conteiner no docker

    realizando toda construção da imagem de maneria personalizada, no nosso caso acima, temos que subir o nosso container com a imagem que construimos e como podemos fazer isso:


    executamos o seguinte comando abaixo:
    ![docker5](https://user-images.githubusercontent.com/105161714/235479342-41e2a8e8-0226-45e7-b6fb-70bed90279ff.PNG)
    
    feito o seguinte podemoremo ver o terminal emitir as seguinte mensagem
    ![docker6](https://user-images.githubusercontent.com/105161714/235479743-f12286e5-f839-447d-b595-27a026d9aa56.PNG)
    
    E no docker vamos ver o seguinte continer com o nome que voce der, no meu caso dei um nome de exemplo como <br>meuBuildNginx<br>;
    ![docker7](https://user-images.githubusercontent.com/105161714/235480547-1a28274f-48e6-4169-bcf9-89cb5382d746.PNG)
    
    Dai em frete você pode estar realizando dentro do docker a execução na web para verificar se esta funcionando, na parte da web, como exempplo abaixo:
    ![docker8](https://user-images.githubusercontent.com/105161714/235483873-d0c8c415-0fb8-4b83-a61f-79c4bd8a6f65.PNG)


    


