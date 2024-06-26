# 让你的附属自动更新(info.yml)

<mark style="color:red;">**注意：**</mark>带\*为必填

**示例：**

```yaml
id: example
name: "示例附属"
depends: []
pluginDepends: []
version: "1.0"
description: "RSC示例附属"
authors: ["mmmjjkx"]
repo: "SlimefunReloadingProject/rsc-example"
```

| 内容 | 描述 |
| --- | ----------- |
| \*id | 附属的id。 |
| \*name | 附属的名称。 |
| depends | 依赖的其它用RykenSlimeCustomizer编辑的自定义附属id |
| pluginDepends | 依赖的插件名称，即在plugin.yml中定义的名称。 |
| \*version | 附属的版本。 |
| description | 附属的描述。 |
| \*authors | 附属的作者。 |
| \*repo | 附属对应的github库，这是附属更新的必填项。 |

## 更新步骤

1.从**GitHub**获取存储库，地址为上述的`repo`

2.寻找最新发行版并比对

3.如果最新版跟当前版本不同则下载源码zip

4.解压zip到`addons/附属ID`

## 注意事项

在Github上设置的Releases版本一定要与上述的version相同！

否则会造成**重复下载**。
