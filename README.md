## 教程

### auto-adspower

本工具是结合 adspower 指纹浏览器实现自动化的工具，意在自动化养号，撸毛等功能。

目前支持的功能

#### twitter 相关
- [x] twitter自动点赞
- [x] twitter自动转推
- [x] twitter自动关注


### 目录


#### conf.ini

conf.ini 是工具的配置文件，可以用文本编辑器(记事本)打开，每行配置有详细的注释可供参考。

#### user_list.xlsx

'user_list.xlsx' 的文件，是通过 adspower 导出的 excel。
如图：
![ads导出](picture/adps-导出.png)
其中，该 excel 有一列 id 列，是 adspower 指纹浏览器的账号 id ，读取该列，是为了每次通过程序加载 id 对其进行浏览器的操作。

#### twitter_url.xlsx

收录了区块链相关的知名作者，自动关注若开启，则会默认从中随机筛选进行账号关注