# Retalho de Açúcar — Cardápio Digital

Cardápio digital dos bolos de rolo artesanais **Retalho de Açúcar**.
Página única (`index.html`), responsiva (mobile-first), com pedidos via WhatsApp.

🔗 Instagram: [@retalhodeacucar](https://www.instagram.com/retalhodeacucar/)

## Seções
- Tradicionais (Goiabada, Doce de Leite, Café)
- Juninos (Milho, Macaxeira, Paçoca, Cocada) — com decoração de bandeirinhas
- Pé de Moleque
- Gourmet (Chocolate, Ninho com Nutella, Oreo e outros)
- Encomende para sua festa (Minis e Bolos de Festa) — aniversário, batizado, chá de bebê, formatura, casamento
- Galeria + história

## Como editar
Tudo num arquivo só: `index.html`.

| O quê | Onde |
|-------|------|
| Número do WhatsApp | `<meta name="whatsapp" content="55...">` no topo |
| Preços e sabores | objeto `MENU` no `<script>` |
| Fotos dos produtos | campo `img:"fotos/arquivo.jpg"` em cada item do `MENU` |
| Fotos da galeria | array `GALLERY` no `<script>` |

Crie uma pasta `fotos/` ao lado do `index.html` e aponte os caminhos.

## Publicar (GitHub Pages)
Settings → Pages → Branch: `main` / `/ (root)` → Save.
O site fica em `https://<usuario>.github.io/<repositorio>/`.

## Tecnologia
HTML + CSS + JavaScript puro. Sem dependências, sem build. Fontes via Google Fonts.
