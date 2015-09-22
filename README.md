<h1>天猫/地狗滚动导航实例总结</h1>
<h2>1.标准盒子模型边框包含padding和width，当width固定时，若改变padding则border大小跟随变化，width不变
。当width不固定而父元素有固定宽度时，改变padding，border大小不变</h2>
<h2>
#menu {
            position: fixed;
            top: 100px;
            left: 50%;
            margin-left: 400px;
            width: 50px;
        }//让menu紧挨居中元素右侧；
        </h2>
