# Usa a imagem oficial do WordPress mais recente como base
FROM wordpress:latest

# Define as variáveis de ambiente que configuram a conexão do WordPress com o banco de dados
ENV WORDPRESS_DB_HOST=db:3306      # Define o endereço do banco de dados (serviço 'db' no Docker Compose)
ENV WORDPRESS_DB_NAME=wordpress    # Nome do banco de dados que será usado pelo WordPress
ENV WORDPRESS_DB_USER=root         # Usuário do banco de dados
ENV WORDPRESS_DB_PASSWORD=root     # Senha do banco de dados

# Expondo a porta 80 para permitir acesso à aplicação via navegador
EXPOSE 80

# Define o comando padrão que será executado ao iniciar o contêiner
CMD ["apache2-foreground"]
