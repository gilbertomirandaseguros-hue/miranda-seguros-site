# Site Miranda Soluções & Seguros

Site estático (HTML + CSS + um pouco de JavaScript), sem dependências e sem etapa de build.

## Estrutura
- `index.html`: página principal (seguros, sobre, depoimentos, parceiras, cotação e contato)
- `politica-de-privacidade.html`: política de privacidade (LGPD)
- `assets/`: logo e brasão

## Formulário de cotação
O formulário monta uma mensagem e abre o WhatsApp (81) 99532-3757 já com os dados do cliente preenchidos.
Para trocar o número, altere `WHATSAPP` no final do `index.html` e os links `wa.me/5581995323757`.

## Publicar na Vercel
1. Suba esta pasta para um repositório no GitHub.
2. Em vercel.com, clique em **Add New → Project**, escolha o repositório e clique em **Deploy** (não precisa configurar nada).
3. Em **Settings → Domains**, adicione `mirandaseguros.com.br` e siga as instruções de DNS.
