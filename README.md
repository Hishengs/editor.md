# Editor.md 增强版本


> 本版本 fork 自 [Editor.md](https://github.com/pandao/editor.md 'Editor.md')，由于原库作者已经很久不维护了，所以我自己 fork 了一份用于解决遇到的一些 bug 和增强了一些功能及体验。

### 解决的 bug
---
1. 添加参数 `syncPreviewContent | true` 默认实时同步内容到预览区域，用于解决不开启watch而开启预览时预览区域无内容的问题


### 添加的功能
---
#### 图片上传
1. 添加自定义上传 post 参数  `imageUploadParams | {}`
2. 添加指定上传的图片 input name 参数  `imageUploadName | ''`


