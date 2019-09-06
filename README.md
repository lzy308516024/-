# -
闲来无事，做个转盘抽奖玩玩，😍

###  技术总结：
 
   实现转盘主要是依赖了 CSS3的动画、和过渡。
   tansform:rotate(xxdeg)  旋转多少度。
   ##transition:property duration timing-function delay;

   		#transition-property:none|all|property;
   		 	none:没有属性获得过度效果
   		 	all：所有属性都将获得过度效果
   		 	property：定义应用过渡效果的 CSS 属性名称列表，列表以逗号分隔。

   		#transition-duration: time;


   		#transition-timing-function:linear|ease|ease-in|ease-out|ease-in-out|cubic-bezier(n,n,n,n);
			linear：规定以相同速度开始至结束的过渡效果
			ease：规定慢速开始，然后变快，然后慢速结束的过渡效果
			ease-in：规定以慢速开始的过渡效果
			ease-out：规定以慢速结束的过渡效果
			ease-in-out：规定以慢速开始和结束的过渡效果
			cubic-bezier(n,n,n,n):在 cubic-bezier 函数中定义自己的值。可能的值是 0 至 1 之间的数值.


 		#transition-delay:time 指定秒或毫秒数之前要等待切换效果开始