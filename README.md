Markdown language: zh-cn

这是一个语言包扩展的模板。

请在 `build` 文件夹中操作内容。  
将 `info.json` 按照以下格式完善  
假设扩展名称是 `Extension` ，想要的语言是 `zh-cn`  
"id":"ExtensionName.langPack.zh.cn"  

假设作者有 XiaoMing 和 XiaoHong  
"author":"XiaoMing , XiaoHong"  
但如果只有 XiaoMing，那么  
"author":"XiaoMing"  

假设原扩展的版本号为`1.0.0`  
"version":"1.0.0"  

保存，回到 `build` 文件夹，打开 `locales` 文件夹，将 `en.json` 内填入汉化包的名称与介绍。  
假设名称为 `Extension zh-cn langPack` ，介绍为 `Extension language pack`  
```
{"ExtensionName.langPack.zh.cn.name": "Extension zh-cn langPack",
"ExtensionName.langPack.zh.cn.description": "Extension language pack"}
```

保存，回到 `locales` 文件夹，创建你想要的语言文件，对应上编辑器对应的语言名称。  
例如简体中文为 `zh-cn` ，那么创建名为 `zh-cn.json` 的文本文件。  
然后打开这个文本文件，按照扩展语言文件的格式，将内容填入。  
具体格式可以参考源扩展的语言文件。  

保存好语言文件，回到 `build` 文件夹，打开 `assets` 文件夹，将svg文件上传到scratch编辑器的造型区，然后按照里面的文字指示，编辑里面的文字。编辑好后，将scratch导出的图片覆盖原图。  

最后，回到根文件夹，将 `build` 文件夹压缩为`zip`文件，然后将名称改为以下格式。  
假设扩展名称是 `Extension` ，想要的语言是 `zh-cn` ，原扩展的版本号为`1.0.0`  
那么，文件名为 `Extension zh-cn langPack @1.0.0 .ccx`  
注意，必须把后缀改为 `ccx`  

恭喜，你的汉化包制作完成(≧▽≦)