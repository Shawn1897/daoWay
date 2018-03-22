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
    还有，在用swiper做轮播的时候，要对图片进行设置，否则会出现些异常。像当前的“到位”就可以用
    background (url)
    当前进度:
        到首页二级菜单。今天争取搞完首页

    不足:
        轮播出现了点异常
    是否以解决:
        以解决

day07
    当前进度:
    首页与服务商静态页面已完成

    不足：
    首页头部下滑时的展示

    是否解决:
    通过查阅文档与组长的帮忙以解决问题

