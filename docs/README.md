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

## 第一天的学习笔记

### Git

- **git config --global user.name"用户名"**
- **git config --global user.email"邮箱"**
- **git log --pretty=oneline**  #显示版本，一起显示
- **git log**      #查看版本，一步步显示
- **git reflog** #查看历史
- **git reset --hard 版本号**   #进入到版本号所在的状态
- **版本号可以不写全，至少4位**
### GitHub

- **git init**        #初始化仓库
- **git status**  #查看当前状态
- **git add 文件名**  #添加到缓存区，可以是多个文件
 **git add .**    将当前目录下添加到缓存区
- **git commit -m "注释内容"**  #提交到版本库
### http协议

- **git remote add origin**   #关联一个远程库，使用命令git 
- **git clone 线上仓库地址**
#将线上仓库克隆到本地
- **git push**   #提交到线上仓库
- **git push -u origin master**  #本地的master分支推送到origin主机，同时指定origin为默认主机，后面就可以不加任何参数使用git push了
- **git pull**   #将线上仓库内容拉取到本地
- ### ssh协议
- **安装openssh**
- **ssh-keygen -t rsa -C "邮箱"**     #ssh创建公私钥对文件
- 将公匙添加到GitHub中ssh，之后步骤与前面一样
- ==修改提交方式为ssh，地址也为ssh模式下的地址==
- ### 分支学习
- **git branch**  #查看分支
- **git branch 名称**  #创建分支
- **git checkout 名称**    #切换分支
- **git merge 要合并的分支名称**  #合并分支
- **git branch -d 分支名**     #删除分支（记得退出要删除的分支)
- ### 设定规则
- 新建一个名为**.gitignore** 的文件，在文件中声明当前目录的规则
- ###常见规则写法
1. **/name/**   #过滤掉整个文件夹

2. ***.zip**     #过滤掉所有.zip文件

3. **/mtk/do.c**     #过滤掉某个具体文件

4. **!index.php**     #不过滤具体某个文件

5. **#** 开头的是注释

   ## 第二，三天的学习笔记

   > java核心机制：Java虚拟机  JVM(跨平台)
   > 垃圾收集机制  GC
   > -JDK  开发工具包 > JDK  > 运行环境  >JVM  虚拟机
   ---
   # java基础
   > 注释
   > - //单行注释
   > - /*   */多行注释
   > - /** * */   文档注释（Java特有）
   > - **System.out.==print==("")**  //输出（不换行）
   - **System.out.==println==("")**
     //输出（换行）
   > - \n  换行
   > - \t  制造空格
   - 关键字：特有的单词并定义好了含义，（所有字母都小写）
   - 保留字：可能后来被作为关键字的单词
   ---
   - 整数类型
   > - byte  范围 -128~127
   > - short 范围 -2^15-2^15-1
   > - int
   > - long  范围最大 
   >
   > >  long i = 3==l==（long特有的赋值方式）
   - 浮点型
   > - float 单精度 7位有效数字
   > >  float a = 1.22==f==  赋值时，数后跟字母f
   > >
   > >  - double 双精度  16位有效数字
   - ==数据类型大的不能向小的转换==
   - 字符类型 char
   - 布尔类型 Boolean 
   > 不能用0，1表示，只能用ture，false
   - 除以上8个基本数据类型，其余都为引用类型
   ---
   - **引用类型在初始化时都可以赋值为null**
   - 字符串 **string** 
   - 基本数据类型转换
   > - byte,short,char之间不会相互转换，他们三者计算时转换为int类型
   ```
   System.out.print(4+4+"hello");  //输出：8hello
   System.out.print("hello"+4+4); //输出：hello44
   System.out.print('a'+1+"hello"); //输出: 98hello
   System.out.print("hello"+'a'+1);//输出：helloa1
   ```
   - 强制转换数据类型
   > - a = (要转换成的数据类型)b     
   - ++或--在变量之前，先对变量运算后，再取变量的值，在变量之后，先取变量的值再运算
   > - a=2; b=++a;    结果：**a=3，b=3**
   > -  a=2; b=a++;    结果：**a=3,b=2**
   - 字符串与其他数据相加时，实际是其他数据转换为字符串，做字符串拼接
   - char 用'' ,只能放一个元素，**可以与数字相加减**
   - string 用" ",可以放0到多个元素，**只能与数字拼接**
   - **字符串可以用+=，就是字符穿的拼接**
   - ==变量参与运算时，会将变量转换为一个长度更长的变量，然后进行运算==
   - ==使用扩展运算符(+=,*=)时,变量在参与运算时会把结果自动强制转换为当前的变量类型==

   > - int i = 1; i*=0.1  结果为：0

> An awesome project.
>
> 
>
> >>>>>> 8a131dc... myblogs first commit

