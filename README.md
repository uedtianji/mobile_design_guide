移动页面设计指南
=======
本指南只针对现在流行的交互单页设计，且以微信中浏览为准，分辨率上以iphone手机为基准。  
![交互单页](https://raw.githubusercontent.com/uedtianji/mobile_design_guide/master/img/1.gif)  
上图就是交互单页的例子，这种页面具有以下特点：  
>1.内容分为多个单页。  
>2.每个单页都充满整个屏幕。  
>3.单页之间依靠上下滑进行页面间的转换。  


根据上面的特点，在设计页面时需注意：  

1.尺寸  
iphone5的页面设计尺寸为```640X1136```,iphone4的页面设计尺寸为```640X960```;  
为保证iphone5下面可以正常充满屏幕，需要按照```640x1136```设计。  
由于在单页中上滑为翻页，所以设计图中的重要内容不能超出屏幕范围，超出的部分将无法显示；屏幕中还有系统任务栏，微信标题栏，两个共计 128px(两倍大小)，所以设计图中的重要内容不能超过```832px```(960-128)。  
例如下面的设计图中的重要内容-奖项设置，超过了832px,虽然在iphone5中显示正常，在iphone4中无法显示完整。  
####iphone5  
![iphone5](https://raw.githubusercontent.com/uedtianji/mobile_design_guide/master/img/gaoduiphone5.jpg)  
####iphone4  
![iphone4](https://raw.githubusercontent.com/uedtianji/mobile_design_guide/master/img/gaoduiphone4.jpg)  


2.输入框  
如果设计中出现了输入框，例如让用户输入姓名、电话之类的信息，输入框的位置要在设计图的顶部，否则输入框会被弹出的键盘遮住导致无法输入。  
例如：  
![iphone5](https://raw.githubusercontent.com/uedtianji/mobile_design_guide/master/img/shuru.jpg)    
将输入框移至顶部后可以正常输入。  
![iphone5](https://raw.githubusercontent.com/uedtianji/mobile_design_guide/master/img/shurur.jpg)    
