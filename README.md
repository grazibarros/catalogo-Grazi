# Catálogo Atomy Grazi

Projeto estático feito apenas com HTML, CSS e JavaScript puro. O arquivo principal é `index.html`, então ele pode ser publicado na Vercel sem framework, build command ou dependências.

## Como testar localmente

Abra o `index.html` direto no navegador ou rode um servidor estático simples:

```bash
python3 -m http.server 3000
```

Depois acesse:

```text
http://localhost:3000
```

## Como atualizar a versão na Vercel

1. Faça as alterações necessárias no `index.html`.
2. Teste localmente no navegador.
3. Envie a nova versão para o repositório conectado à Vercel:

```bash
git add index.html README.md
git commit -m "Atualiza catalogo Atomy"
git push
```

4. A Vercel deve iniciar um novo deploy automaticamente.
5. No painel da Vercel, abra o projeto e confira a aba **Deployments** para validar se o deploy ficou como **Ready**.

## Configuração recomendada na Vercel

- Framework Preset: **Other**
- Build Command: deixe vazio
- Output Directory: deixe vazio
- Root Directory: pasta raiz do repositório

Se preferir subir manualmente pela Vercel CLI:

```bash
npx vercel
```

Para publicar direto em produção:

```bash
npx vercel --prod
```
