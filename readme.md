# Introduction

resume via Gulp+Scss+Jade, it is about me . you can modify info.json about your infomation.<br>
一款基于Gulp+Scss+Jade生成在线简历生成器，你能够修改其中的info.json来修改简历的内容，默认的内容为我简历的内容。<br>
如果要修改样式与布局，请在 src=>jade=>layout.jade && src=>scss=>xxx.scss 进行修改，具体语法请参考Jade,Scss<br>

### 运行方式：
打开终端，运行`gulp`即可。 <br>
生成内容可在dist文件夹查看。<br>
PDF请在chrome浏览器下按ctrl+p or command+p,保存为pdf格式，放入项目的pdf文件夹。<br>
不建议自动部署，因为覆盖掉之前你github pages的内容，如果真的需要自动部署，运行`gulp deploy`即可。

### 注意
请修改项目里面GitHub的地址为你的地址。图标目前不是很全，如果自己想要添加，请利用字体图标自行解决。

### 自定义域名
修改CNAME文件，替换为你的域名即可
