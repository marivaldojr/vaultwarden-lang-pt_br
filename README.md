# vaultwarden-lang-pt_br

Tradução para português brasileiro de todos os modelos de e-mail de dani-garcia/vaultwarden localizados em src/static/templates/email, conforme descrito na [Wiki oficial](https://github.com/dani-garcia/vaultwarden/wiki/Translating-the-email-templates).

📌 Versões e Tags
Para garantir a compatibilidade e evitar erros de renderização nos e-mails, este repositório segue as versões oficiais do Vaultwarden.

Tags: Existe uma tag correspondente para cada versão do Vaultwarden (ex: 1.32.0, 1.35.4).

Como usar: Certifique-se de baixar os arquivos da tag que condiz com a versão que você está executando.

⚠️ Versão atual (branch principal): alinhada à v1.37.4

Na v1.37.x o modelo `admin_reset_password` foi substituído por `admin_account_recovery`. Ele avisa quando um administrador altera a senha mestra, redefine o login em duas etapas, ou as duas coisas. Também entrou o modelo `recover_twofactor`, enviado quando o código de recuperação desativa o login em duas etapas. Quem ainda usa a v1.35.4 deve permanecer na tag `1.35.4`.
