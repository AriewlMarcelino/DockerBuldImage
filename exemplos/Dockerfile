# Primeira camamda do nosso Docker;
FROM ubuntu:18.04

# Vamos execultar com o comando run para poder, execultar alguns comandos
    # Atualiza o nosso ubuntu
RUN apt-get update \
    # Onstalando o nginx, dentro do ubuntu.
    && apt-get install -y nginx \
    # Limpa nossa tela
    && apt-get clean \
    # Deletar algumas pasta desnecessarias;
    && rm -rf /var/lib/apt/lists/* /tpm/* /var/tmp/* \
    # Traz um log com informações de conf dentro da nginx.conf
    && echo "deamon off;" >> /etc/nginx/nginx.conf

# Comando de acesso a aplicação a imagem;
EXPOSE 80
# Comando de execução do sistema;
CMD ["nginx"]

