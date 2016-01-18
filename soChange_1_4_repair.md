1,为了避免歧义，将参数名称botLast改为botPrev
2,添加了一个新参数：thumbOverEvent，
由于之前的示例只能是默认鼠标经过时延迟触发事件，鼠标点击直接触发切换事件，
修改后，将这个动作交给参数设置，
即thumbOverEvent为true时，开启鼠标经过事件，
否则关闭此事件，默认为true