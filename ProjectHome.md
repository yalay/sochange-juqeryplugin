Based on jQuery object switching plugin,
Simple Lightweight

基于jQuery的对象切换插件，
简易轻量

所有参数：

$(obj).soChange({ <br />
> thumbObj:null, //导航对象，默认为空<br />
> botPrev:null, //按钮上一个，默认为空<br />
> botNext:null, //按钮下一个。默认为空<br />
> thumbNowClass:'now', //导航对象当前的class,默认为now<br />
> thumbOverEvent:true,//鼠标经过thumbObj时是否切换对象，默认为 true，为false时，只有鼠标点击thumbObj才切换对象<br />
> slideTime:1000, //对象平滑过渡持续时间，默认为1000ms<br />
> autoChange:true, //是否自动切换，默认为true<br />
> clickFalse:true,//导航对象如果有链接，点击是否链接无效，即是否返回return false，默认是return false链接无效，当thumbOverEvent为false时，此项必须为true，否则鼠标点击事件冲突<br />
> overStop:true,//鼠标经过切换对象时，切换对象是否停止切换，并于鼠标离开后重启自动切换，前提是已开启自动切换，默认开启鼠标经过对象停止切换<br />
> changeTime:5000, //对象自动切换时间，默认为5000ms，即5秒<br />
> delayTime:300 //鼠标经过时对象切换迟滞时间，推荐值为300ms<br />
});