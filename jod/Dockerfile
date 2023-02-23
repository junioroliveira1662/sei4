FROM image-registry.openshift-image-registry.svc:5000/openshift/php:latest

# Copie o seu código fonte para o diretório de trabalho
COPY . /app

# Defina o diretório de trabalho
WORKDIR /app

# Exponha a porta 8080
EXPOSE 8080

# Inicie o servidor da web do PHP
CMD ["php", "-S", "0.0.0.0:8080"]