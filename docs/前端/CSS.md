>### 行级排版上下文
+ Inline Formatting Context (IFC)
+ **只包含行级盒子**的容器会创建一个IFC
+ IFC 内的排版规则
    + 盒子在一行内水平拜访
    + 一行内放不下时，换行显示
    + text-align 决定一行内盒子的水平对齐
    + vertical-align 决定一个盒子在行内的垂直对齐
    + 避开浮动(float)元素


<style>
    strong {
        color: lawngreen;
    }
</style>