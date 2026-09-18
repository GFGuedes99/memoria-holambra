MEMÓRIA HOLAMBRA — V4

Esta versão NÃO usa reset-password.html.
A recuperação de senha acontece dentro do próprio index.html.

IMPORTANTE:
1. Troque AUTH_EMAIL no index.html pelo e-mail criado em Supabase > Authentication > Users.
2. Para recuperação de senha funcionar, o site precisa estar publicado em uma URL HTTPS/HTTP (ou localhost). Abrir por file:// não permite o redirecionamento do e-mail.
3. No Supabase, em Authentication > URL Configuration, coloque a URL publicada em Site URL e adicione também a URL exata da página como Redirect URL.

Fluxo:
Login > Esqueci a senha > e-mail > link do Supabase > nova senha > volta para a memória.
