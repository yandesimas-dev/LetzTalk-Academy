# LetzTalk Academy — site

Site estático. Nenhuma build, nenhuma dependência: é só subir a pasta.

```
index.html        página completa (35 KB)
img/              13 imagens em WebP (555 KB no total)
```

## Publicar na Netlify (mais rápido)
1. Acesse app.netlify.com e faça login.
2. Na aba **Sites**, arraste esta pasta inteira para a área "Deploy manually".
3. Pronto — sai no ar em segundos com HTTPS.
4. Em *Site settings → Domain management* você liga o domínio próprio.

Para atualizar depois: arraste a pasta de novo.

## Publicar na Vercel
1. Acesse vercel.com e faça login.
2. **Add New → Project → Deploy without Git** e envie esta pasta
   (ou suba a pasta num repositório do GitHub e importe o projeto).
3. Framework Preset: **Other**. Não preencha comando de build nem output.
4. Em *Settings → Domains* você liga o domínio próprio.

## Trocar uma imagem
Substitua o arquivo dentro de `img/` mantendo o mesmo nome — o HTML não muda.
Se o tamanho em pixels mudar, ajuste `width` e `height` na tag `<img>`
correspondente, para a página não "pular" durante o carregamento.

| arquivo | onde aparece |
|---|---|
| `logo-1.webp` / `logo-2.webp` | logo no topo e no rodapé (tema claro / escuro) |
| `professor-yan.webp` | foto redonda do topo |
| `turma-encontros.webp` | "Aqui você não aprende sozinho" |
| `aula-ao-vivo.webp` | bloco 01 — Aulas ao vivo com professor |
| `biblioteca-aulas.webp` | bloco 02 — Aulas gravadas |
| `app-pronuncia.webp` | bloco 03 — Treino de pronúncia |
| `depoimento-01..06.webp` | carrossel de depoimentos |
