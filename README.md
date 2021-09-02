# Shortcodes for [Hugo](https://gohugo.io)
These are a collection of custom shortcodes used in [YourOnly.One](https://YourOnly.One) and other Hugo-powered websites made by YourOnly.One.

## Shortcodes
* `{{< image >}}`
* `{{< instagram >}}`
* `{{< music >}}`
* `{{% quotebox %}}`
* `{{< scribd >}}`
* `{{< youtube >}}`

### How to use {{< image >}}
```go
{{< image
  type="image OR imagecoverattrib"

  imgheight=""
  imgwidth=""

  imgsrc=""
  imglink=""
  imgrel="noopener external nofollow"

  imgtitle="formal title"
  imgcaption="description"
  imgalt=""

  attribalign=""

  licensecode="any OR cc0 OR publicdomain OR allrightsreserved"
  licenseurl=""
  licensename=""

  attribto=""
  attriblink=""
  attribrel="noopener external nofollow"
>}}
```

### How to use {{< instagram >}}
```go
{{< instagram POST_ID hidecaption >}}
```

### How to use {{< music >}}
```go
{{< music src="" >}}
```

### How to use {{% quotebox %}}
```go
{{% quotebox boxstyle="qbs_generic" qmarkstyle="qbm_doublequotationmark" boxcolour="qbc_blue" attribalign="txt_right" srctitle="" srclink="" srcrel="noopener external nofollow" attribto="" attriblink="" attribrel="noopener external nofollow" %}}
  content
{{% /quotebox %}}
```

### How to use {{< scribd >}}
```go
{{< scribd
  doctitle=""
  docid=""
  startpage="1"
  viewmode="slideshow OR scroll"
  docrel="noopener external nofollow"

  authorname=""
  authorid=""
  authorrel="noopener external nofollow"
>}}
```

### How to use {{< youtube >}}
```go
{{< youtube id="" title="" >}}
```
