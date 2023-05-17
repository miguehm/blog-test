---
title: "Mi Primer Post"
date: 2023-05-17T10:25:55-06:00
draft: false
toc:
  enable: true
  auto: true
code:
  copy: true
  maxShownLines: 50
---

## Post de Prueba

{{< typeit >}}
Texto animado como escritura en teclado en vivo
{{< /typeit >}}

{{< figure src="/cats/cat.jpg" title="michi (figure)" >}}

{{< youtube G6TyH-dQUV0 >}}

{{< highlight html >}}
<section id="main">
    <div>
        <h1 id="title">{{ .Title }}</h1>
        {{ range .Pages }}
            {{ .Render "summary"}}
        {{ end }}
    </div>
</section>
{{< /highlight >}}

{{< admonition quote "Frase" true >}}
Una piedra y un grano de arena, en el agua se hunden igual.
{{< /admonition >}}

