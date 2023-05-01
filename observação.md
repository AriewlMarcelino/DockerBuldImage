- Construindo uma imagem no docker

    Ao personalizar o arquivo "DockerFile", vamos acessar a pasta com onde criou o arquivo.

    

    Na barra de informações onde esta p caminho , você colocara, a seguinte instrução CMD. Ele abrira o nosso prompt de comando do windowns.

    Feito o seguinte o primeiro comando para construir a nossa build é o seguinte.

    - OBS: Sempre que criarmos uma imagem temos que passar o nome da imagem, e uma tag.

    - Explicação do comando abaixo: 
        - docker => Usamos sempre que execultarmos algo relacionando ao Doker.
        - build => Quando queremos execultar a construção de uma imagem.
        - -t => seria para abranger o nome de nossa tag.
        - NomeImagem => Seria o nome da imagem ao qual esta subindo.
        - TagDaImagem => Uma breve descrição sobre a imagem como exemplo se ela e uma versão latest.
        - . => seria aonde ele encontria o nosso arquivo. Lembrando que . se refere se estiver na mesma pasta, se caso não estiver adicione o caminho da pasta on de esta o arquivo DockerFile.

       - docker build -t "nomeDaImagem:TagDaImagem" .