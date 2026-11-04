# Trovato Tech: Landing page

Site estático (HTML, CSS e JS puros, sem build).

## Rodar localmente

```bash
python3 -m http.server 5173
```

Abra http://localhost:5173.

## Estrutura

- `index.html`: página única (header, hero, logos, serviços, diferenciais, método, cases, depoimentos, redes sociais, FAQ, contato/localização e rodapé)
- `assets/css/styles.css`: estilos; paleta em `:root` (navy dos SVGs de referência + acento cobalto)
- `assets/js/main.js`: menu mobile, carrossel de logos e de depoimentos, contadores, animações e validação do formulário
- `assets/img/`: logo e favicon

## Antes de publicar: substituir os placeholders

Todos estão marcados com `PLACEHOLDER` ou `TODO` no código.

- [ ] Logos e nomes de clientes (são fictícios; use apenas clientes que autorizaram)
- [ ] Depoimentos (são fictícios; use apenas com autorização por escrito)
- [ ] Cases e números (12 anos, 140+ projetos etc.)
- [ ] Endereço, mapa (coordenadas do iframe), telefone, WhatsApp, e-mail e CNPJ
- [ ] URLs e handles das redes sociais (também no JSON-LD do `<head>`)
- [ ] Conectar o formulário a um endpoint real (`assets/js/main.js`)
- [ ] Links de Política de Privacidade, Termos e Cookies
- [ ] Domínio em `canonical` / `og:url`
