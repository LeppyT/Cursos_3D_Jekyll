

## Para criar um post, faça upload ao diretório `_posts`. O nome do arquivo deve ser "AAAA-MM-DD-titulo-post.html".

Primeiro, digite a Front Matter do post, que determina a estrutura da página.\

```markdown
---
layout: post
title: "Seu título aqui"
subtitle: "Subtítulo do post"
author: "Autor do post"
date: AAAA-MM-DD [HH:MM:SS] (OBS: pode-se colocar uma data futura,
e o site mostrará apenas naquela data. Horário é opcional.)
background: '/img/posts/exemplo.jpg' (O upload da imagem é necessário,
ou um link para a imagem pode ser incluído aqui caso seja de um site externo)
---
```

Após isso, você pode escrever seu post utilizando apenas tags de HTML de forma simplificada. Segue aqui exemplos:\


```html
<p>Parágrafo comum. Para inserir texto de forma normal.</p>


<h2 class="section-heading">Título de uma seção</h2>

<blockquote class="blockquote">Tag para uma citação</blockquote>

<img class="img-fluid" src="https://source.unsplash.com/Mn9Fa_wQH-M/800x450" alt="Erro">
(Imagens. src pode conter uma imagem nativa ao site ou o link a uma imagem externa)
<span class="caption text-muted">Texto de legenda centralizado.
A classe text-muted muda a cor do texto para um cinza mais leve,
e pode ser incluído em qualquer tag que possui texto.</span>
```

Não se esqueça de fazer upload das umagens utilizadas na pasta img!\
[Um post de exemplo pode ser encontrado aqui](https://leppyt.github.io/Cursos_3D_Jekyll/2025/04/09/cursos-d3-saber.html)

