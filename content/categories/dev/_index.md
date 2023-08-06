---
title: Dev Posts
---

<ul>
  {{ range .Pages }}
    <li>
      <a href="{{ .Permalink }}">{{ .Title }}</a>
      {{ .Params.wikipedia }}
    </li>
  {{ end }}
</ul>