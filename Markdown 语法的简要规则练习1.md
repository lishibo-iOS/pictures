# Markdown 语法的简要规则

# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题

#### 无序列表
* 1
* 2
- 1
- 2

#### 有序列表
1. 1111
2. 2222
3. 3333

> 这里是引用

要注意符号和文本间的空格

#### 插入链接

[Baidu](https://www.baidu.com)

#### 插入图片

![Mou icon](http://mouapp.com/Mou_128.png)

**粗体**

*斜体*

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

	NSMutableAttributedString *text3 = [[NSMutableAttributedString alloc] initWithString:self.lectureCreateTime];
	text3.color = [UIColor lightGrayColor];
	text3.font = [UIFont systemFontOfSize:12.];
	text3.alignment = NSTextAlignmentRight;
	YYTextContainer *container3 = [YYTextContainer containerWithSize:CGSizeMake(Lecture_CreateDate_Label_Width, MAXFLOAT)];
    self.createDateLabelLayout = [YYTextLayout
     layoutWithContainer:container3 text:text3];

***


