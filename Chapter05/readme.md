1. flickr-rollovers:  
实现当鼠标放在图片上，突出人物头部， 运用定位（absolute,relative）  
关键在于`left:-300000px;` ,鼠标放在超链接上`left:50px;` 和运用伪类:hover  
2. horizontal-nav:  
实现用列表形成导航条，关键语句  
        ul li{
        float:left;
        }

3. remote-rollovers:  
实现点击文本，在相应图片的位置凸显出来(方框的方式)，原理：现在相应位置放边框，利用定位  
然后放到联接上时，在设置边框即可。  
	\#pic .rich a .hotspot{
        top:15px;
	    left:95px;
        }
         #pic a:hover .hotspot{
             border:1px solid #fff;
        }
