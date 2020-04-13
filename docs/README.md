## PicGo安装与简单应用

# PicGo的安装


## 配置图床（[Github](https://github.com)）
### 新建库
 - 进入 [GitHub官网](https://github.com/)，注册账号。
 - 点击右上角+号，点击第一个New repository![在这里插入图片描述](https://img-blog.csdnimg.cn/20200409162235354.jpg?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80NTc1MzkyNA==,size_16,color_FFFFFF,t_70)
 - 创建新的仓库，第一行**仓库名**必填
 - 第二行为**仓库的说明**，可以*不填写*
 - 选项**选第一个公开**，将最后的**方块勾选✔**，点击**绿色的创建仓库**
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200409163225810.jpg?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80NTc1MzkyNA==,size_16,color_FFFFFF,t_70)

### 创建Token（令牌）

 - 建完库后，点击右上角头像列表中**倒数第二个Settings**（设置）
 - 进入后点击右边蓝字的**最后一个Developer settings**（开发人员设定）
 ![在这里插入图片描述](https://img-blog.csdnimg.cn/20200409164819458.jpg?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80NTc1MzkyNA==,size_16,color_FFFFFF,t_70)
 - 进入后点击右边蓝字的**最后一个Personal access tokens**（个人访问令牌）
 - 点击中间右上角的**Generate now token**（生成新令牌）
    ![在这里插入图片描述](https://img-blog.csdnimg.cn/20200409165601152.jpg?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80NTc1MzkyNA==,size_16,color_FFFFFF,t_70)
 - 在**Note(请注意)**填写token名称
 - 将**repo全部勾上√**
 - 其余不用管，直接到低点击**绿色图标Generate token**（生成令牌）
 ![在这里插入图片描述](https://img-blog.csdnimg.cn/2020040917053946.jpg?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80NTc1MzkyNA==,size_16,color_FFFFFF,t_70)

 - 完成后页面会跳转，生成令牌，**令牌只出现一次**，**一定要保存**
 - 黑线覆盖的部分就是令牌![](https://img-blog.csdnimg.cn/20200409171039738.jpg?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80NTc1MzkyNA==,size_16,color_FFFFFF,t_70)
 - ***到这GitHub库与令牌就配置完成***
## [PicGo](https://molunerfinn.com/PicGo/)的安装与配置
### PicGo的安装
 - 首先进入[PicGo](https://molunerfinn.com/PicGo/)官网，点击免费下载
 - 进入大佬分享在GitHub上的开源软件界面
 - 向下找到最新版本的下载地址（.dmg为苹果系统版本，.exe为Windows系统版）
![在这里插入图片描述](https://img-blog.csdnimg.cn/2020040917523532.jpg?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80NTc1MzkyNA==,size_16,color_FFFFFF,t_70)
### PicGo的配置
 - 下载安装完后打开PicGo
 - 点击**左边图床设置**进入**GitHub图床**
 - 设定仓库名，填写：**你的GitHub名/新建的GitHub库名**如：**GitHubname/Repositoryname**
 - 分支，**默认填master**
 - 设定Token，写**刚才保存的token令牌**
 - 指定存储路径，**默认填img/**
 - 点击确定和设为默认图床
![在这里插入图片描述](https://img-blog.csdnimg.cn/202004091810473.jpg?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80NTc1MzkyNA==,size_16,color_FFFFFF,t_70)
 - 进入PicGo设置，点击**设置Server**，将**设置监听端口改为
 -==36677==**
 ![在这里插入图片描述](https://img-blog.csdnimg.cn/20200409182635338.jpg?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80NTc1MzkyNA==,size_16,color_FFFFFF,t_70)
 - 最好将PicGo设置中的时间戳重命名选上（两项设置都是为防止在Markdown使用上传照片时出错）
## PicGo的简单应用，[Tpora](https://typora.io/)，[Markdown](https://www.runoob.com/markdown/md-tutorial.html)
 *不了解Typora，和Markdown的可以点小标题的链接进行下载与了解*

 - 安装好后找到文件中的偏好设置
 - 点击**图像**，**前两项打勾√**
 - 将**上传服务改为PicGo（app）**
 - PicGo路径改为你**本地PicGo安装目录中的PicGo.exe文件
 -** 
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200409183914117.jpg?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80NTc1MzkyNA==,size_16,color_FFFFFF,t_70)
 ![在这里插入图片描述](https://img-blog.csdnimg.cn/20200409183923672.jpg?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80NTc1MzkyNA==,size_16,color_FFFFFF,t_70)
 - 在Tpora中插入图片后点击上传，图片将通过PicGo上传到Github的库中，以后传输Tpora文件时便不用将图片一起打包上传

借鉴文章视频：开始安装时查了很多，这只是个别几个
手把手教你用Typora自动上传到picgo图床【教程与排坑】：https://zhuanlan.zhihu.com/p/114175770
picgo介绍：https://picgo.github.io/PicGo-Doc/zh/guide/
bilibiil视频（不是本人）：https://www.bilibili.com/video/BV1TE411w758?t=96

> An awesome project.
>
> 
>
> >>>>>> 8a131dc... myblogs first commit

