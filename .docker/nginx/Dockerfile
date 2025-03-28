# Use a imagem oficial do Nginx como base
FROM nginx:alpine

# Adiciona o arquivo de configuração personalizado do Nginx
ADD .docker/nginx/default.conf /etc/nginx/conf.d/

# Certifique-se de que o diretório /var/www/html está disponível
# Caso esteja usando volumes, não é necessário copiar os arquivos diretamente para o container
# porque os arquivos serão montados a partir do host
# COPY ./src /var/www/html

# Defina a porta em que o Nginx vai escutar
EXPOSE 80
