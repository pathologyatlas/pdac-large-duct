







```
r language pdac-large-duct, echo=FALSE, include=TRUE
source("./R/language.R")
output_type <- knitr::opts_knit$get("rmarkdown.pandoc.to")
```


```
asis pankreatik duktal adenokarsinom, large-duct tip TR, echo = (language == "TR")
## pdac-large-duct - pankreatik duktal adenokarsinom, large-duct tip {#sec-pdac-large-duct }
```


```
asis pancreatic ductal adenocarcinoma, large duct type EN, echo = (language == "EN")
## pdac-large-duct - pancreatic ductal adenocarcinoma, large duct type {#sec-pdac-large-duct }
```






```
r pdac-large-duct screenshot HE, eval=TRUE, include=FALSE
if (!file.exists("./screenshots/thumbnail_pdac-large-duct-HE.png")) {
webshot2::webshot(
  url = "https://images.patolojiatlasi.com/pdac-large-duct/HE.html",
  file = "./screenshots/thumbnail_pdac-large-duct-HE.png"
)
}
```





::::: panel-tabset


### WSI - Link










[https://images.patolojiatlasi.com/pdac-large-duct/HE.html](https://images.patolojiatlasi.com/pdac-large-duct/HE.html)





```
asis, echo = (language == "TR")

**pankreatik duktal adenokarsinom, large-duct tip**


[![Tam Ekran Görmek İçin Resmi Tıklayın](./screenshots/thumbnail_pdac-large-duct-HE.png){width="25%"}](https://images.patolojiatlasi.com/pdac-large-duct/HE.html) [Tam Ekran Görmek İçin Resmi Tıklayın](https://images.patolojiatlasi.com/pdac-large-duct/HE.html)
```

```
asis, echo = (language == "EN")

**pancreatic ductal adenocarcinoma, large duct type**

[![Click for Full Screen WSI](./screenshots/thumbnail_pdac-large-duct-HE.png){width="25%"}](https://images.patolojiatlasi.com/pdac-large-duct/HE.html) [Click for Full Screen WSI](https://images.patolojiatlasi.com/pdac-large-duct/HE.html)

```





### WSI








```
asis, echo = ((language=="TR") & (output_type=="html"))
Mikroskopik görüntüleri inceleyin:

<iframe src="https://images.patolojiatlasi.com/pdac-large-duct/HE.html" style="height:600px;width:100%;" data-external="1"></iframe>

```





```
asis, echo = ((language == "EN") & (output_type=="html"))

See Microscopy with viewer:

<iframe src="https://images.patolojiatlasi.com/pdac-large-duct/HE.html" style="height:600px;width:100%;" data-external="1"></iframe>

```





### Diagnosis


```
asis, echo = (language == "TR")


::: {.callout-tip collapse="true" appearance="default" icon="true"}
### Tanı için tıklayın

pankreatik duktal adenokarsinom, large-duct tip

:::


```


```
asis, echo = (language == "EN")


::: {.callout-tip collapse="true" appearance="default" icon="true"}
### Click for Diagnosis

pancreatic ductal adenocarcinoma, large duct type

:::

```









:::::








