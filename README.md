#[点我快速安装脚本](https://nightlyfantasy.github.io/Tieba_Recent_Emoi/Tieba_Recent_Emoi.user.js)

## 作用：贴吧最近使用表情

## 楼中楼最近表情面板绝对水平位置,如果你没用样式优化贴吧，那么该值在451，使用样式后可能导致楼中楼最近表情面板水平位置不对劲，这里可调，数值越大越靠左，可负值，自行调节

### 在脚本开头你可以找到如下设置，请按自己实际更改即可

> //---------------------小白式控制面板，注意请在英文输入法下编辑----------------------------------------------

> lzldivright=451;//楼中楼最近表情面板绝对水平位置,如果你没用样式优化贴吧，那么该值在451，使用样式后可能导致楼中楼最近表情面板水平位置不对劲，这里可调，数值越大越靠左，可负值，自行调节

> Maxwidth = 501;//扑捉最大像素宽度为Maxwidth以内且高度为Maxheight以内的图片[主贴回复框]

> Maxheight = 501; //扑捉最大像素宽度为Maxwidth以内且高度为Maxheight以内的图片[主贴回复框]

> //-------------------小白式控制面板到此结束，以下内容请勿编辑-----------------------------------------------

### 2014.09.12[v1.1] 脚本失效半年因无人使用，博主也搬砖忙没时间使用，所以一直没去修复，知道贴吧吧友反馈希望修复，在此就修复下，修复如下

>					1:更换脚本名称，使用个好听的名字吧

>					2:重建最近表情面板，使用原贴吧表情面板[作娇小处理]

>					3:函数重写，参考了大花猫的脚本[喵~ ＞▽＜]

>					4:博主在火狐34nightly+GM2.2下运行完全正常

>					5:ajax提交也即时更新表情的新旧增减

#### 2013.10.28 增加了楼中楼最近表情功能，可关闭，(小贴士:楼中楼无法使用自定义表情，只能使用static.tieba.baidu.com域名内的表情，也就是度娘自带表情)

#### PS:因为楼中楼表情是附加上去的，未对同一类函数做重用处理，有空改改将函数重用，减少代码量(￣︶￣)↗

#### 关于面板位置需要调节的说明：本人代码水平有限，需要各位自己动手改成自己合适的位置

#### 注意:楼中楼最近表情和主贴回复最近表情是分开保存设置的


## [BUG反馈地址](http://bilili.ml/489.html)