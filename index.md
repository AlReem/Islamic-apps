---
layout: default
---
### Best islamic applications on Android and Apple iStore
The following are the best islamic applications on different platforms.  List is not mature, please comment if you would like to include more.

|#|Icon & Link|App name|Description|Platform|
|-|-|-|-|-|-|
{% for app in site.data.apps %}|{{app.id}}|[![{{app.appname}}]({{app.imagelink}}){: height="150" width="150" .img-responsive .img-thumbnail}]({{app.link}})|{{app.appname}}|{{ app.description | markdownify_ }}|{{app.platform}}|
{% endfor %}{: .table .table-striped .table-hover}
