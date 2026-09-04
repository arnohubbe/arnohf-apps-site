# ArnoHF Apps

Site institucional estático para os aplicativos ArnoHF.

## Estrutura

- `/public/index.html` — página inicial
- `/public/camera-files/` — página do Camera Files
- `/public/camera-files/privacy/` — Política de Privacidade
- `/public/camera-files/support/` — suporte
- `/public/assets/site.css` — estilos
- `/public/_headers` — cabeçalhos de segurança para Cloudflare Pages

## Antes de publicar

Procure em todo o repositório por:

`[SEU_EMAIL_PUBLICO_DE_SUPORTE]`

e substitua pelo endereço público de suporte do Camera Files.

## Repositório GitHub sugerido

`arnohf-apps-site`

## Publicação no Cloudflare Pages

Configuração sugerida:

- Production branch: `main`
- Framework preset: `None`
- Build command: `exit 0`
- Build output directory: `public`
- Root directory: deixar vazio (raiz do repositório)

Depois do primeiro deploy, o Cloudflare Pages fornecerá um endereço `*.pages.dev`.

Se o projeto for chamado `arnohf-apps`, a URL normalmente será semelhante a:

`https://arnohf-apps.pages.dev/`

A Política de Privacidade ficará em:

`https://arnohf-apps.pages.dev/camera-files/privacy/`

## Atualizações futuras

Para adicionar novos aplicativos, crie novas pastas dentro de `/public`, por exemplo:

- `/public/app-2/`
- `/public/app-3/`

Cada aplicativo pode ter sua própria página, suporte e política de privacidade.
