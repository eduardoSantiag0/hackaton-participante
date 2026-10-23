Cada grupo deve:
1. Copiar o bloco do email para grupo-template/.env
2. Executar ./gerar-conf.sh (gera o wg0.conf a partir do .env)
3. Executar docker compose up -d (assim não precisa instalar o WireGuard na máquina deles)
4. Acessar a aplicação do grupo em http://localhost:8080 (a app do grupo precisa escutar na porta 8080 dentro do container deles, convenção fixa)
