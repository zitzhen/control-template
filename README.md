# control-template
适用于连接CoCo-Community控件自动更新的模板

## 如何使用此template?
点击Github上方的「Use this template」创建自己的模板/如何使用此template

将此处的「README.md」文件 替换为您的control/控件的README.md文件 这将展示在CoCo-Community上方

您可创建LICENSE文件表明本项目的开源程度 许可范围等

## 如何添加控件
在本仓库中创建以你目标控件版本号的文件夹 例如`v1.0.0`或`1.0.0` 在里面放入`information.json`及`control.jsx`文件 `control.jsx`文件为您的控件文件。

## 正确使用`information.json`
您的`information.json`文件应按照以下格式进行配置
```json
{
  "Release_input": "总发行数量",
  "Current_version": "最新版本号",
  "author": "Github作者用户名",
  "Latest_submission_time": false,
  "Version_number_list": [
    "1.0.0"
  ]
}
```

其中 `Version_number_list`为版本号列表 如您有更多版本 请扩展该字段 例如
```json
  "Version_number_list": [
    "1.0.0",
    "1.1.0"
  ]
```

©[Your Name] [Year]

>use zitzhen/control-template template