# Desmame Carinhoso · Quiz e página de vendas

Página estática (um único `index.html`) com o quiz "Por onde começar o desmame" e a oferta do guia Desmame Carinhoso.

## Configuração
- Link do checkout: constante `CHECKOUT_URL` no fim do `index.html` (Lastlink).
- Eventos registrados em `dataLayer` (e no Meta Pixel, se instalado): `quiz_start`, `quiz_complete`, `skip_to_offer`, `checkout_click`.
- Parâmetros UTM da URL são repassados ao checkout.

## Publicação
Projeto estático na Vercel, sem build. Cada push na branch principal publica automaticamente.
