# 表情包管理器
可以方便的复制表情到剪贴板 也可以从剪贴板保存表情（ctrl+v）

这个最初是为了自用而做的

解决新版QQ没了本地表情的痛点。

从1.1.0开始正式支持下载 TG 贴纸包

目前只提供 Windows amd64 的程序

## 下载

在 [releases](https://github.com/morinoyuki/emoji-manager-releases/releases) 中

## 配置注释

程序启动后会让你选择一个表情包主目录

然后会自动生成配置文件 `config.ini`

```Ini
[Settings]
maindirectory = C:/xxxxx  #表情包主目录
windowsize = 779x686      #窗口大小
recentlimit = 10          #历史记录上限
```

### 1.3.x 支持了与 Google Drive 同步表情包文件
同步时在程序运行期间会监视本地文件的变化同步到云端

在程序运行之前的变化会在启动时全部扫描同步一次 但不会尝试删除文件 避免丢失数据

使用之前需要先准备 `credentials.json` 文件 放程序目录中

1. 打开 [Google Cloud Console](https://console.cloud.google.com/)。
2. 创建一个新项目或选择现有项目。
3. 启用 Google Drive API。
4. 创建 OAuth 2.0 客户端凭据，下载 `credentials.json` 文件。

其他修改懒得写

最后：新年快乐

## 预览图
![](c8a2cccf44574c830449953fb1d4d0dc.gif)
