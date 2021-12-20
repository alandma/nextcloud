# Nextcloud

Um lugar seguro para todos os seus dados. 

Acesse e compartilhe seus arquivos, calendários, contatos, e-mail e muito mais de qualquer dispositivo.

## Subindo estrutura
```bash
docker-compose up -d --build
```
O usuario e senha padrão de acesso se encontra no arquivo `nc.env`, dentro de `.env`.

O onlyoffice server esta desativado, mas se for uma necessidade editar arquivos de doc ou planilhas online, é somente descomentar no `docker-compose.yml`.
