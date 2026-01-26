# Formatierungen

## Links (URLs)

```
[Linktext](URL){:target="_blank"}
```

{:target="_blank"} öffnet Link in neuem Fenster

## Images

Die Bilder liegen in /assets/images und ggfs in Unterordnern davon ...

```
<img src="{{ site.baseurl }}/assets/images/.../imagename.png" alt="Barrierefreiheit" width="600">
```

Mit der width experimentieren ...

## Inhaltsverzeichnis in der Sektion

```
# Überschift
{: .no_toc }

## Inhalt
{: .no_toc .text-delta }

1. TOC
{:toc}
```

`1. TOC` erzeugt ein nummeriertes Inhaltsverzeichnis