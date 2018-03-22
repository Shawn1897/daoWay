day06
    在用swiper做轮播图的时候，在处理js逻辑处需要把src路径去掉,如下。带了src轮播图就不能用了
    <script type="text/javascript" >
    window.onload = function () {
        var swiper = new Swiper('.swiper-container', {
            loop:true,
            autoplay:true,
            pagination:{
                el:'.swiper-pagination',
                clickable:true
            }
        });
    }
    当前进度:
        到首页二级菜单。今天争取搞完首页

    不足:
        轮播出现了点异常
    是否以解决:
        以解决

