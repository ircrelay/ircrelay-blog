title: Blog
----

{{ range .Site.Pages.Children "posts/" }}
#### [>> {{ .Title }}]({{ $.UrlTo . }})

*Posted on {{ .Date.Format "Monday, January 02, 2006" }} by [{{ .Other.Author }}]({{ .Other.Author }})*
{{ end }}
