# 电子班务栏操作手册v2.5

程序如有更改，恕不另行通知。

（作者特别提醒：不要更改res文件夹里的任何内容！为使程序发挥功能，请设置开机自启。）

## 一、环境配置

### 1. **Python环境**
   本程序基于Python 3开发。在运行本程序时，请在[Python官网](https://www.python.org/downloads/)下载Python 3.x。
    
```shell
    https://www.python.org/downloads/ 
```

### 2. **本地部署**
获取本程序库：

```shell
git clone https://github.com/Xinyu-Jia/e-bar.git
```

如果您的powershell或cmd报告没有git指令，您可以选择安装git或直接在GitHub界面下载源码文件。

下一步，运行main.pyw文件（代码仅供参考）：

```shell
cd e-bar
python3 ./main.pyw
```


### 3. **开机启动**
   
   为使程序发挥功能，需要设置开机自启。方法：在
   
```shell
   C:\ProgramData\Microsoft\Windows\StartMenu\Programs\StartUp
```

为 `main.pyw` 创建快捷方式。 请放心，程序几乎不会影响电脑运行速度。

## 二、设置界面

### 1. **字体、背景颜色的修改**
   在Ver2.x中，您可以直观地单击选取颜色。

### 2. **可能的U盘盘符** *（非常重要！）*
   您需要观察您的电脑通常分配给U盘的盘符。考虑到不同情况下U盘盘符可能有所不同，程序提供了3个盘符：当“打开U盘”触发后将按照设置里从左到右的顺序依次尝试。成功打开后将停止继续尝试。 示例：如果您的电脑有C、D两个本地磁盘，那不妨设置成E、F、G。设置完请点击右侧“保存”。

### 3. **彩蛋**
   作为二次元lover的作者设置了一个彩蛋，触发方式为右键/长按主页下方版本号。

### 4. **导入/导出设置**
   您可以单击‘导出设置’将当前颜色、标题、U盘盘符等设置导出。

## 三、课表

在主页长按课表方块，会弹出一个txt文档。第1-7行分别对应周一到周日。如果某天没有课程可以留空行。 建议按照示例，一节课用一个字表示，防止显示不开。保存txt后需在设置中重启程序生效。

## 四、倒计时

长按主页倒计时方块可以修改。注意：目标日期必须严格按照xxxx-xx-xx格式书写。

## 五、关于

这个程序由 **@txstmsb(酷安)@爱电脑的昕宇(萝卜头IT论坛)@KZnrain(哔哩哔哩)** 开发。 您可以通过jiaxinyu1108@outlook.com联系TA。 本程序免费开源，严禁用于商业用途。 2024-2-28# e-bar ///
