Sertão News — Deploy na Vercel (HTML estático)
==============================================

Arquivos principais:
- index.html (home)
- paulo-afonso.html, delmiro-gouveia.html, brasil.html, receitas.html, anuncie.html, admin.html
- live.json, boletim.json, settings.json
- vercel.json (configuração para servir estático)
- 404.html
- imagens SVG

Como publicar (Web UI):
1) Acesse vercel.com → New Project → Continue → Import → **Other** (ou Deployments → New Deployment).
2) Arraste e solte TODOS os arquivos desta pasta (sem subpastas) na área de upload.
3) Em Framework preset, escolha **Other**. Não defina Build Command.
4) Output Directory: **.** (um ponto).
5) Deploy.

Após o deploy:
- Edite `settings.json` no próprio painel (ou reenvie o arquivo) para colocar seu **Meta Pixel** e **GA4**.
- Edite `live.json` e `boletim.json` para atualizar o Ao vivo e o Boletim.

Rotas úteis:
- /index.html  (ou /)
- /paulo-afonso.html
- /delmiro-gouveia.html
- /brasil.html
- /admin.html (página de editor — oculta do menu; noindex)
