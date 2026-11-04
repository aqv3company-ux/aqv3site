# Site da AQV3 Company

Site estático (HTML + CSS + um pouco de JS), sem build. Arquivos:
- `index.html` — o site inteiro
- `favicon.svg` — ícone da aba

## 1. Trocar seus contatos
No final do `index.html`, edite o bloco `CONTATO` (WhatsApp, Instagram, e-mail).
O número do WhatsApp vai só com dígitos: 55 + DDD + número. Ex.: `5522988887777`.

## 2. Publicar na Vercel
1. Crie um repositório novo no GitHub (ex.: `aqv3-site`) e envie esta pasta:
   ```
   cd aqv3-site
   git init
   git add .
   git commit -m "Site da AQV3 Company"
   git branch -M main
   git remote add origin https://github.com/SEU-USUARIO/aqv3-site.git
   git push -u origin main
   ```
2. Vercel → Add New → Project → importe `aqv3-site`.
3. Framework Preset: **Other**. Não precisa de comando de build. Clique em Deploy.

Cada `git push` depois disso atualiza o site.

## 3. Domínio próprio (opcional)
Vercel → projeto → Settings → Domains → adicione `aqv3.com.br` (ou o que você registrar no Registro.br)
e copie os registros DNS que a Vercel mostrar para o painel do Registro.br.
