参数和使用上无变化，
整体修改了插件参数的写入模式，
去除了可能污染全局的settings设置和var $sG = $.soChangeLong;
将参数及操作全部封装在
$.fn.extend({
> "soChange": function(o){

> }
})
达到真正的完整封装，避免插件在部分应用下的冲突问题