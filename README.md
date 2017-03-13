# TaoBao_nianhuo
###学习大漠老师 年货节作品 html5分析
#### css选择器<br>
```css

.music input[type=checkbox]

/*checkbox 选中的时候操作统计兄弟*/
.dragon-play .music input[type="checkbox"]:checked+label:before
/*not的使用*/
.weui_cells_access .weui_cell:not(.no_access):active

```
#### 添加animation的技巧<br>
```css
/*多个动画*/
animation: lihua .2s steps(2) infinite,fadeOut .2s linear 6s both;

/*单独设置animation名称*/
.dragon-playing.is-animation{
             animation: fadein 1s ease both;
         }
         .dragon-playing.is-animation .dragon{
             animation-duration: 4s;
             /*代替ease ease-in  ease-out */
             animation-timing-function: steps(10) ;
             animation-iteration-count: infinite;
         }
         .dragon-playing.is-animation .dragon.dragon1{
             animation-name: dragon1;
         }
         .dragon-playing.is-animation .dragon.dragon2{
             animation-name: dragon2;
         }
         .dragon-playing.is-animation .dragon.dragon3{
             animation-name: dragon3;
         }
         .dragon-playing.is-animation .dragon.dragon4{
             animation-name: dragon3;
         }
         .dragon-playing.is-animation .dragon.dragon5{
             animation-name: dragon3;
         }
```
#### 。。。<br>
第一场景<br>
![image](https://github.com/MengZhaoFly/TaoBao_nianhuo/blob/master/res1.png)
第二场景<br>
![image](https://github.com/MengZhaoFly/TaoBao_nianhuo/blob/master/res2.png)
