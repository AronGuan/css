1. 2-col-fixed:  
固定布局，关键部分  
        body {
         text-align: center; 
         min-width: 760px;
        }   
        
        #wrapper {
          width: 720px; 
          margin: 0 auto; 
          text-align: left; 
        } //外部
          
        #content { 
          width: 520px;
          float: right; 
        } //内部用浮动
        
        #mainNav { 
          width: 180px; 
          float: left; 
        } 
        
        #footer { 
          clear: both; 
        }   
2. centering-negative-margin:  
整体居中 除了常见的`margin: 0 auto; `  
也可以以下这种方式
        #wrapper{
          position:relative;
          left:50%;
	      width:720px;
          margin-left:-360px;
        }
3. 固定宽度意味着使用width: px方式，  而流动宽度使用width: %方式，更加可以适应浏览器。  
一般%>em>px方式