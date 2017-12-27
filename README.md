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
