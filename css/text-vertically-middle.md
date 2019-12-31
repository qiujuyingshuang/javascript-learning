### 文字垂直居中的4中方法：

1. 把`height`和`line-height`设置成一样高———知道元素具体高度；
2. `display:flex`配合`align-items:center`——不需要知道元素具体高度，好像元素设置了；
3. `display:table-cell`配合`vertical-align:middle`;
4.  伪元素：::before{
            display: inline-block;
            content: "";
            height: 100%;
            vertical-align: middle;
          }
          ——使用场景：在不知道具体高度时使用；或者给多个元素设置时，每个的高度不一致；

