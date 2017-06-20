#### reset.css
    ```
    html,body,h1,h2,h3,h4,h5,h6,div,dl,dt,dd,ul,ol,li,p,blockquote,pre,hr,figure,table,caption,th,td,form,fieldset,legend,input,button,textarea,menu{margin:0;padding:0;}
    header,footer,section,article,aside,nav,hgroup,address,figure,figcaption,menu,details{display:block;}
    table{border-collapse:collapse;border-spacing:0;}
    caption,th{text-align:left;font-weight:normal;}
    html,body,fieldset,img,iframe,abbr{border:0;}
    i,cite,em,var,address,dfn{font-style:normal;}
    [hidefocus],summary{outline:0;}
    li{list-style:none}
    h1,h2,h3,h4,h5,h6,small{font-size100%;}
    sup,sub{font-size:83%;}
    pre,code,kbd,samp{font-family:inherit;}
    q:before,q:after{content:none;}
    textarea{overflow:auto;resize:none;}
    label,summary{cursor:default;}
    a,button{cursor:pointer;}
    h1,h2,h3,h4,h5,h6,em,strong,b{font-weight:normal;}
    del,ins,u,s,a,a:hover{text-decoration:none;}
    body,textarea,input,button,select,keygen,legend{font:12px/1.14 arial,simsun,color:#333;outline:0;}
    body{background:#fff;}
    a,a:hover{color:#333}

    :-moz-placeholder{color:#ccc !important;}
    ::-moz-placeholder{color:#ccc !important;}
    :-ms-input-placeholder{color:#ccc !important;}
    :-webkit-input-placeholder{color:#ccc,!important;}

    input::-ms-clear{display:none;}
    html{-webkit-tap-highlight-color:rgba(0,0,0,0);}
    ```
#### css

- 背景

    ```
    background-image:url(sprite.png)  
    background-repeat:no-repeat  
    background-postion:1-100px;（可以实现sprite效果）
    background-attachment:fixed|scroll|
    background-position:10px 20px;
        |20% 50%|50% 50%(居中)
        |center center(居中)
        |right(x轴上靠右，其他值默认center)
        |right 10px top 20px;

    background-repeat:no-repeat
    background-origin:默认是padding box
    background-clip:默认是border box
    ```

#### CSS布局

- 块级显示，在文档流
    ```
    display:block|display:inline-block|display:none
    ```

- 定位显示，不在文档流，绝对定位元素以相对定位元素为参考标准
    ```
    position：absolute(脱离文档流)|position:relative（不脱离文档流）
    ```

- 半脱离文档流：
    ```
    float:两列布局，两列自适应布局
    ```

#### 灵活多列自适应布局：
- flex
    水平居中
    ```
    display:flex;
    justify-content:center;
    ```
    垂直居中：
    ```
    display:flex;
    align-items:center;
    ```
    水平垂直居中：
    ```
    display:flex;
    justify-content:center;
    align-items:center;
    ```

#### 3中常用居中方式：
- flex方式
    ```
        display:flex;
        justify-content:center;
        align-items:center;
    ```

- tranform方式
    ```
    position:absolute;
    left:50%;
    right:50%;
    transform:translate(-50%,-50%)
    ```
- inline-block:展示方式是行级元素

    ```
    display:inline-block;
    text-align:center;
    ```




