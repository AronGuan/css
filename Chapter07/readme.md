1. 2-col-fixed:  
�̶����֣��ؼ�����  
        body {
         text-align: center; 
         min-width: 760px;
        }   
        
        #wrapper {
          width: 720px; 
          margin: 0 auto; 
          text-align: left; 
        } //�ⲿ
          
        #content { 
          width: 520px;
          float: right; 
        } //�ڲ��ø���
        
        #mainNav { 
          width: 180px; 
          float: left; 
        } 
        
        #footer { 
          clear: both; 
        }   
2. centering-negative-margin:  
������� ���˳�����`margin: 0 auto; `  
Ҳ�����������ַ�ʽ
        #wrapper{
          position:relative;
          left:50%;
	      width:720px;
          margin-left:-360px;
        }
3. �̶������ζ��ʹ��width: px��ʽ��  ���������ʹ��width: %��ʽ�����ӿ�����Ӧ�������  
һ��%>em>px��ʽ