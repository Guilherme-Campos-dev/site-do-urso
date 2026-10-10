# Site (landing page) da Urso Burguers

Só a página pública. Os pedidos são enviados para a API do painel.

1. O index.html já está apontando para a API do painel (`https://urso-painel.vercel.app/api`). Se o endereço do painel mudar, troque a linha `var API_URL=...`.
2. Suba esta pasta em um repositório do GitHub (ex.: urso-site).
3. Na Vercel: Add New > Project > escolha o repositório > Deploy. Não precisa de variáveis.
4. Domínio: seusite.com.br (Settings > Domains).

Se o endereço do painel mudar, atualize a linha do API_URL.
