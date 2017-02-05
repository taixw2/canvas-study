## Canvas自身提供的元素属性

|属性|描述|取值|
|-|:-:|:-:|
|width|绘画面宽度，默认值为：300，如果在css中定义了元素宽度，绘画面大小不变，拉伸绘画面为css中定义的宽度|非负整数|
|height|绘画面高度，默认值：150，拉伸规则与width一样|非负整数|

## Canvas自身提供的方法
|属性|描述|参数|
|-|:-:|:-:|
|getContext(type)|返回绘画面环境对象，每个canvas均有一个环境对象，并且每个环境对象都与一个canvas关联|所穿件的绘画环境的类型：2d|
|toDataURL(type,quality)|生成canvas的数据地址，可以用于img的src属性中|第一个参数：图像类型，image/png等，第二个参数设置图像质量0~1.0的值|
|toBlob(callback,type,args...)|生成canvas元素的blob|第一个参数：回调函数，第二个参数：图像类型，第三个参数：图像质量|
