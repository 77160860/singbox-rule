# singbox-geosite

在links.txt添加规则集，自动生成 sing-box Source Format。fork后自己添加想要转换的规则集。

仓库 Settings ----> Actions ----> General ----> Workflow permissions ----> Read and write permissions 勾选上

规则集源文件写法eg:

```json
{
  "tag": "me",
  "type": "remote",
  "format": "binary",
  "url": "https://raw.githubusercontent.com/77160860/singbox-geosite/main/rule/me.srs",
  "download_detour": "auto"
}
```
