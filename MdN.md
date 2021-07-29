# MdN
关于Markdown的语法及编辑器Typora使用的学习笔记  

*更新日志:*
*2021/7/29 *: 编辑器下载,常用快捷键 Markdown语法 包括标题,字体,列表,表格,分割线,代码,图片,引用


## 编辑器——Typora
特点：将预览和源代码模式结合，实现所见即所得  
下载地址 https://typora.io/  
建议如下经由 Typora界面-文件-偏好设置-Markdown设置 将拓展语法开启    
![](https://github.com/SValeriey/MdN/blob/main/MdN_Images/%E6%8B%93%E5%B1%95%E8%AF%AD%E6%B3%95.png?raw=true)

### 快捷键收录
*CTRL+L*:	来回切换源代码模式和预览模式  
*CTRL+T*:	预览模式下快速插入表格  
*CTRL+单击链接*:	打开链接  


## Markdown语法

### 标题
标题分六级,需要加对应级别个数的#(井号)并加空格
```markdown
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题
```
效果如下:  
![](https://github.com/SValeriey/MdN/blob/main/MdN_Images/%E6%A0%87%E9%A2%98.png?raw=true)

### 字体
在文本两边分别加单个 *(星号) 包围表示斜体	`*斜体*`; 加两个 *(星号) 包围表示粗体	`**粗体**`'; 三个 *(星号) 表示斜体加粗	`***斜体加粗***`  
在文本两边分别加两个 =(等号) 表示高亮	`==高亮==`  
在文本两边分别加两个 ~(波浪线) 表示删除线		`~~删除线~~`  
在文本两边分别加 ^(指数) 表示上标	`我是^上标^`; 加 ~(波浪线) 表示下标	`我是~下标~`  
以上代码的效果如下:  
![](https://github.com/SValeriey/MdN/blob/main/MdN_Images/%E5%AD%97%E4%BD%93.jpg?raw=true)

### 列表

#### 有序列表
有序列表直接序号加 .(点) 加空格即可,并且回车后会自动添加下一序号
```markdown
1. 一级有序列表
2. 二级有序列表
3. 三级有序列表
4. 四级有序列表
```
效果如下:  
![](https://github.com/SValeriey/MdN/blob/main/MdN_Images/%E6%9C%89%E5%BA%8F%E5%88%97%E8%A1%A8.png?raw=true)

#### 无序列表
无序列表通过 +(加号) 和空格表示,回车后会自动添加同一级列表  
列表级别通过缩进控制,缩进值为Tab键或两个空格  
第二级列表前为空心圆圈,其余为实心  
```markdown
+ + 一级无序列表
	+ 啦啦啦 
	+ 二级无序列表
		+ 三级无序列表
			+ 四级无序列表
```
效果如下:  
![](https://github.com/SValeriey/MdN/blob/main/MdN_Images/%E6%97%A0%E5%BA%8F%E5%88%97%E8%A1%A8.png?raw=true)

### 表格

#### 源代码模式下插入表格
表格第一列为表头,第二列固定为|----|(两竖杠,中间四个连字符)  
每一小格通过 |(竖杠) 隔开  

```markdown
|你好|你好|
|----|----|
|Hello|Hi|
|hello|hi|
```
  
![](https://github.com/SValeriey/MdN/blob/main/MdN_Images/%E8%A1%A8%E6%A0%BC.png?raw=true)

#### 预览模式下插入表格
Typora预览模式下,可以使用快捷键*CTRL+T*快速插入表格  

### 分割线
三个以上 -(连字符) 即表示下划线  
```markdown
---------
```
------------

### 代码

#### 单独代码
文本两边用 `(像单引号但不是,位于键盘Tab键上方,1左方) 包围表示代码  
```markdown
`单独代码`
```
![](https://github.com/SValeriey/MdN/blob/main/MdN_Images/%E5%8D%95%E7%8B%AC%E4%BB%A3%E7%A0%81.png?raw=true)

#### 代码段
用三个 ` 包围起来的文本表示代码段,并且可以指定语言  
![](https://github.com/SValeriey/MdN/blob/main/MdN_Images/%E4%BB%A3%E7%A0%81%E6%AE%B51.png?raw=true)  
![](https://github.com/SValeriey/MdN/blob/main/MdN_Images/%E4%BB%A3%E7%A0%81%E6%AE%B52.png?raw=true)  

### 图片
图片采用`![](文件路径)`的形式  

### 引用
引用使用 >(大于号) 表示,不同数量代表不同级别  
```markdown
> Hello World
> > Hello Markdown
> > > Hello Typora
```
![](https://github.com/SValeriey/MdN/blob/main/MdN_Images/%E5%BC%95%E7%94%A8.png?raw=true)  
