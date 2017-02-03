# css-selector-priority
a demo to desc the priority of css selector

# demo1
根据html引入样式的方式可以把样式分为三种，外部样式、内部样式和内联样式。
一般情况下，内联样式的优先级高于内部样式和外部样式，而对于内部样式和外部样式，后面的样式将覆盖前面的样式；

# demo2 and demo3
  对于同一种样式（eg内部样式），根据css选择器的不同，样式优先级不同，ID 选择器的优先级权值为 100；
  Class 类选择器的优先级权值为 10；
  HTML 标签选择器的优先级权值为 1；

# demo4
   继承的CSS 样式不如后来指定的CSS 样式；

# conclusion
CSS 优先级法则：
    1.选择器都有一个权值，权值越大越优先；
         （1）内联样式表的权值最高 1000；
         （2）ID 选择器的权值为 100
         （3）Class 类选择器的权值为 10
         （4）HTML 标签选择器的权值为 1
    2.当权值相等时，后出现的样式表设置要优于先出现的样式表设置；
    3.创作者的规则高于浏览者：即网页编写者设置的CSS 样式的优先权高于浏览器所设置的样式；
    4.继承的CSS 样式不如后来指定的CSS 样式；
    5.在同一组属性设置中标有“!important”规则的优先级最大；