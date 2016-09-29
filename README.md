# 微信小程序 cnode社区版本

> 官方文档：https://mp.weixin.qq.com/debug/wxadoc/dev/

> 参考资料：https://github.com/coolfishstudio/wechat-webapp-cnode

### 小程序预览

![编辑器截图](./screenshots/demo2.gif)

### 项目结构
<pre>
│  .gitattributes
│  .gitignore
│  app.js                # 小程序逻辑
│  app.json              # 小程序公共设置（页面路径、窗口表现、设置网络超时时间、设置多tab）
│  app.wxss              # 小程序公共样式表
│  README.md             # 小程序项目说明
│  
├─image                  # 小程序图片资源
|
├─pages                  # 小程序文件
│  ├─common     
│  ├─detail
│  ├─index        
│  │    index.js    # 页面逻辑
│  │    index.wxml  # 页面渲染层
│  │    index.wxss  # 页面样式
│  ├─login
|  ├─logs
│  └─topics
│          
└─utils                  # 小程序公用方法模块
    api.js       
    util.js    
</pre>


### 开发环境
下载地址 ：https://mp.weixin.qq.com/debug/wxadoc/dev/devtools/download.html?t=1474887501214

### 开发过程
 后续补上、、、

### 使用说明

1. 将仓库克隆到本地：

  ```bash
  $ git clone https://github.com/vincentSea/wechat-cnode.git
  ```

2. 打开`微信Web开放者工具`（注意：必须是`0.9.092300`版本）

3. 选择`添加项目`，填写或选择相应信息

  - AppID：点击右下角`无AppID`
  - 项目名称：随便填写，因为不涉及到部署，所以无所谓
  - 项目目录：选择刚刚克隆的文件夹
  - 点击`添加项目`


### 特别感谢
感谢 coolfish 的项目案例

coolfish的github: https://github.com/coolfishstudio
