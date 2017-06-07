# Some records!
# css设置文字不换行
>
> overflow:hidden;
> text-overflow:ellipsis;
> white-space:nowrap;
> width:210px;

# display:flex 兼容
>
> display: -webkit-box;
> display: -webkit-flex;
> display: flex;
> display: -ms-inline-flexbox;
## align-items
-webkit-box-align: center;
-webkit-align-items: center;
align-items: center;

# 设置全局的CSS样式，避免图中的长按弹出菜单与选中文本的行为
>
> a, img {
>   -webkit-touch-callout: none; /* 禁止长按链接与图片弹出菜单 */
> }
> html, body {
    -webkit-user-select: none;   /* 禁止选中文本（如无文本选中需求，此为必选项） */
    user-select: none;
}