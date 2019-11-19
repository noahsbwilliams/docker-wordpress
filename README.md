# Simple reference repo for deploying WordPress with Docker

## Usage

1. Clone repo
2. Make a `.env` file in the dir
   1. Add database creds in the `DB_USER` & `DB_PASSWORD` environment variables
3. Put the sucker behind a reverse proxy to handle SSL
   1. Recommended Config: [Nginx](https://www.nginx.com) & [CertBot](https://certbot.eff.org)
