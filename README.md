<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>淘宝网 - 淘！我喜欢</title>
	<!-- 引入css文件 -->
	<link rel="stylesheet" href="http://at.alicdn.com/t/font_1476086402_7038264.css">
	<link rel="stylesheet" href="css/resetStyle.css">
	<link rel="stylesheet" href="css/QR.css">
	<link rel="stylesheet" href="css/fixed-nav.css">
	<link rel="stylesheet" href="css/fixed-search.css">
	<link rel="stylesheet" href="css/help.css">
	<link rel="stylesheet" href="css/link.css">
	<link rel="stylesheet" href="css/nav.css">
	<link rel="stylesheet" href="css/often-visit.css">
	<link rel="stylesheet" href="css/trail.css">
	<link rel="stylesheet" href="css/side-nav.css">
	<link rel="stylesheet" href="css/slide1.css">
	<link rel="stylesheet" href="css/slide2.css">
	<link rel="stylesheet" href="css/search.css">
	<link rel="stylesheet" href="css/head.css">
	<link rel="stylesheet" href="css/aliAPP.css">
	<link rel="stylesheet" href="css/side-announcement.css">
	<link rel="stylesheet" href="css/side-recharge.css">
	<link rel="stylesheet" href="css/side-user.css">
	<link rel="stylesheet" href="css/hot-today.css" />
	<link rel="stylesheet" href="css/popularity.css" />
	<link rel="stylesheet" href="css/my-often-visit.css" />
	<link rel="stylesheet" href="css/ifashion.css" />
	<link rel="stylesheet" href="css/quality.css">
    <link rel="stylesheet" href="css/feature.css">
    <link rel="stylesheet" href="css/benefits.css">
    <link rel="stylesheet" href="css/headline.css">
    <link rel="stylesheet" href="css/goodGoods.css">
    <link rel="stylesheet" href="css/goodShop.css">
    <link rel="stylesheet" href="css/hotSale.css">
    <link rel="stylesheet" href="css/hotSaleBottom.css">
    <link rel="stylesheet" href="css/guessYouLike.css">
    <link rel="shortcut icon" href="img/title.ico" type="image/x-icon"/>  
	<style>
		body{ background: #F1F1F1; }
		#search{ width: inherit; height: inherit; background: #fff; }
		#logo,.search,.QR-code{ float: left; }
		#search .search-bg{ width: 1190px; height: 164px; margin: 0 auto; position: relative;  }
		#main{ width: 1190px; margin: 0 auto; }
		#sub-main{ width: 889px; position: relative; float: left; }
		#sub-main #market,#sub-main .slide,#sub-main .good-bag,#sub-main .slide2,#sub-main .hot-today{  float: left; }
		.good-bag{ margin: 10px 0 0 9px; }
		.bag{ position: absolute; left: 0; top: 489px; }
		.bag img{ width: 192px; }
		#side{ float: right; width: 290px; }
		.price-99{ display: inline-block; line-height: 0; margin: 15px 0 0 5px; }
        .startwork-lowprice{ float: left; margin: 16px 0 0 5px; }
        #shunfengbaoyou{ width: 290px; height: 270px; margin-top: 73px; }
        #shunfengbaoyou img{ margin-left: 5px; }
        #shunfengbaoyou h2{ font-size: 14px; font-weight: bold; color: #3C3C3C; margin-bottom: 12px; }
	</style>
</head>
<body>
    <!--固定的右侧导航条-->
    <div class="fixed-nav">
        <ul>
            <li class="often"><a href="javascript:;">我常逛的</a></li>
            <li class="fashion"><a href="javascript:;">时尚</a></li>
            <li class="quality"><a href="javascript:;">品质</a></li>
            <li class="feature"><a href="javascript:;">特色</a></li>
            <li class="benefits"><a href="javascript:;">实惠</a></li>
            <li class="guess-like"><a href="javascript:;">猜你喜欢</a></li>
            <li class="top"><a href="javascript:;"><span class="arrows iconfont icon-jiantoushang"></span><span class="top-span">顶部</span></a></li>
            <li class="couple-back"><a href="javascript:;">反馈</a></li>
            <li class="report"><a href="javascript:;">暴恐举报</a></li>
        </ul>
    </div>
    <!--固定定位的search-->
    <div class="fixed-search">
        <div class="wrap">
            <a class="logo" href="#"><img src="img/fixed-search/1.png" alt=""></a>
            <div class="box-1">
                <form class="form clear" action="#">
                    <div class="choose">
                        <a class="active goods" href="javascript:;">宝贝</a>
                        <a class="Tmall" href="javascript:;">天猫</a>
                        <a class="shop" href="javascript:;">店铺</a>
                    </div>
                    <input class="text" type="text">
                    <span class="wrap-1 iconfont icon-xiangji"><input class="file" type="file"></span>
                    <input class="submit" type="submit" value="搜索">
                </form>
            </div>
            <div class="box-2">
                <form class="form clear" action="#">
                    <div class="choose">
                        <a class="active Tmall" href="javascript:;">天猫</a>
                        <a class="goods" href="javascript:;">宝贝</a>
                        <a class="shop" href="javascript:;">店铺</a>
                    </div>
                    <input class="text text-2" type="text">
                    <input class="submit submit-2" type="submit" value="搜索">
                </form>
            </div>
            <div class="box-3">
                <form class="form clear" action="#">
                    <div class="choose">
                        <a class="active shop" href="javascript:;">店铺</a>
                        <a class="Tmall" href="javascript:;">天猫</a>
                        <a class="goods" href="javascript:;">宝贝</a>
                    </div>
                    <input class="text text-3" type="text">
                    <input class="submit" type="submit" value="搜索">
                </form>
            </div>
        </div>
    </div>
    <!--头部-->
    <div id="header">
        <div id="headwrap">
            <div id="head">
                <ul class="left">
                    <li><a class="active left-1" href="#">亲，请登录</a></li>
                    <li><a class="left-2" href="#">免费注册</a></li>
                    <li><a class="left-3" href="#">手机逛淘宝</a></li>
                </ul>
                <ul class="right">
                    <li class="li-1 my-taobao"><a class="left" href="#">我的淘宝</a><span class="iconfont icon-xiajiantou"></span>
                        <ul>
                            <li><a href="#">已买到的宝贝</a></li>
                            <li><a href="#">我的足迹</a></li>
                        </ul>
                    </li>
                    <li class="li-1 shopping-cart"><span class="left iconfont icon-gouwuche"></span><a href="#">购物车<span class="count">0</span></a><span class="iconfont icon-xiajiantou"></span>
                        <ul></ul>
                    </li>
                    <li class="li-1 favorite"><span class="left iconfont icon-shoucangjia"></span><a href="#">收藏夹</a><span class="iconfont icon-xiajiantou"></span>
                        <ul>
                            <li><a href="#">收藏的宝贝</a></li>
                            <li><a href="#">收藏的店铺</a></li>
                        </ul>
                    </li>
                    <li class="li-1 classify"><a class="left" href="#">商品分类</a><span class="iconfont icon-shuxian"></span>
                    </li>
                    <li class="li-1 seller"><a class="left" href="#">卖家中心</a><span class="iconfont icon-xiajiantou"></span>
                        <ul>
                            <li><a href="#">免费开店</a></li>
                            <li><a href="#">已卖出的宝贝</a></li>
                            <li><a href="#">出售中的宝贝</a></li>
                            <li><a href="#">卖家服务市场</a></li>
                            <li><a href="#">卖家培训中心</a></li>
                            <li><a href="#">体检中心</a></li>
                        </ul>
                    </li>
                    <li class="li-1 service"><a class="left" href="#">联系客服</a><span class="iconfont icon-xiajiantou"></span>
                        <ul>
                            <li><a href="#">消费者客服</a></li>
                            <li><a href="#">卖家客服</a></li>
                        </ul>
                    </li>
                    <!-- 网站导航 -->
                    <li class="nav-li-1 navigation"><span class="left iconfont icon-daohang"></span><a href="#">网站导航</a><span class="iconfont icon-xiajiantou"></span>
                        <ul class="ul-1">
                            <li class="li-2 d-1">
                                <h2 class="h2-1">主题市场</h2>
                                <ul class="ul-2">
                                    <li><a class="hot" href="#">女装</a></li>
                                    <li><a href="#">男装</a></li>
                                    <li><a href="#">内衣</a></li>
                                    <li><a href="#">鞋靴</a></li>
                                    <li><a href="#">箱包</a></li>
                                    <li><a href="#">婴童</a></li>
                                    <li><a class="n" href="#">家电</a></li>
                                    <li><a href="#">数码</a></li>
                                    <li><a href="#">手机</a></li>
                                    <li><a href="#">美妆</a></li>
                                    <li><a href="#">珠宝</a></li>
                                    <li><a href="#">眼镜</a></li>
                                    <li><a href="#">手表</a></li>
                                    <li><a href="#">运动</a></li>
                                    <li><a href="#">户外</a></li>
                                    <li><a href="#">乐器</a></li>
                                    <li><a href="#">游戏</a></li>
                                    <li><a href="#">动漫</a></li>
                                    <li><a href="#">影视</a></li>
                                    <li><a href="#">美食</a></li>
                                    <li><a href="#">鲜花</a></li>
                                    <li><a href="#">宠物</a></li>
                                    <li><a href="#">农资</a></li>
                                    <li><a href="#">房产</a></li>
                                    <li><a href="#">装修</a></li>
                                    <li><a href="#">建材</a></li>
                                    <li><a class="hot" href="#">家居</a></li>
                                    <li><a href="#">百货</a></li>
                                    <li><a href="#">汽车</a></li>
                                    <li><a href="#">二手车</a></li>
                                    <li><a href="#">办公</a></li>
                                    <li><a href="#">企业购</a></li>
                                    <li><a href="#">定制</a></li>
                                    <li><a href="#">教育</a></li>
                                    <li><a href="#">卡券</a></li>
                                    <li><a href="#">本地</a></li>
                                </ul>
                            </li>
                            <li class="li-2 d-2">
                                <h2 class="h2-2">特色市场</h2>
                                <ul class="ul-2 w-2">
                                    <li><a class="n" href="#">iFashion</a></li>
                                    <li><a href="#">爱逛街</a></li>
                                    <li><a href="#">美妆秀</a></li>
                                    <li><a class="hot" href="#">全球购</a></li>
                                    <li><a href="#">腔调</a></li>
                                    <li><a href="#">淘女郎</a></li>
                                    <li><a href="#">星店</a></li>
                                    <li><a href="#">汇吃</a></li>
                                    <li><a href="#">格调</a></li>
                                    <li><a href="#">运动派</a></li>
                                    <li><a class="hot" href="#">极有家</a></li>
                                    <li><a href="#">特色中国</a></li>
                                    <li><a href="#">潮店街</a></li>
                                    <li><a href="#">拍卖会</a></li>
                                    <li><a href="#">淘宝众筹</a></li>
                                    <li><a href="#">中国质造</a></li>
                                    <li><a href="#">质+</a></li>
                                    <li><a href="#">阿里旅行</a></li>
                                    <li><a class="n" href="#">亲宝贝</a></li>
                                    <li><a href="#">闲鱼</a></li>
                                    <li><a href="#">桃花源</a></li>
                                    <li><a href="#">农资</a></li>
                                    <li>
                                        <aclass="hot" href="#">天天特价</a>
                                    </li>
                                    <li><a href="#">清仓</a></li>
                                    <li><a href="#">俪人购</a></li>
                                    <li><a href="#">聚名品</a></li>
                                    <li><a href="#">淘抢购</a></li>
                                    <li><a href="#">生活汇</a></li>
                                    <li><a href="#">全球精选</a></li>
                                    <li><a href="#">非常大牌</a></li>
                                    <li><a href="#">试用</a></li>
                                    <li><a href="#">量贩团</a></li>
                                    <li><a href="#">阿里翻译</a></li>
                                </ul>
                            </li>
                            <li class="li-2 d-3">
                                <h2 class="h2-3">阿里APP</h2>
                                <ul class="ul-2 w-2">
                                    <li><a class="hot" href="#">淘宝</a></li>
                                    <li><a href="#">天猫</a></li>
                                    <li><a href="#">支付宝</a></li>
                                    <li><a href="#">聚划算</a></li>
                                    <li><a href="#">去啊</a></li>
                                    <li><a class="n" href="#">蚂蚁聚宝</a></li>
                                    <li><a href="#">旺信</a></li>
                                    <li><a class="hot" href="#">闲鱼</a></li>
                                    <li><a href="#">阿里钱盾</a></li>
                                    <li><a class="hot" href="#">钉钉</a></li>
                                    <li><a href="#">高德地图</a></li>
                                    <li><a href="#">点点虫</a></li>
                                    <li><a href="#">虾米音乐</a></li>
                                    <li><a href="#">淘宝电影</a></li>
                                    <li><a class="n" href="#">菜鸟裹裹</a></li>
                                    <li><a href="#">爱逛街</a></li>
                                    <li><a href="#">拍卖会</a></li>
                                    <li><a href="#">阿里云</a></li>
                                    <li><a href="#">网商银行</a></li>
                                    <li><a class="n" href="#">阿里邮箱</a></li>
                                    <li><a href="#">阿里众包</a></li>
                                </ul>
                            </li>
                            <li class="li-2 d-4">
                                <h2 class="h2-4">精彩推荐集</h2>
                                <ul class="ul-2 w-3">
                                    <li><a class="hot" href="#">余额宝</a></li>
                                    <li><a href="#">大牌捡宝</a></li>
                                    <li><a href="#">淘公仔</a></li>
                                    <li><a href="#">浏览器</a></li>
                                    <li><a href="#">淘宝香港</a></li>
                                    <li><a href="#">淘宝台湾</a></li>
                                    <li><a href="#">淘宝全球</a></li>
                                    <li><a href="#">淘宝东南亚</a></li>
                                    <li><a href="#">闺蜜淘货</a></li>
                                    <li><a href="#">淘宝视频</a></li>
                                    <li><a href="#">大众评审</a></li>
                                    <li><a class="n" href="#">淘工作</a></li>
                                </ul>
                            </li>
                        </ul>
                    </li>
                </ul>
            </div>
        </div>
    </div>
    <!--search-->
    <div id="search">
        <div class="search-bg">
            <a href="#"><img id="logo" src="img/logo.png"></a>
            <div class="search">
                <p class="title clear">
                    <a class="goods active" href="#" javascript:;>宝贝</a>
                    <a class="tmall" href="#" javascript:;>天猫</a>
                    <a class="store" href="#" javascript:;>店铺</a>
                </p>
                <div class="box-1">
                    <form class="form clear" action="#">
                        <input class="text" type="text">
                        <span class="wrap iconfont icon-xiangji"><input class="file" type="file"></span>
                        <input class="submit" type="submit" value="搜索">
                    </form>
                    <a class="adv-search" href="#">高级搜索</a>
                    <ul class="clear">
                        <li><a class="hot" href="#">男休闲裤</a></li>
                        <li><a class="hot" href="#">月饼礼盒</a></li>
                        <li><a class="hot" href="#">男士T恤</a></li>
                        <li><a href="#">老人机</a></li>
                        <li><a class="hot" href="#">老人手机</a></li>
                        <li><a href="#">笔记本</a></li>
                        <li><a href="#">男装</a></li>
                        <li><a href="#">月饼</a></li>
                        <li><a href="#">男鞋</a></li>
                        <li><a href="#">时尚女包</a></li>
                        <li><a href="#">长袖女T恤</a></li>
                        <li><a href="#">男包</a></li>
                        <li class="more"><a href="#">更多></a></li>
                    </ul>
                </div>
                <div class="box-2">
                    <form class="form clear" action="#">
                        <input class="text text-2" type="text">
                        <input class="submit submit-2" type="submit" value="搜索">
                    </form>
                    <a class="adv-search" href="#">高级搜索</a>
                    <ul class="clear">
                        <li><a href="#">妈妈装</a></li>
                        <li><a class="hot-2" href="#">休闲裤男</a></li>
                        <li><a href="#">女鞋</a></li>
                        <li><a class="hot-2" href="#">笔记本电脑</a></li>
                        <li><a href="#">睡衣</a></li>
                        <li><a href="#">运动鞋</a></li>
                        <li><a class="hot-2" href="#">拉杆箱</a></li>
                        <li><a href="#">月饼</a></li>
                        <li><a class="hot-2" href="#">奶粉</a></li>
                        <li><a href="#">零食</a></li>
                        <li><a href="#">吹风机</a></li>
                        <li><a class="hot-2" href="#">避孕套</a></li>
                        <li><a href="#">双肩包</a></li>
                    </ul>
                </div>
                <div class="box-3">
                    <form class="form clear" action="#">
                        <input class="text text-3" type="text">
                        <input class="submit" type="submit" value="搜索">
                    </form>
                    <a class="adv-search" href="#">高级搜索</a>
                    <ul class="clear">
                        <li><a class="hot" href="#">男休闲裤</a></li>
                        <li><a class="hot" href="#">月饼礼盒</a></li>
                        <li><a class="hot" href="#">男士T恤</a></li>
                        <li><a href="#">老人机</a></li>
                        <li><a class="hot" href="#">老人手机</a></li>
                        <li><a href="#">笔记本</a></li>
                        <li><a href="#">男装</a></li>
                        <li><a href="#">月饼</a></li>
                        <li><a href="#">男鞋</a></li>
                        <li><a href="#">时尚女包</a></li>
                        <li><a href="#">长袖女T恤</a></li>
                        <li><a href="#">男包</a></li>
                        <li class="more"><a href="#">更多></a></li>
                    </ul>
                </div>
            </div>
            <div class="QR-code">
                <li>
                    <a class="close iconfont icon-cha" href="javascript:;"></a>
                </li>
                <li>
                    <a href=""><img src="img/QR-code/1.png" alt=""></a>
                </li>
            </div>
            <div class="nav">
                <ul>
                    <li class="hot"><a href="#">天猫</a></li>
                    <li class="hot"><a href="#">聚划算</a></li>
                    <li class="hot"><a href="#">天猫超市</a></li>
                    <li class="iconfont icon-shuxian"></li>
                    <li><a href="#">淘抢购</a></li>
                    <li><a href="#">电器城</a></li>
                    <li><a href="#">司马拍卖</a></li>
                    <li><a href="#">中国质造</a></li>
                    <li><a href="#">特色中国</a></li>
                    <li class="iconfont icon-shuxian"></li>
                    <li><a href="#">阿里旅行</a></li>
                    <li><a href="#">智能生活</a></li>
                    <li><a href="#">苏宁易购</a></li>
                </ul>
            </div>
        </div>
    </div>
    <!--main-->
    <div id="main">
        <div id="sub-main">
            <div id="market">
                <ul>
                    <li class="title"><a href="#">主题市场</a><a href="#"><span class="iconfont icon-caidan"></span></a></li>
                    <!-- 1 -->
                    <li class="_li">
                        <p class="p1"><span class="zhan1 iconfont icon-fuzhuangneiyi"></span><a href="#">女装</a>/<a href="#">男装</a>/<a href="#">内衣</a><span class="zhan2 iconfont icon-hot"></span><span class="arrow">></span></p>
                        <ul class="right">
                            <li class="__li">
                                <p class="p2"><a class="h3 woman_dress" href="#">女装</a><a class="more" href="#">更多></a></p>
                                <ul>
                                    <li><a href="#">韩版</a></li>
                                    <li><a class="hot" href="#">秋新品</a></li>
                                    <li><a href="#">淘品牌</a></li>
                                    <li><a href="#">90后潮流志</a></li>
                                    <li><a class="hot" href="#">连衣裙</a></li>
                                    <li><a class="hot" href="#">T恤</a></li>
                                    <li><a href="#">裤子</a></li>
                                    <li><a href="#">衬衫</a></li>
                                    <li><a href="#">雪纺/蕾丝衫</a></li>
                                    <li><a class="hot" href="#">半身裙</a></li>
                                    <li><a class="hot" href="#">套装</a></li>
                                    <li><a href="#">卫衣</a></li>
                                    <li><a href="#">高腰裤</a></li>
                                    <li><a href="#">牛仔裤</a></li>
                                    <li><a href="#">短外套</a></li>
                                    <li><a href="#">小西装</a></li>
                                    <li><a class="hot" href="#">风衣</a></li>
                                    <li><a class="hot" href="#">针纺衫</a></li>
                                    <li><a href="#">阔腿裤</a></li>
                                    <li><a href="#">雪纺衫</a></li>
                                    <li><a href="#">伯尼外套</a></li>
                                    <li><a href="#">妈妈装</a></li>
                                    <li><a class="hot" href="#">大码</a></li>
                                    <li><a href="#">好货</a></li>
                                    <li><a class="hot" href="#">红人私服</a></li>
                                    <li><a href="#">甜美风</a></li>
                                    <li><a class="hot" href="#">文艺风</a></li>
                                    <li><a class="hot" href="#">原创单品</a></li>
                                    <li><a href="#">街风头</a></li>
                                    <li><a href="#">通勤风</a></li>
                                    <li><a href="#">大厂直供</a></li>
                                </ul>
                            </li>
                            <li class="__li">
                                <p class="p2"><a class="h3 man_dress" href="#">男装</a><a class="more" href="#">更多></a></p>
                                <ul>
                                    <li><a class="hot" href="#">刺绣夹克潮</a></li>
                                    <li><a class="hot" href="#">焕新</a></li>
                                    <li><a href="#">潮搭</a></li>
                                    <li><a href="#">设计款</a></li>
                                    <li><a href="#">品牌清仓</a></li>
                                    <li><a href="#">质造</a></li>
                                    <li><a class="hot" href="#">短袖T</a></li>
                                    <li><a href="#">条纹T</a></li>
                                    <li><a href="#">纯色T</a></li>
                                    <li><a class="hot" href="#">衬衫</a></li>
                                    <li><a class="hot" href="#">短裤</a></li>
                                    <li><a href="#">休闲裤</a></li>
                                    <li><a href="#">小脚裤</a></li>
                                    <li><a href="#">哈伦裤</a></li>
                                    <li><a href="#">运动裤</a></li>
                                    <li><a href="#">九分裤</a></li>
                                    <li><a class="hot" href="#">夹克</a></li>
                                    <li><a href="#">薄外套</a></li>
                                    <li><a href="#">棒球服</a></li>
                                    <li><a href="#">牛仔外套</a></li>
                                    <li><a href="#">牛仔衬衫</a></li>
                                    <li><a class="hot" href="#">牛仔裤</a></li>
                                    <li><a href="#">卫衣</a></li>
                                    <li><a href="#">情侣装</a></li>
                                    <li><a href="#">运动套装</a></li>
                                    <li><a href="#">西装</a></li>
                                    <li><a href="#">风衣</a></li>
                                    <li><a href="#">Polo</a></li>
                                    <li><a href="#">马甲</a></li>
                                    <li><a href="#">背心</a></li>
                                    <li><a href="#">开衫</a></li>
                                    <li><a class="hot" href="#">大码</a></li>
                                </ul>
                            </li>
                            <li class="__li">
                                <p class="p2"><a class="h3 underwear" href="#">内衣</a><a class="more" href="#">更多></a></p>
                                <ul>
                                    <li><a class="hot" href="#">抢新品</a></li>
                                    <li><a href="#">薄款</a></li>
                                    <li><a class="hot" href="#">性感</a></li>
                                    <li><a href="#">透视</a></li>
                                    <li><a href="#">抹胸</a></li>
                                    <li><a href="#">文胸</a></li>
                                    <li><a class="hot" href="#">发育期</a></li>
                                    <li><a href="#">聚拢</a></li>
                                    <li><a href="#">睡衣</a></li>
                                    <li><a href="#">套装</a></li>
                                    <li><a class="hot" href="#">胖MM</a></li>
                                    <li><a href="#">连体睡衣</a></li>
                                    <li><a href="#">情侣睡衣</a></li>
                                    <li><a href="#">女内裤</a></li>
                                    <li><a class="hot" href="#">男内裤</a></li>
                                    <li><a href="#">丁字裤</a></li>
                                    <li><a href="#">无痕内裤</a></li>
                                    <li><a href="#">丝袜</a></li>
                                    <li><a href="#">棉袜</a></li>
                                    <li><a href="#">打底裤</a></li>
                                    <li><a href="#">美体衣</a></li>
                                </ul>
                            </li>
                            <li class="like">
                            </li>
                        </ul>
                    </li>
                    <!-- 2 -->
                    <li class="_li">
                        <p class="p1"><span class="zhan1 iconfont icon-xiexue"></span><a href="#">鞋靴</a>/<a href="#">箱包</a>/<a href="#">配件</a><span class="arrow">></span></p>
                        <ul class="right">
                            <li class="__li">
                                <p class="p2"><a class="h3 shoe" href="#">鞋靴</a><a class="more" href="#">更多></a></p>
                                <ul>
                                    <li><a class="hot" href="#">女鞋</a></li>
                                    <li><a class="hot" href="#">新品</a></li>
                                    <li><a href="#">夏上新</a></li>
                                    <li><a href="#">懒人一脚蹬</a></li>
                                    <li><a class="hot" href="#">绑带鞋</a></li>
                                    <li><a href="#">中空鞋</a></li>
                                    <li><a href="#">后空鞋</a></li>
                                    <li><a href="#">人字拖</a></li>
                                    <li><a href="#">一字拖</a></li>
                                    <li><a href="#">四季鞋</a></li>
                                    <li><a href="#">松糕厚底</a></li>
                                    <li><a class="hot" href="#">简约平底</a></li>
                                    <li><a href="#">气质高跟</a></li>
                                    <li><a href="#">帆布鞋</a></li>
                                    <li><a href="#">妈妈鞋</a></li>
                                    <li><a class="hot" href="#">男鞋</a></li>
                                    <li><a href="#">休闲鞋</a></li>
                                    <li><a class="hot" href="#">夏季新品</a></li>
                                    <li><a href="#">凉字拖</a></li>
                                    <li><a href="#">网面鞋</a></li>
                                    <li><a href="#">洞洞鞋</a></li>
                                    <li><a class="hot" href="#">豆豆鞋</a></li>
                                    <li><a href="#">运动鞋</a></li>
                                    <li><a href="#">板鞋</a></li>
                                    <li><a href="#">乐福鞋</a></li>
                                    <li><a href="#">正装鞋</a></li>
                                    <li><a href="#">商务鞋</a></li>
                                    <li><a href="#">帆布鞋</a></li>
                                    <li><a href="#">布洛克</a></li>
                                    <li><a href="#">爸爸鞋</a></li>
                                    <li><a href="#">潮鞋</a></li>
                                </ul>
                            </li>
                            <li class="__li">
                                <p class="p2"><a class="h3 bag" href="#">箱包</a><a class="more" href="#">更多></a></p>
                                <ul>
                                    <li><a href="#">女包</a></li>
                                    <li><a href="#">男包</a></li>
                                    <li><a href="#">双肩包</a></li>
                                    <li><a href="#">拉杆箱</a></li>
                                    <li><a href="#">钱包</a></li>
                                    <li><a class="hot" href="#">夏上新</a></li>
                                    <li><a href="#">明星款</a></li>
                                    <li><a href="#">潮包</a></li>
                                    <li><a href="#">大牌</a></li>
                                    <li><a href="#">真皮包</a></li>
                                    <li><a href="#">帆布包</a></li>
                                    <li><a href="#">单肩包</a></li>
                                    <li><a href="#">斜挎包</a></li>
                                    <li><a href="#">手提包</a></li>
                                    <li><a href="#">手拿包</a></li>
                                    <li><a href="#">手机包</a></li>
                                    <li><a href="#">零钱包</a></li>
                                    <li><a href="#">中年包</a></li>
                                    <li><a href="#">迷你包</a></li>
                                    <li><a href="#">大包</a></li>
                                    <li><a href="#">小方包</a></li>
                                    <li><a href="#">贝壳包</a></li>
                                    <li><a href="#">链条包</a></li>
                                    <li><a href="#">欧美风</a></li>
                                    <li><a href="#">日韩风</a></li>
                                    <li><a href="#">学院风</a></li>
                                    <li><a href="#">腰包</a></li>
                                    <li><a href="#">通勤</a></li>
                                    <li><a href="#">休闲</a></li>
                                    <li><a href="#">胸包</a></li>
                                    <li><a href="#">学生箱</a></li>
                                    <li><a href="#">拉杆包</a></li>
                                    <li><a href="#">航空箱</a></li>
                                    <li><a href="#">万向轮</a></li>
                                </ul>
                            </li>
                            <li class="__li">
                                <p class="p2"><a class="h3 part" href="#">配件配饰</a><a class="more" href="#">更多></a></p>
                                <ul>
                                    <li><a class="hot" href="#">帽子</a></li>
                                    <li><a href="#">棒球帽</a></li>
                                    <li><a href="#">贝雷帽</a></li>
                                    <li><a href="#">渔夫帽</a></li>
                                    <li><a class="hot" href="#">鸭舌帽</a></li>
                                    <li><a href="#">围巾</a></li>
                                    <li><a href="#">羊绒</a></li>
                                    <li><a href="#">披肩</a></li>
                                    <li><a href="#">皮带</a></li>
                                    <li><a href="#">头层牛皮</a></li>
                                    <li><a class="hot" href="#">帆布腰包</a></li>
                                    <li><a href="#">假领</a></li>
                                    <li><a href="#">手套</a></li>
                                    <li><a href="#">手链</a></li>
                                    <li><a href="#">DIY饰品</a></li>
                                    <li><a href="#">发饰</a></li>
                                    <li><a href="#">耳饰</a></li>
                                    <li><a class="hot" href="#">戒指</a></li>
                                    <li><a href="#">吊坠</a></li>
                                    <li><a class="hot" href="#">手串</a></li>
                                    <li><a href="#">手镯</a></li>
                                    <li><a href="#">首饰收纳</a></li>
                                    <li><a href="#">小叶紫檀</a></li>
                                    <li><a href="#">胸针</a></li>
                                    <li><a href="#">银饰</a></li>
                                    <li><a class="hot" href="#">水晶饰品</a></li>
                                    <li><a href="#">耳钉</a></li>
                                    <li><a href="#">毛衣链</a></li>
                                    <li><a class="hot" href="#">锁骨链</a></li>
                                    <li><a href="#">新娘头饰</a></li>
                                    <li><a href="#">对戒</a></li>
                                    <li><a href="#">时尚饰品</a></li>
                                </ul>
                            </li>
                            <li class="like">
                            </li>
                        </ul>
                    </li>
                    <!-- 3 -->
                    <li class="_li">
                        <p class="p1"><span class="zhan1 iconfont icon-naiping"></span><a class="a1" href="#">童装玩具</a>/<a href="#">孕产</a>/<a href="#">用</a><span class="arrow">></span></p>
                        <ul class="right">
                            <li class="__li">
                                <p class="p2"><a class="h3 toy" href="#">童装玩具</a><a class="more" href="#">更多></a></p>
                                <ul>
                                    <li><a class="hot" href="#">童装新款</a></li>
                                    <li><a href="#">演出服</a></li>
                                    <li><a href="#">新生儿礼盒</a></li>
                                    <li><a href="#">连衣裙</a></li>
                                    <li><a href="#">打底裤</a></li>
                                    <li><a href="#">男童外套</a></li>
                                    <li><a href="#">男童裤子</a></li>
                                    <li><a href="#">女童外套</a></li>
                                    <li><a href="#">遮阳帽</a></li>
                                    <li><a href="#">亲子装</a></li>
                                    <li><a href="#">童装</a></li>
                                    <li><a href="#">女童鞋春款</a></li>
                                    <li><a href="#">男童鞋春款</a></li>
                                    <li><a href="#">学步鞋</a></li>
                                    <li><a href="#">女童运动鞋</a></li>
                                    <li><a href="#">男同运动鞋</a></li>
                                    <li><a href="#">毛毛虫童鞋</a></li>
                                    <li><a href="#">玩具</a></li>
                                    <li><a href="#">积木</a></li>
                                    <li><a href="#">早教</a></li>
                                    <li><a href="#">儿童自行车</a></li>
                                    <li><a href="#">电动童车</a></li>
                                    <li><a href="#">遥控模型</a></li>
                                    <li><a href="#">户外玩具</a></li>
                                    <li><a href="#">亲子玩具</a></li>
                                    <li><a href="#">学习用品</a></li>
                                    <li><a href="#">描红本</a></li>
                                </ul>
                            </li>
                            <li class="__li">
                                <p class="p2"><a class="h3 pab" href="#">孕产用品</a><a class="more" href="#">更多></a></p>
                                <ul>
                                    <li><a href="#">孕妇春装</a></li>
                                    <li><a href="#">孕妇裤</a></li>
                                    <li><a href="#">月子服</a></li>
                                    <li><a href="#">哺乳文胸</a></li>
                                    <li><a href="#">吸奶器</a></li>
                                    <li><a href="#">孕妇内裤</a></li>
                                    <li><a href="#">连衣裙</a></li>
                                    <li><a href="#">待产包</a></li>
                                    <li><a href="#">孕妇牛仔裤</a></li>
                                    <li><a href="#">孕妇营养品</a></li>
                                    <li><a href="#">防溢乳垫</a></li>
                                    <li><a href="#">美德乐</a></li>
                                    <li><a href="#">十月妈咪</a></li>
                                    <li><a href="#">三洋</a></li>
                                    <li><a href="#">Bravado</a></li>
                                    <li><a href="#">新生儿</a></li>
                                    <li><a href="#">婴儿床</a></li>
                                    <li><a href="#">婴儿推车</a></li>
                                    <li><a href="#">睡袋</a></li>
                                    <li><a href="#">抱被</a></li>
                                    <li><a href="#">隔尿垫</a></li>
                                    <li><a href="#">学步车</a></li>
                                    <li><a href="#">安抚奶嘴</a></li>
                                    <li><a href="#">体温计</a></li>
                                    <li><a href="#">纸尿裤</a></li>
                                    <li><a href="#">花王</a></li>
                                    <li><a href="#">洗衣液</a></li>
                                    <li><a href="#">湿巾</a></li>
                                </ul>
                            </li>
                            <li class="__li">
                                <p class="p2"><a class="h3 make" href="#">奶食</a><a class="more" href="#">更多></a></p>
                                <ul>
                                    <li><a href="#">爱他美</a></li>
                                    <li><a href="#">羊奶粉</a></li>
                                    <li><a href="#">特殊配方奶粉</a></li>
                                    <li><a href="#">喜宝</a></li>
                                    <li><a href="#">惠氏</a></li>
                                    <li><a href="#">启禀</a></li>
                                    <li><a href="#">牛栏</a></li>
                                    <li><a href="#">美素佳儿</a></li>
                                    <li><a href="#">贝因美</a></li>
                                    <li><a href="#">雅培</a></li>
                                    <li><a href="#">美赞成</a></li>
                                    <li><a href="#">可瑞康</a></li>
                                    <li><a href="#">a2</a></li>
                                    <li><a href="#">嘉宝</a></li>
                                    <li><a href="#">美林</a></li>
                                    <li><a href="#">米粉</a></li>
                                    <li><a href="#">泡芙</a></li>
                                    <li><a href="#">溶溶豆</a></li>
                                    <li><a href="#">肉肠</a></li>
                                    <li><a href="#">果肉条</a></li>
                                    <li><a href="#">奶片</a></li>
                                    <li><a href="#">益生菌</a></li>
                                    <li><a href="#">维生素</a></li>
                                    <li><a href="#">钙铁锌</a></li>
                                    <li><a href="#">DHA</a></li>
                                    <li><a href="#">宝宝食用油</a></li>
                                    <li><a href="#">核桃油</a></li>
                                    <li><a href="#">葡萄糖</a></li>
                                    <li><a href="#">宝宝调料</a></li>
                                    <li><a href="#">奶瓶</a></li>
                                    <li><a href="#">餐具</a></li>
                                    <li><a href="#">餐椅</a></li>
                                    <li><a href="#">暖奶器</a></li>
                                </ul>
                            </li>
                            <li class="like">
                            </li>
                        </ul>
                    </li>
                    <!-- 4 -->
                    <li class="_li">
                        <p class="p1"><span class="zhan1 iconfont icon-shouji"></span><a href="#">家电</a>/<a href="#">数码</a>/<a href="#">手机</a><span class="zhan2 iconfont icon-hot"></span><span class="arrow">></span></p>
                        <ul class="right">
                            <li class="__li">
                                <p class="p2"><a class="h3 appliance" href="#">家电</a><a class="more" href="#">更多></a></p>
                                <ul>
                                    <li><a href="#">蒸汽拖把</a></li>
                                    <li><a href="#">除螨仪</a></li>
                                    <li><a class="hot" href="#">净水器</a></li>
                                    <li><a href="#">吸尘器</a></li>
                                    <li><a href="#">扫地机器人</a></li>
                                    <li><a href="#">烤箱</a></li>
                                    <li><a class="hot" href="#">豆浆机</a></li>
                                    <li><a href="#">榨汁机</a></li>
                                    <li><a href="#">电饭煲</a></li>
                                    <li><a class="hot" href="#">足浴盆</a></li>
                                    <li><a href="#">剃须刀</a></li>
                                    <li><a href="#">卷发器</a></li>
                                    <li><a class="hot" href="#">按摩器材</a></li>
                                    <li><a href="#">网络机顶盒</a></li>
                                    <li><a href="#">耳机</a></li>
                                    <li><a href="#">HiFi音箱</a></li>
                                    <li><a class="hot" href="#">蓝牙音箱</a></li>
                                    <li><a href="#">看片神器</a></li>
                                    <li><a href="#">音响</a></li>
                                    <li><a href="#">看戏机</a></li>
                                    <li><a class="hot" href="#">空调</a></li>
                                    <li><a href="#">油烟机</a></li>
                                    <li><a class="hot" href="#">平板电视</a></li>
                                    <li><a href="#">好货</a></li>
                                    <li><a href="#">洗衣机</a></li>
                                    <li><a href="#">冰箱</a></li>
                                    <li><a href="#">厨房大电</a></li>
                                </ul>
                            </li>
                            <li class="__li">
                                <p class="p2"><a class="h3 digital" href="#">数码</a><a class="more" href="#">更多></a></p>
                                <ul>
                                    <li><a class="hot" href="#">苹果ipad</a></li>
                                    <li><a href="#">win10平板</a></li>
                                    <li><a href="#">平板电脑</a></li>
                                    <li><a class="hot" href="#">超级本</a></li>
                                    <li><a href="#">笔记本</a></li>
                                    <li><a href="#">镜头</a></li>
                                    <li><a class="hot" href="#">单反</a></li>
                                    <li><a href="#">卡片机</a></li>
                                    <li><a href="#">摄像机</a></li>
                                    <li><a class="hot" href="#">微单</a></li>
                                    <li><a class="hot" href="#">拍立得</a></li>
                                    <li><a href="#">自拍神器</a></li>
                                    <li><a class="hot" href="#">一体机</a></li>
                                    <li><a href="#">DIY电脑</a></li>
                                    <li><a href="#">自拍</a></li>
                                    <li><a href="#">游戏本</a></li>
                                    <li><a class="hot" ref="#">路由器</a></li>
                                    <li><a href="#">电脑配件</a></li>
                                    <li><a href="#">iPhone壳套</a></li>
                                    <li><a class="hot" href="#">移动电源</a></li>
                                    <li><a href="#">自拍杆</a></li>
                                </ul>
                            </li>
                            <li class="__li">
                                <p class="p2"><a class="h3 phone" href="#">手机</a><a class="more" href="#">更多></a></p>
                                <ul>
                                    <li><a class="hot" href="#">苹果6s plus</a></li>
                                    <li><a class="hot" href="#">苹果6S</a></li>
                                    <li><a href="#">苹果6</a></li>
                                    <li><a href="#">苹果6 plus</a></li>
                                    <li><a class="hot" href="#">荣耀</a></li>
                                    <li><a href="#">苹果5s</a></li>
                                    <li><a href="#">二手iphone</a></li>
                                    <li><a class="hot" href="#">二手回收</a></li>
                                    <li><a href="#">三星</a></li>
                                    <li><a class="hot" href="#">三星s7</a></li>
                                    <li><a href="#">三星s6</a></li>
                                    <li><a href="#">小米</a></li>
                                    <li><a class="hot" href="#">小米5</a></li>
                                    <li><a href="#">红米note3</a></li>
                                    <li><a href="#">红米3</a></li>
                                    <li><a href="#">小米4s</a></li>
                                    <li><a class="hot" href="#">华为</a></li>
                                    <li><a href="#">华为mate8</a></li>
                                    <li><a href="#">魅族</a></li>
                                    <li><a href="#">乐视</a></li>
                                    <li><a class="hot" href="#">vivo Xplay5</a></li>
                                    <li><a href="#">oppo</a></li>
                                </ul>
                            </li>
                            <li class="like">
                            </li>
                        </ul>
                    </li>
                    <!-- 5 -->
                    <li class="_li">
                        <p class="p1"><span class="zhan1 iconfont icon-meizhuang"></span><a class="a1" href="#">美妆</a>/<a href="#">洗护</a>/<a href="#">保健品</a><span class="arrow">></span></p>
                        <ul class="right">
                            <li class="__li">
                                <p class="p2"><a class="h3 beauty" href="#">美妆</a><a class="more" href="#">更多></a></p>
                                <ul>
                                    <li><a class="hot" href="#">面膜</a></li>
                                    <li><a href="#">洁面</a></li>
                                    <li><a class="hot" href="#">防晒</a></li>
                                    <li><a href="#">爽肤水</a></li>
                                    <li><a class="hot" href="#">眼霜</a></li>
                                    <li><a class="hot" href="#">乳液</a></li>
                                    <li><a href="#">面霜</a></li>
                                    <li><a class="hot" href="#">精华</a></li>
                                    <li><a class="hot" href="#">卸妆</a></li>
                                    <li><a href="#">男士护肤</a></li>
                                    <li><a href="#">眼线</a></li>
                                    <li><a href="#">粉底液</a></li>
                                    <li><a href="#">BB霜</a></li>
                                    <li><a class="hot" href="#">隔离</a></li>
                                    <li><a href="#">睫毛膏</a></li>
                                    <li><a href="#">唇膏</a></li>
                                    <li><a class="hot" href="#">腮红</a></li>
                                    <li><a href="#">香水</a></li>
                                    <li><a class="hot" href="#">精油</a></li>
                                    <li><a href="#">身体护理</a></li>
                                    <li><a href="#">丰胸</a></li>
                                    <li><a class="hot" href="#">纤体</a></li>
                                    <li><a href="#">脱毛</a></li>
                                    <li><a class="hot" href="#">海外直邮</a></li>
                                </ul>
                            </li>
                            <li class="__li">
                                <p class="p2"><a class="h3 cleaning" href="#">洗护</a><a class="more" href="#">更多></a></p>
                                <ul>
                                    <li><a class="hot" href="#">洗发水</a></li>
                                    <li><a href="#">护发素</a></li>
                                    <li><a href="#">发膜</a></li>
                                    <li><a href="#">头发造型</a></li>
                                    <li><a class="hot" href="#">染发膏</a></li>
                                    <li><a href="#">烫发水</a></li>
                                    <li><a href="#">假发</a></li>
                                    <li><a class="hot" href="#">沐浴露</a></li>
                                    <li><a href="#">私处护理</a></li>
                                    <li><a class="hot" href="#">身体乳液</a></li>
                                    <li><a class="hot" href="#">牙膏</a></li>
                                    <li><a href="#">牙刷</a></li>
                                    <li><a href="#">漱口水</a></li>
                                    <li><a href="#">足贴</a></li>
                                    <li><a href="#">洗手液</a></li>
                                    <li><a href="#">卫生巾</a></li>
                                    <li><a class="hot" href="#">成人纸尿裤</a></li>
                                    <li><a href="#">抽纸</a></li>
                                    <li><a href="#">卷纸</a></li>
                                    <li><a href="#">洗衣液</a></li>
                                    <li><a class="hot" href="#">清洁剂</a></li>
                                    <li><a href="#">厨房清洁</a></li>
                                    <li><a href="#">家私/皮具护理</a></li>
                                    <li><a href="#">香薰</a></li>
                                </ul>
                            </li>
                            <li class="__li">
                                <p class="p2"><a class="h3 hcp" href="#">保健品</a><a class="more" href="#">更多></a></p>
                                <ul>
                                    <li><a class="hot" href="#">多维矿物质</a></li>
                                    <li><a href="#">B族维生素</a></li>
                                    <li><a class="hot" href="#">葡萄籽</a></li>
                                    <li><a href="#">辅酶Q10</a></li>
                                    <li><a href="#">消化酶</a></li>
                                    <li><a href="#">软骨素</a></li>
                                    <li><a class="hot" href="#">维生素C</a></li>
                                    <li><a href="#">钙</a></li>
                                    <li><a href="#">大豆异黄酮</a></li>
                                    <li><a href="#">益生菌</a></li>
                                    <li><a class="hot" href="#">氨基葡萄糖</a></li>
                                    <li><a href="#">葡萄籽</a></li>
                                    <li><a href="#">生物素</a></li>
                                    <li><a href="#">玛咖（玛卡）</a></li>
                                    <li><a class="hot" href="#">酵素</a></li>
                                    <li><a href="#">螺旋藻</a></li>
                                    <li><a class="hot" href="#">胶原蛋白</a></li>
                                    <li><a class="hot" href="#">月见草油</a></li>
                                    <li><a href="#">DHA</a></li>
                                    <li><a href="#">蔓越莓</a></li>
                                    <li><a href="#">褪黑素</a></li>
                                    <li><a href="#">锯棕榈</a></li>
                                </ul>
                            </li>
                            <li class="like">
                            </li>
                        </ul>
                    </li>
                    <!-- 6 -->
                    <li class="_li">
                        <p class="p1"><span class="zhan1 iconfont icon-zhubao"></span><a href="#">珠宝</a>/<a href="#">眼镜</a>/<a href="#">手表</a><span class="arrow">></span></p>
                        <ul class="right">
                            <li class="__li">
                                <p class="p2"><a class="h3 jewelry" href="#">珠宝</a><a class="more" href="#">更多></a></p>
                                <ul>
                                    <li><a class="hot" href="#">珠宝特色馆</a></li>
                                    <li><a href="#">和田玉</a></li>
                                    <li><a class="hot" href="#">琥珀蜜蜡</a></li>
                                    <li><a href="#">翡翠手镯</a></li>
                                    <li><a href="#">钻戒</a></li>
                                    <li><a href="#">铂金</a></li>
                                    <li><a href="#">黄金首饰</a></li>
                                    <li><a class="hot" href="#">高端定制</a></li>
                                    <li><a href="#">彩色宝石</a></li>
                                    <li><a href="#">珍珠</a></li>
                                    <li><a href="#">金镶玉</a></li>
                                    <li><a href="#">钻石</a></li>
                                    <li><a href="#">K金首饰</a></li>
                                    <li><a href="#">岫岩玉雕</a></li>
                                    <li><a href="#">和田籽料拍卖</a></li>
                                    <li><a href="#">裸石</a></li>
                                    <li><a class="hot" href="#">翡翠玉石</a></li>
                                    <li><a href="#">一元起拍</a></li>
                                    <li><a href="#">设计师</a></li>
                                    <li><a class="hot" href="#">珠宝首饰</a></li>
                                    <li><a href="#">金条</a></li>
                                    <li><a class="hot" href="#">情侣对戒</a></li>
                                    <li><a href="#">琥珀原石</a></li>
                                    <li><a href="#">老坑冰种拍卖</a></li>
                                </ul>
                            </li>
                            <li class="__li">
                                <p class="p2"><a class="h3 glasses" href="#">眼镜</a><a class="more" href="#">更多></a></p>
                                <ul>
                                    <li><a class="hot" href="#">太阳镜</a></li>
                                    <li><a href="#">眼镜架</a></li>
                                    <li><a class="hot" href="#">3D眼镜</a></li>
                                    <li><a href="#">司机镜</a></li>
                                    <li><a href="#">防辐射眼镜</a></li>
                                    <li><a href="#">老花镜</a></li>
                                    <li><a href="#">儿童镜</a></li>
                                    <li><a href="#">色盲眼镜</a></li>
                                    <li><a class="hot" href="#">无框眼镜</a></li>
                                    <li><a href="#">眼镜片</a></li>
                                    <li><a href="#">依视路</a></li>
                                    <li><a class="hot" href="#">雷朋</a></li>
                                    <li><a href="#">复古眼镜</a></li>
                                    <li><a class="hot" href="#">超轻眼镜</a></li>
                                    <li><a href="#">护目镜</a></li>
                                    <li><a href="#">眼镜配件</a></li>
                                    <li><a class="hot" href="#">滑雪镜</a></li>
                                    <li><a href="#">超耐磨</a></li>
                                    <li><a href="#">GM眼镜</a></li>
                                    <li><a href="#">配镜服务</a></li>
                                </ul>
                            </li>
                            <li class="__li">
                                <p class="p2"><a class="h3 watch" href="#">手表</a><a class="more" href="#">更多></a></p>
                                <ul>
                                    <li><a class="hot" href="#">天梭</a></li>
                                    <li><a href="#">运动表</a></li>
                                    <li><a class="hot" href="#">卡西欧</a></li>
                                    <li><a href="#">国表</a></li>
                                    <li><a href="#">时尚表</a></li>
                                    <li><a class="hot" href="#">女表</a></li>
                                    <li><a href="#">儿童表</a></li>
                                    <li><a class="hot" href="#">学生表</a></li>
                                    <li><a href="#">浪琴</a></li>
                                    <li><a class="hot" href="#">斯沃琪表</a></li>
                                    <li><a href="#">镂空机械表</a></li>
                                    <li><a href="#">皮带表</a></li>
                                    <li><a class="hot" href="#">钢带表</a></li>
                                    <li><a href="#">欧米茄</a></li>
                                    <li><a href="#">电子表</a></li>
                                    <li><a class="hot" href="#">陶瓷表</a></li>
                                    <li><a href="#">瑞士表</a></li>
                                    <li><a href="#">手表放心淘</a></li>
                                    <li><a href="#">日韩腕表</a></li>
                                    <li><a class="hot" href="#">情侣表</a></li>
                                    <li><a href="#">光能表</a></li>
                                    <li><a class="hot" href="#">怀表</a></li>
                                    <li><a href="#">表带</a></li>
                                    <li><a href="#">手表配件</a></li>
                                    <li><a href="#">休闲</a></li>
                                    <li><a class="hot" href="#">精钢</a></li>
                                    <li><a href="#">复古手表</a></li>
                                    <li><a href="#">中性手表</a></li>
                                    <li><a class="hot" href="#">帆布表带</a></li>
                                    <li><a href="#">深度防水</a></li>
                                </ul>
                            </li>
                            <li class="like">
                            </li>
                        </ul>
                    </li>
                    <!-- 7 -->
                    <li class="_li">
                        <p class="p1"><span class="zhan1 iconfont icon-chelun"></span><a href="#">运动</a>/<a href="#">户外</a>/<a href="#">乐器</a><span class="arrow">></span></p>
                        <ul class="right">
                            <li class="__li">
                                <p class="p2"><a class="h3 movement" href="#">运动</a><a class="more" href="#">更多></a></p>
                                <ul>
                                    <li><a class="hot" href="#">AJ1禁穿</a></li>
                                    <li><a href="#">AJ12病倒</a></li>
                                    <li><a href="#">Yeezy 350</a></li>
                                    <li><a href="#">Alpha Bounce</a></li>
                                    <li><a href="#">AJ30</a></li>
                                    <li><a class="hot" href="#">Stan Smith</a></li>
                                    <li><a href="#">大Air皮蓬</a></li>
                                    <li><a class="hot" href="#">KD9</a></li>
                                    <li><a href="#">Kayano23</a></li>
                                    <li><a href="#">Sock Dart</a></li>
                                    <li><a href="#">Hyperdunk</a></li>
                                    <li><a href="#">耐克</a></li>
                                    <li><a href="#">阿迪达斯</a></li>
                                    <li><a href="#">New Balance</a></li>
                                    <li><a class="hot" href="#">亚瑟士</a></li>
                                    <li><a href="#">Under Armour</a></li>
                                    <li><a href="#">匡威</a></li>
                                    <li><a href="#">彪马</a></li>
                                    <li><a href="#">VANS</a></li>
                                    <li><a href="#">锐步</a></li>
                                    <li><a href="#">斯凯奇</a></li>
                                    <li><a href="#">美津浓</a></li>
                                    <li><a href="#">李宁</a></li>
                                    <li><a href="#">跑鞋</a></li>
                                    <li><a href="#">篮球鞋</a></li>
                                    <li><a href="#">复古休闲</a></li>
                                    <li><a href="#">健身</a></li>
                                    <li><a href="#">足球</a></li>
                                </ul>
                            </li>
                            <li class="__li">
                                <p class="p2"><a class="h3 outdoor" href="#">户外</a><a class="more" href="#">更多></a></p>
                                <ul>
                                    <li><a href="#">冲锋衣</a></li>
                                    <li><a class="hot" href="#">登山鞋</a></li>
                                    <li><a class="hot" href="#">钓竿</a></li>
                                    <li><a href="#">鱼线</a></li>
                                    <li><a href="#">鱼线轮</a></li>
                                    <li><a href="#">户外鞋</a></li>
                                    <li><a href="#">登山包</a></li>
                                    <li><a href="#">帐篷</a></li>
                                    <li><a href="#">睡袋</a></li>
                                    <li><a href="#">望远镜</a></li>
                                    <li><a class="hot" href="#">皮肤衣</a></li>
                                    <li><a href="#">速干衣</a></li>
                                    <li><a href="#">速干裤</a></li>
                                    <li><a href="#">手电筒</a></li>
                                    <li><a class="hot" href="#">山地车</a></li>
                                    <li><a href="#">公路车</a></li>
                                    <li><a href="#">骑行服</a></li>
                                    <li><a href="#">护具</a></li>
                                    <li><a class="hot" href="#">军迷用品</a></li>
                                    <li><a href="#">舞蹈体操</a></li>
                                    <li><a class="hot" href="#">羽毛球</a></li>
                                    <li><a class="hot" href="#">游泳</a></li>
                                    <li><a class="hot" href="#">瑜伽</a></li>
                                    <li><a href="#">跑步机</a></li>
                                    <li><a class="hot" href="#">健身器</a></li>
                                    <li><a href="#">烧烤架</a></li>
                                    <li><a href="#">冲锋裤</a></li>
                                    <li><a href="#">单车零件</a></li>
                                    <li><a href="#">骑行装备</a></li>
                                    <li><a href="#">遮阳棚</a></li>
                                    <li><a href="#">户外手表</a></li>
                                </ul>
                            </li>
                            <li class="__li">
                                <p class="p2"><a class="h3 instrument" href="#">乐器</a><a class="more" href="#">更多></a></p>
                                <ul>
                                    <li><a class="hot" href="#">吉他</a></li>
                                    <li><a class="hot" href="#">全新钢琴</a></li>
                                    <li><a href="#">二手钢琴</a></li>
                                    <li><a href="#">电钢琴</a></li>
                                    <li><a href="#">电子琴</a></li>
                                    <li><a class="hot" href="#">萨克斯</a></li>
                                    <li><a href="#">尤克里里</a></li>
                                    <li><a href="#">架子鼓</a></li>
                                    <li><a href="#">小提琴</a></li>
                                    <li><a href="#">口琴</a></li>
                                    <li><a class="hot" href="#">手卷钢琴</a></li>
                                    <li><a class="hot" href="#">古筝</a></li>
                                    <li><a href="#">古琴</a></li>
                                    <li><a href="#">二胡</a></li>
                                    <li><a href="#">葫芦丝</a></li>
                                    <li><a href="#">陶笛</a></li>
                                    <li><a href="#">琵琶</a></li>
                                    <li><a href="#">笛子</a></li>
                                    <li><a href="#">非洲鼓</a></li>
                                    <li><a href="#">贝司</a></li>
                                    <li><a href="#">效果器</a></li>
                                    <li><a class="hot" href="#">节拍器</a></li>
                                    <li><a href="#">电吉他</a></li>
                                    <li><a class="hot" href="#">电箱吉他</a></li>
                                    <li><a href="#">吉他音箱</a></li>
                                    <li><a href="#">电子鼓</a></li>
                                    <li><a class="hot" href="#">智能钢琴</a></li>
                                    <li><a href="#">手风琴</a></li>
                                    <li><a href="#">大提琴</a></li>
                                    <li><a href="#">音频接口</a></li>
                                    <li><a href="#">话筒</a></li>
                                </ul>
                            </li>
                            <li class="like">
                            </li>
                        </ul>
                    </li>
                    <!-- 8 -->
                    <li class="_li">
                        <p class="p1"><span class="zhan1 iconfont icon-youxi"></span><a href="#">游戏</a>/<a href="#">动漫</a>/<a href="#">影视</a><span class="arrow">></span></p>
                        <ul class="right">
                            <li class="__li">
                                <p class="p2"><a class="h3 game" href="#">游戏</a><a class="more" href="#">更多></a></p>
                                <ul>
                                    <li><a href="#">DNF</a></li>
                                    <li><a href="#">梦幻西游</a></li>
                                    <li><a href="#">魔兽</a></li>
                                    <li><a href="#">LOL</a></li>
                                    <li><a href="#">坦克世界</a></li>
                                    <li><a href="#">剑网3</a></li>
                                    <li><a href="#">魔域</a></li>
                                    <li><a href="#">DOTA2</a></li>
                                    <li><a href="#">街头篮球</a></li>
                                    <li><a href="#">CF</a></li>
                                    <li><a href="#">天龙八部</a></li>
                                    <li><a href="#">大话西游2</a></li>
                                    <li><a href="#">三国争霸</a></li>
                                    <li><a href="#">YY</a></li>
                                    <li><a href="#">劲舞团</a></li>
                                    <li><a href="#">倩女幽魂</a></li>
                                    <li><a href="#">天下3</a></li>
                                    <li><a class="hot" href="#">反恐精英</a></li>
                                    <li><a class="hot" href="#">冒险岛</a></li>
                                    <li><a href="#">问道</a></li>
                                    <li><a href="#">逆战</a></li>
                                    <li><a href="#">大唐无双</a></li>
                                    <li><a href="#">征途2</a></li>
                                    <li><a href="#">九阴真经</a></li>
                                    <li><a href="#">龙之谷</a></li>
                                    <li><a href="#">热血江湖</a></li>
                                    <li><a href="#">剑灵</a></li>
                                </ul>
                            </li>
                            <li class="__li">
                                <p class="p2"><a class="h3 cartoon" href="#">动漫</a><a class="more" href="#">更多></a></p>
                                <ul>
                                    <li><a href="#">手办</a></li>
                                    <li><a class="hot" href="#">高达模型</a></li>
                                    <li><a href="#">秦时明月</a></li>
                                    <li><a href="#">大圣归来</a></li>
                                    <li><a href="#">海贼王</a></li>
                                    <li><a href="#">圣斗士</a></li>
                                    <li><a href="#">火影忍者</a></li>
                                    <li><a href="#">LOVELIVE!</a></li>
                                    <li><a href="#">银魂</a></li>
                                    <li><a href="#">进击的巨人</a></li>
                                    <li><a class="hot" href="#">从零开始的异世界生活</a></li>
                                    <li><a href="#">最终幻想</a></li>
                                    <li><a href="#">复仇者联盟</a></li>
                                    <li><a href="#">魔兽世界</a></li>
                                    <li><a href="#">守望先锋</a></li>
                                    <li><a class="hot" href="#">英雄联盟</a></li>
                                    <li><a href="#">剑三</a></li>
                                    <li><a href="#">全职高手</a></li>
                                    <li><a href="#">盗墓笔记</a></li>
                                    <li><a href="#">COS女装</a></li>
                                    <li><a href="#">COS男装</a></li>
                                    <li><a href="#">漫展门票</a></li>
                                    <li><a href="#">在下坂本有何贵干</a></li>
                                </ul>
                            </li>
                            <li class="__li">
                                <p class="p2"><a class="h3 film" href="#">影视</a><a class="more" href="#">更多></a></p>
                                <ul>
                                    <li><a class="hot" href="#">太阳的后裔</a></li>
                                    <li><a href="#">琅琊榜</a></li>
                                    <li><a href="#">太子妃升职记</a></li>
                                    <li><a href="#">哈利波特</a></li>
                                    <li><a href="#">星球大战</a></li>
                                    <li><a href="#">蝙蝠侠</a></li>
                                    <li><a href="#">盗墓笔记</a></li>
                                    <li><a href="#">神探夏洛克</a></li>
                                    <li><a href="#">古剑奇谭</a></li>
                                    <li><a href="#">花千骨</a></li>
                                    <li><a href="#">EXO</a></li>
                                    <li><a class="hot" href="#">欢乐颂</a></li>
                                    <li><a href="#">少女时代</a></li>
                                    <li><a href="#">BIGBANG</a></li>
                                    <li><a class="hot" href="#">TFBOYS</a></li>
                                    <li><a href="#">东方神起</a></li>
                                    <li><a href="#">AKB48</a></li>
                                    <li><a href="#">岚ARASHI</a></li>
                                    <li><a href="#">SHINHWA神话</a></li>
                                </ul>
                            </li>
                            <li class="like">
                            </li>
                        </ul>
                    </li>
                    <!-- 9 -->
                    <li class="_li">
                        <p class="p1"><span class="zhan1 iconfont icon-naicha"></span><a href="#">美食</a>/<a href="#">生鲜</a>/<a href="#">零食</a><span class="arrow">></span></p>
                        <ul class="right">
                            <li class="__li">
                                <p class="p2"><a class="h3 cate" href="#">美食</a><a class="more" href="#">更多></a></p>
                                <ul>
                                    <li><a href="#">麦片</a></li>
                                    <li><a href="#">咖啡</a></li>
                                    <li><a href="#">牛奶</a></li>
                                    <li><a href="#">柚子茶</a></li>
                                    <li><a href="#">酸梅汤</a></li>
                                    <li><a href="#">矿泉水</a></li>
                                    <li><a href="#">酵素</a></li>
                                    <li><a href="#">藕粉</a></li>
                                    <li><a href="#">大米</a></li>
                                    <li><a href="#">橄榄油</a></li>
                                    <li><a href="#">小米</a></li>
                                    <li><a href="#">黄豆</a></li>
                                    <li><a href="#">赤豆</a></li>
                                    <li><a href="#">火腿</a></li>
                                    <li><a href="#">香肠</a></li>
                                    <li><a href="#">木耳</a></li>
                                    <li><a href="#">枸杞</a></li>
                                    <li><a href="#">人参</a></li>
                                    <li><a href="#">石斛</a></li>
                                    <li><a href="#">燕窝</a></li>
                                    <li><a href="#">雪蛤</a></li>
                                    <li><a href="#">蜂蜜</a></li>
                                    <li><a href="#">天麻</a></li>
                                    <li><a href="#">花粉</a></li>
                                    <li><a href="#">铁观音</a></li>
                                    <li><a href="#">红茶</a></li>
                                    <li><a href="#">花草茶</a></li>
                                    <li><a href="#">龙井</a></li>
                                    <li><a href="#">普洱</a></li>
                                    <li><a href="#">黑茶</a></li>
                                    <li><a href="#">鸡尾酒</a></li>
                                    <li><a href="#">红酒</a></li>
                                    <li><a href="#">啤酒</a></li>
                                    <li><a href="#">白酒</a></li>
                                    <li><a href="#">梅酒</a></li>
                                    <li><a href="#">洋酒</a></li>
                                    <li><a href="#">清酒</a></li>
                                    <li><a href="#">滋补酒</a></li>
                                    <li><a href="#">绿茶</a></li>
                                </ul>
                            </li>
                            <li class="__li">
                                <p class="p2"><a class="h3 fresh" href="#">生鲜</a><a class="more" href="#">更多></a></p>
                                <ul>
                                    <li><a class="hot" href="#">樱桃</a></li>
                                    <li><a href="#">海参</a></li>
                                    <li><a href="#">麻辣小龙虾</a></li>
                                    <li><a class="hot" href="#">三文鱼</a></li>
                                    <li><a href="#">牛排</a></li>
                                    <li><a href="#">咸鸭蛋</a></li>
                                    <li><a href="#">土鸡蛋</a></li>
                                    <li><a href="#">奇异果</a></li>
                                    <li><a href="#">土鸡</a></li>
                                    <li><a href="#">芒果</a></li>
                                    <li><a href="#">橙子</a></li>
                                    <li><a href="#">黄秋葵</a></li>
                                    <li><a href="#">苹果</a></li>
                                    <li><a class="hot" href="#">榴莲</a></li>
                                    <li><a href="#">柠檬</a></li>
                                    <li><a href="#">干贝</a></li>
                                    <li><a href="#">大闸蟹</a></li>
                                    <li><a href="#">虾仁</a></li>
                                    <li><a href="#">生蚝</a></li>
                                    <li><a href="#">牛肉</a></li>
                                    <li><a href="#">虾皮</a></li>
                                    <li><a href="#">北极贝</a></li>
                                    <li><a class="hot" href="#">银鳕鱼</a></li>
                                    <li><a href="#">车厘子</a></li>
                                    <li><a href="#">蔬菜</a></li>
                                    <li><a href="#">菠萝蜜</a></li>
                                    <li><a href="#">紫薯</a></li>
                                    <li><a href="#">山竹</a></li>
                                    <li><a href="#">木瓜</a></li>
                                    <li><a href="#">牛油果</a></li>
                                    <li><a href="#">甜虾</a></li>
                                    <li><a href="#">泥螺</a></li>
                                    <li><a href="#">土猪肉</a></li>
                                    <li><a href="#">青蟹</a></li>
                                    <li><a href="#">哈密瓜</a></li>
                                    <li><a href="#">花胶</a></li>
                                </ul>
                            </li>
                            <li class="__li">
                                <p class="p2"><a class="h3 sock" href="#">零食</a><a class="more" href="#">更多></a></p>
                                <ul>
                                    <li><a href="#">山核桃</a></li>
                                    <li><a class="hot" href="#">星空棒棒糖</a></li>
                                    <li><a href="#">碧根果</a></li>
                                    <li><a href="#">巴旦木</a></li>
                                    <li><a href="#">开心果</a></li>
                                    <li><a href="#">夏威夷果</a></li>
                                    <li><a href="#">鸭肉</a></li>
                                    <li><a href="#">话梅糖</a></li>
                                    <li><a href="#">泡泡糖</a></li>
                                    <li><a href="#">薄荷糖</a></li>
                                    <li><a href="#">Kirkland坚果</a></li>
                                    <li><a href="#">牛奶糖</a></li>
                                    <li><a class="hot" href="#">费列罗</a></li>
                                    <li><a href="#">布丁</a></li>
                                    <li><a href="#">果冻</a></li>
                                    <li><a href="#">白色恋人饼干</a></li>
                                    <li><a href="#">甜甜圈</a></li>
                                    <li><a class="hot" href="#">辣条</a></li>
                                    <li><a href="#">蛋条</a></li>
                                    <li><a href="#">椰蓉球</a></li>
                                    <li><a href="#">冻米糖</a></li>
                                    <li><a href="#">饼干</a></li>
                                    <li><a href="#">豆羹</a></li>
                                    <li><a href="#">谷物棒</a></li>
                                    <li><a href="#">软糕</a></li>
                                    <li><a class="hot" href="#">芒果干</a></li>
                                    <li><a href="#">牛肉干</a></li>
                                    <li><a href="#">进口蓝莓干</a></li>
                                    <li><a href="#">葡萄干</a></li>
                                </ul>
                            </li>
                            <li class="like">
                            </li>
                        </ul>
                    </li>
                    <!-- 10 -->
                    <li class="_li">
                        <p class="p1"><span class="zhan1 iconfont icon-xiaoshumiao"></span><a href="#">鲜花</a>/<a href="#">宠物</a>/<a href="#">农资</a><span class="arrow">></span></p>
                        <ul class="right">
                            <li class="__li">
                                <p class="p2"><a class="h3 flower" href="#">鲜花</a><a class="more" href="#">更多></a></p>
                                <ul>
                                    <li><a class="hot" href="#">鲜花速递</a></li>
                                    <li><a class="hot" href="#">多肉植物</a></li>
                                    <li><a href="#">干花</a></li>
                                    <li><a href="#">永生花</a></li>
                                    <li><a href="#">食虫植物</a></li>
                                    <li><a class="hot" href="#">桌面盆栽</a></li>
                                    <li><a href="#">手捧花</a></li>
                                    <li><a href="#">鲜果蓝</a></li>
                                    <li><a href="#">园艺方案</a></li>
                                    <li><a href="#">仿真植物</a></li>
                                    <li><a href="#">仿真蔬果</a></li>
                                    <li><a href="#">开业花篮</a></li>
                                    <li><a class="hot" href="#">花瓶</a></li>
                                    <li><a href="#">绿植同城</a></li>
                                    <li><a href="#">蔬菜种子</a></li>
                                    <li><a href="#">水培花卉</a></li>
                                    <li><a href="#">苔藓景观</a></li>
                                    <li><a href="#">空气凤梨</a></li>
                                    <li><a class="hot" href="#">肥料</a></li>
                                    <li><a href="#">花盆花器</a></li>
                                    <li><a href="#">花卉药剂</a></li>
                                    <li><a class="hot" href="#">营养土</a></li>
                                    <li><a href="#">花卉药剂</a></li>
                                    <li><a href="#">园艺工具</a></li>
                                    <li><a href="#">洒水壶</a></li>
                                    <li><a href="#">花架</a></li>
                                    <li><a href="#">铺面石</a></li>
                                    <li><a href="#">月季</a></li>
                                    <li><a href="#">铁线莲</a></li>
                                </ul>
                            </li>
                            <li class="__li">
                                <p class="p2"><a class="h3 pet" href="#">宠物</a><a class="more" href="#">更多></a></p>
                                <ul>
                                    <li><a class="hot" href="#">狗粮</a></li>
                                    <li><a href="#">宠物服饰</a></li>
                                    <li><a href="#">狗厕所</a></li>
                                    <li><a href="#">宠物窝</a></li>
                                    <li><a href="#">航空箱</a></li>
                                    <li><a href="#">海藻粉</a></li>
                                    <li><a href="#">羊奶粉</a></li>
                                    <li><a href="#">宠物笼</a></li>
                                    <li><a href="#">储粮桶</a></li>
                                    <li><a href="#">剃毛器</a></li>
                                    <li><a href="#">营养膏</a></li>
                                    <li><a href="#">上门服务</a></li>
                                    <li><a href="#">猫砂</a></li>
                                    <li><a href="#">猫粮</a></li>
                                    <li><a href="#">猫爬架</a></li>
                                    <li><a href="#">猫砂盆</a></li>
                                    <li><a href="#">化毛膏</a></li>
                                    <li><a href="#">猫罐头</a></li>
                                    <li><a href="#">喂食器</a></li>
                                    <li><a href="#">猫抓板</a></li>
                                    <li><a href="#">猫玩具</a></li>
                                    <li><a href="#">猫笼</a></li>
                                    <li><a href="#">水草</a></li>
                                    <li><a href="#">水草泥</a></li>
                                    <li><a href="#">沉木</a></li>
                                    <li><a href="#">仿真水草</a></li>
                                    <li><a class="hot" href="#">鱼缸</a></li>
                                    <li><a href="#">氧气泵</a></li>
                                    <li><a href="#">过滤器</a></li>
                                    <li><a href="#">水草灯</a></li>
                                    <li><a href="#">鱼粮</a></li>
                                    <li><a href="#">水质维护</a></li>
                                </ul>
                            </li>
                            <li class="__li">
                                <p class="p2"><a class="h3 amop" href="#">农资</a><a class="more" href="#">更多></a></p>
                                <ul>
                                    <li><a class="hot" href="#">农药</a></li>
                                    <li><a href="#">除草剂</a></li>
                                    <li><a href="#">杀虫剂</a></li>
                                    <li><a href="#">杀菌剂</a></li>
                                    <li><a class="hot" href="#">肥料</a></li>
                                    <li><a href="#">叶面肥</a></li>
                                    <li><a href="#">有机肥</a></li>
                                    <li><a href="#">新型肥料</a></li>
                                    <li><a href="#">氮肥</a></li>
                                    <li><a href="#">磷肥</a></li>
                                    <li><a href="#">钾肥</a></li>
                                    <li><a class="hot" href="#">种子/种苗</a></li>
                                    <li><a href="#">粮油种</a></li>
                                    <li><a href="#">蔬菜种</a></li>
                                    <li><a href="#">果树苗</a></li>
                                    <li><a href="#">食用菌菌种</a></li>
                                    <li><a href="#">动物种苗</a></li>
                                    <li><a class="hot" href="#">饲料</a></li>
                                    <li><a href="#">预混料</a></li>
                                    <li><a href="#">浓缩料</a></li>
                                    <li><a href="#">饲料添加剂</a></li>
                                    <li><a href="#">全价料</a></li>
                                    <li><a class="hot" href="#">农具</a></li>
                                    <li><a class="hot" href="#">农膜</a></li>
                                    <li><a class="hot" href="#">农机</a></li>
                                    <li><a href="#">农配件</a></li>
                                    <li><a class="hot" href="#">畜牧药品/兽药</a></li>
                                    <li><a href="#">化学药</a></li>
                                    <li><a href="#">中兽药</a></li>
                                    <li><a href="#">消毒剂</a></li>
                                    <li><a href="#">驱虫药</a></li>
                                </ul>
                            </li>
                            <li class="like">
                            </li>
                        </ul>
                    </li>
                    <!-- 11 -->
                    <li class="_li">
                        <p class="p1"><span class="zhan1 iconfont icon-zhuangxiu"></span><a href="#">房产</a>/<a href="#">装修</a>/<a href="#">建材</a><span class="arrow">></span></p>
                        <ul class="right">
                            <li class="__li">
                                <p class="p2"><a class="h3 hp" href="#">房产</a><a class="more" href="#">更多></a></p>
                                <ul>
                                    <li><a class="hot" href="#">开发商直营更优惠</a></li>
                                    <li><a href="#">单身公寓</a></li>
                                    <li><a href="#">舒适两房</a></li>
                                    <li><a href="#">阔绰四房</a></li>
                                    <li><a class="hot" href="#">小三房</a></li>
                                    <li><a href="#">土豪豪宅</a></li>
                                    <li><a href="#">花园洋房</a></li>
                                    <li><a href="#">精装修</a></li>
                                    <li><a href="#">住在杭州</a></li>
                                    <li><a href="#">住在广州</a></li>
                                    <li><a href="#">住在北京</a></li>
                                    <li><a href="#">住在上海</a></li>
                                    <li><a href="#">即将开盘</a></li>
                                    <li><a href="#">低首付</a></li>
                                    <li><a href="#">学区房</a></li>
                                    <li><a href="#">优惠好房</a></li>
                                    <li><a href="#">住在深圳</a></li>
                                    <li><a href="#">租房精选</a></li>
                                    <li><a href="#">拎包入住</a></li>
                                    <li><a href="#">二手好房</a></li>
                                    <li><a href="#">住在天津</a></li>
                                    <li><a href="#">低总价</a></li>
                                    <li><a href="#">整租</a></li>
                                    <li><a href="#">合租</a></li>
                                </ul>
                            </li>
                            <li class="__li">
                                <p class="p2"><a class="h3 fitment" href="#">装修</a><a class="more" href="#">更多></a></p>
                                <ul>
                                    <li><a href="#">全包</a></li>
                                    <li><a href="#">半包</a></li>
                                    <li><a href="#">全套设计</a></li>
                                    <li><a href="#">拎包入住</a></li>
                                    <li><a href="#">免费设计</a></li>
                                    <li><a href="#">优质装修公司</a></li>
                                    <li><a class="hot" href="#">家装设计</a></li>
                                    <li><a href="#">样板</a></li>
                                    <li><a href="#">案例</a></li>
                                    <li><a href="#">小户型</a></li>
                                    <li><a href="#">婚房</a></li>
                                    <li><a href="#">旧屋翻新</a></li>
                                    <li><a href="#">美式风</a></li>
                                    <li><a href="#">装修日记</a></li>
                                    <li><a href="#">90平2居</a></li>
                                    <li><a href="#">10万装修</a></li>
                                    <li><a class="hot" href="#">宜家风</a></li>
                                </ul>
                            </li>
                            <li class="__li">
                                <p class="p2"><a class="h3 bm" href="#">建材</a><a class="more" href="#">更多></a></p>
                                <ul>
                                    <li><a href="#">吸顶灯</a></li>
                                    <li><a href="#">台灯</a></li>
                                    <li><a href="#">客厅灯</a></li>
                                    <li><a href="#">LED灯泡</a></li>
                                    <li><a href="#">实木地板</a></li>
                                    <li><a href="#">强化地板</a></li>
                                    <li><a href="#">仿古砖</a></li>
                                    <li><a href="#">花砖</a></li>
                                    <li><a href="#">马赛克</a></li>
                                    <li><a href="#">玻化砖</a></li>
                                    <li><a href="#">浴室柜</a></li>
                                    <li><a href="#">花洒</a></li>
                                    <li><a href="#">智能马桶</a></li>
                                    <li><a href="#">水槽</a></li>
                                    <li><a href="#">台上盆</a></li>
                                    <li><a href="#">毛巾杆</a></li>
                                    <li><a href="#">普通马桶</a></li>
                                    <li><a href="#">龙头</a></li>
                                    <li><a href="#">浴缸</a></li>
                                    <li><a href="#">墙纸</a></li>
                                    <li><a href="#">壁纸</a></li>
                                    <li><a href="#">墙布</a></li>
                                    <li><a href="#">背景墙</a></li>
                                    <li><a href="#">指纹锁</a></li>
                                    <li><a href="#">防盗锁</a></li>
                                    <li><a href="#">监控摄像头</a></li>
                                    <li><a href="#">开关插座</a></li>
                                    <li><a href="#">无线摄像头</a></li>
                                    <li><a href="#">门</a></li>
                                    <li><a href="#">榻榻米</a></li>
                                    <li><a href="#">整体橱柜</a></li>
                                    <li><a href="#">楼梯</a></li>
                                </ul>
                            </li>
                            <li class="like">
                            </li>
                        </ul>
                    </li>
                    <!-- 12 -->
                    <li class="_li">
                        <p class="p1"><span class="zhan1 iconfont icon-shafa"></span><a href="#">家具</a>/<a href="#">家饰</a>/<a href="#">家纺</a><span class="zhan2 iconfont icon-hot"></span><span class="arrow">></span></p>
                        <ul class="right">
                            <li class="__li">
                                <p class="p2"><a class="h3 meuble" href="#">家具</a><a class="more" href="#">更多></a></p>
                                <ul>
                                    <li><a class="hot" href="#">沙发</a></li>
                                    <li><a class="hot" href="#">床</a></li>
                                    <li><a class="hot" href="#">高低床</a></li>
                                    <li><a href="#">餐桌</a></li>
                                    <li><a href="#">床垫</a></li>
                                    <li><a href="#">茶几</a></li>
                                    <li><a href="#">电视柜</a></li>
                                    <li><a href="#">衣柜</a></li>
                                    <li><a href="#">鞋柜</a></li>
                                    <li><a href="#">椅凳</a></li>
                                    <li><a href="#">书桌</a></li>
                                    <li><a href="#">电脑桌</a></li>
                                    <li><a href="#">坐具</a></li>
                                    <li><a href="#">现代简约</a></li>
                                    <li><a href="#">美式家具</a></li>
                                    <li><a href="#">北欧家具</a></li>
                                    <li><a href="#">中式家具</a></li>
                                    <li><a href="#">儿童家具</a></li>
                                    <li><a href="#">真皮沙发</a></li>
                                    <li><a href="#">布艺沙发</a></li>
                                    <li><a href="#">皮床</a></li>
                                    <li><a href="#">实木床</a></li>
                                    <li><a href="#">儿童床</a></li>
                                    <li><a href="#">乳胶床垫</a></li>
                                    <li><a href="#">儿童学习桌</a></li>
                                    <li><a href="#">书架</a></li>
                                    <li><a href="#">花架</a></li>
                                    <li><a href="#">椅子</a></li>
                                    <li><a href="#">电脑椅</a></li>
                                    <li><a href="#">佛山家具</a></li>
                                </ul>
                            </li>
                            <li class="__li">
                                <p class="p2"><a class="h3 hd" href="#">家饰</a><a class="more" href="#">更多></a></p>
                                <ul>
                                    <li><a class="hot" href="#">窗帘</a></li>
                                    <li><a class="hot" href="#">地毯</a></li>
                                    <li><a class="hot" href="#">沙发垫</a></li>
                                    <li><a href="#">十字绣</a></li>
                                    <li><a href="#">桌布</a></li>
                                    <li><a href="#">地垫</a></li>
                                    <li><a href="#">抱枕</a></li>
                                    <li><a href="#">坐垫</a></li>
                                    <li><a href="#">飘窗垫</a></li>
                                    <li><a href="#">门帘</a></li>
                                    <li><a href="#">缝纫机</a></li>
                                    <li><a href="#">洗衣机罩</a></li>
                                    <li><a href="#">卷帘</a></li>
                                    <li><a href="#">珠帘</a></li>
                                    <li><a href="#">沙发巾</a></li>
                                    <li><a href="#">靠垫</a></li>
                                    <li><a href="#">空调罩</a></li>
                                    <li><a href="#">餐桌布</a></li>
                                    <li><a href="#">门垫</a></li>
                                    <li><a href="#">浴室防滑垫</a></li>
                                    <li><a href="#">茶几桌布</a></li>
                                    <li><a href="#">桌垫</a></li>
                                    <li><a class="hot" href="#">装饰画</a></li>
                                    <li><a class="hot" href="#">摆件</a></li>
                                    <li><a href="#">照片墙</a></li>
                                    <li><a href="#">相框</a></li>
                                    <li><a class="hot" href="#">墙贴</a></li>
                                    <li><a href="#">花瓶</a></li>
                                    <li><a href="#">壁纸</a></li>
                                    <li><a href="#">挂钟</a></li>
                                    <li><a href="#">仿真花</a></li>
                                    <li><a href="#">油画</a></li>
                                    <li><a href="#">客厅装饰画</a></li>
                                </ul>
                            </li>
                            <li class="__li">
                                <p class="p2"><a class="h3 ht" href="#">家纺</a><a class="more" href="#">更多></a></p>
                                <ul>
                                    <li><a class="hot" href="#">全棉套件</a></li>
                                    <li><a class="hot" href="#">夏凉被</a></li>
                                    <li><a href="#">草席</a></li>
                                    <li><a href="#">床褥</a></li>
                                    <li><a href="#">U型枕</a></li>
                                    <li><a href="#">蚊帐</a></li>
                                    <li><a href="#">凉席</a></li>
                                    <li><a href="#">天丝套件</a></li>
                                    <li><a href="#">贡缎套件</a></li>
                                    <li><a href="#">提花套件</a></li>
                                    <li><a href="#">婚庆套件</a></li>
                                    <li><a href="#">儿童套件</a></li>
                                    <li><a href="#">空调被</a></li>
                                    <li><a href="#">儿童床品</a></li>
                                    <li><a href="#">麻将凉席</a></li>
                                    <li><a href="#">四件套</a></li>
                                    <li><a href="#">毛巾被</a></li>
                                    <li><a href="#">记忆枕</a></li>
                                    <li><a href="#">老粗布</a></li>
                                    <li><a href="#">床垫</a></li>
                                    <li><a href="#">婚庆床品</a></li>
                                    <li><a href="#">床笠</a></li>
                                    <li><a href="#">蒙古包蚊帐</a></li>
                                    <li><a href="#">空调毯</a></li>
                                    <li><a href="#">枕头</a></li>
                                    <li><a href="#">宫廷蚊帐</a></li>
                                    <li><a href="#">牛皮席</a></li>
                                    <li><a href="#">冰丝席</a></li>
                                    <li><a href="#">竹席</a></li>
                                    <li><a href="#">藤席</a></li>
                                </ul>
                            </li>
                            <li class="like">
                            </li>
                        </ul>
                    </li>
                    <!-- 13 -->
                    <li class="_li">
                        <p class="p1"><span class="zhan1 iconfont icon-icon"></span><a class="a1" href="#">汽车</a>/<a href="#">二手车</a>/<a href="#">用品</a><span class="arrow">></span></p>
                        <ul class="right">
                            <li class="__li">
                                <p class="p2"><a class="h3 car" href="#">汽车</a><a class="more" href="#">更多></a></p>
                                <ul>
                                    <li><a class="hot" href="#">好车底价特卖</a></li>
                                    <li><a class="hot" href="#">贷款买车</a></li>
                                    <li><a href="#">限量特卖</a></li>
                                    <li><a class="hot" href="#">车秒贷</a></li>
                                    <li><a href="#">车码头</a></li>
                                    <li><a class="hot" href="#">轿车</a></li>
                                    <li><a href="#">7座车</a></li>
                                    <li><a href="#">SUV</a></li>
                                    <li><a class="hot" href="#">新能源车</a></li>
                                    <li><a href="#">玛莎拉蒂</a></li>
                                    <li><a href="#">奥迪</a></li>
                                    <li><a href="#">别克</a></li>
                                    <li><a href="#">标致</a></li>
                                    <li><a href="#">日产</a></li>
                                    <li><a href="#">雪铁龙</a></li>
                                    <li><a href="#">本田</a></li>
                                    <li><a href="#">海马</a></li>
                                    <li><a href="#">吉利</a></li>
                                    <li><a href="#">奇瑞</a></li>
                                    <li><a href="#">沃尔沃</a></li>
                                    <li><a class="hot" href="#">加油卡</a></li>
                                    <li><a class="hot" href="#">4S保养</a></li>
                                    <li><a href="#">上门保养</a></li>
                                    <li><a class="hot" href="#">连锁保养</a></li>
                                    <li><a class="hot" href="#">镀晶服务</a></li>
                                    <li><a href="#">洗车卡</a></li>
                                    <li><a href="#">打蜡服务</a></li>
                                    <li><a href="#">钣金喷漆</a></li>
                                    <li><a href="#">空调清洗</a></li>
                                    <li><a href="#">内饰精洗</a></li>
                                </ul>
                            </li>
                            <li class="__li">
                                <p class="p2"><a class="h3 twocar" href="#">二手车</a><a class="more" href="#">更多></a></p>
                                <ul>
                                    <li><a class="hot" href="#">司法车拍卖</a></li>
                                    <li><a class="hot" href="#">公车拍卖</a></li>
                                    <li><a href="#">二手车卖场</a></li>
                                    <li><a href="#">二手车拍卖</a></li>
                                    <li><a href="#">二手车帮卖</a></li>
                                    <li><a class="hot" href="#">车秒拍</a></li>
                                    <li><a class="hot" href="#">大众</a></li>
                                    <li><a href="#">宝马</a></li>
                                    <li><a href="#">奥迪</a></li>
                                    <li><a class="hot" href="#">丰田</a></li>
                                    <li><a href="#">奔驰</a></li>
                                    <li><a href="#">本田</a></li>
                                    <li><a href="#">别克</a></li>
                                    <li><a href="#">福特</a></li>
                                    <li><a href="#">马自达</a></li>
                                    <li><a href="#">雪佛兰</a></li>
                                    <li><a href="#">3万以下</a></li>
                                    <li><a href="#">3-5万</a></li>
                                    <li><a href="#">5-10万</a></li>
                                    <li><a href="#">10-20万</a></li>
                                    <li><a href="#">20-30万</a></li>
                                    <li><a href="#">30-40万</a></li>
                                    <li><a href="#">40万以上</a></li>
                                    <li><a class="hot" href="#">SUV</a></li>
                                    <li><a href="#">MPV</a></li>
                                    <li><a href="#">跑车</a></li>
                                    <li><a href="#">越野车</a></li>
                                    <li><a class="hot" href="#">10万买宝马</a></li>
                                    <li><a class="hot" href="#">卖车送爱疯6s</a></li>
                                    <li><a href="#">特价进口新车</a></li>
                                </ul>
                            </li>
                            <li class="__li">
                                <p class="p2"><a class="h3 thing" href="#">用品</a><a class="more" href="#">更多></a></p>
                                <ul>
                                    <li><a href="#">脚垫</a></li>
                                    <li><a class="hot" href="#">夏季座垫</a></li>
                                    <li><a href="#">后备箱垫</a></li>
                                    <li><a href="#">座套</a></li>
                                    <li><a href="#">安全座椅</a></li>
                                    <li><a href="#">香水</a></li>
                                    <li><a class="hot" href="#">车震床</a></li>
                                    <li><a class="hot" href="#">记录仪</a></li>
                                    <li><a href="#">GPS导航</a></li>
                                    <li><a href="#">车载导航</a></li>
                                    <li><a class="hot" href="#">安全预警仪</a></li>
                                    <li><a class="hot" href="#">后视镜导航</a></li>
                                    <li><a href="#">机油</a></li>
                                    <li><a href="#">便携式导航</a></li>
                                    <li><a href="#">轮胎</a></li>
                                    <li><a class="hot" href="#">贴膜</a></li>
                                    <li><a class="hot" href="#">镀晶</a></li>
                                    <li><a class="hot" href="#">车蜡</a></li>
                                    <li><a href="#">洗车机</a></li>
                                    <li><a class="hot" href="#">车载冰箱</a></li>
                                    <li><a href="#">车载净化器</a></li>
                                    <li><a class="hot" href="#">轮胎报警器</a></li>
                                    <li><a href="#">车充</a></li>
                                    <li><a href="#">氙气灯</a></li>
                                    <li><a href="#">雨刮</a></li>
                                    <li><a href="#">车窗饰条</a></li>
                                    <li><a href="#">车用钥匙包</a></li>
                                    <li><a class="hot" href="#">车挂</a></li>
                                    <li><a href="#">安全锤</a></li>
                                    <li><a href="#">燃油宝</a></li>
                                </ul>
                            </li>
                            <li class="like">
                            </li>
                        </ul>
                    </li>
                    <!-- 14 -->
                    <li class="_li">
                        <p class="p1"><span class="zhan1 iconfont icon-monitor"></span><a class="a2" href="#">办公</a>/<a href="#">DIY</a>/<a href="#">五金电子</a><span class="arrow">></span></p>
                        <ul class="right">
                            <li class="__li">
                                <p class="p2"><a class="h3 office" href="#">办公</a><a class="more" href="#">更多></a></p>
                                <ul>
                                    <li><a href="#">打印机</a></li>
                                    <li><a href="#">一体机</a></li>
                                    <li><a href="#">投影仪</a></li>
                                    <li><a href="#">办公用纸</a></li>
                                    <li><a href="#">点钞机</a></li>
                                    <li><a href="#">硒鼓</a></li>
                                    <li><a href="#">坚果投影仪</a></li>
                                    <li><a href="#">门禁</a></li>
                                    <li><a href="#">保险箱</a></li>
                                    <li><a href="#">八爪鱼</a></li>
                                    <li><a href="#">安防摄像</a></li>
                                    <li><a href="#">无线网卡</a></li>
                                    <li><a href="#">WiFi放大器</a></li>
                                    <li><a href="#">无线呼叫器</a></li>
                                    <li><a href="#">格子间</a></li>
                                    <li><a href="#">电脑桌</a></li>
                                    <li><a href="#">办公椅</a></li>
                                    <li><a href="#">迷你标签机</a></li>
                                    <li><a href="#">理线器</a></li>
                                    <li><a href="#">计算器</a></li>
                                    <li><a href="#">荧光告示贴</a></li>
                                    <li><a href="#">翻译笔</a></li>
                                    <li><a class="hot" href="#">毛笔</a></li>
                                    <li><a href="#">马克笔</a></li>
                                    <li><a href="#">文件收纳</a></li>
                                    <li><a href="#">本册</a></li>
                                    <li><a href="#">书写工具</a></li>
                                    <li><a href="#">文具</a></li>
                                    <li><a class="hot" href="#">画具画材</a></li>
                                </ul>
                            </li>
                            <li class="__li">
                                <p class="p2"><a class="h3 diy" href="#">DIY</a><a class="more" href="#">更多></a></p>
                                <ul>
                                    <li><a class="hot" href="#">纸箱</a></li>
                                    <li><a href="#">飞机盒</a></li>
                                    <li><a href="#">包装胶带</a></li>
                                    <li><a href="#">不干胶</a></li>
                                    <li><a href="#">标签定制</a></li>
                                    <li><a href="#">文化衫</a></li>
                                    <li><a href="#">饰品定制</a></li>
                                    <li><a href="#">汉服定制</a></li>
                                    <li><a href="#">cosplay制服</a></li>
                                    <li><a href="#">吊牌定制</a></li>
                                    <li><a class="hot" href="#">广告扇</a></li>
                                    <li><a href="#">LOGO设计</a></li>
                                    <li><a href="#">平面设计</a></li>
                                    <li><a href="#">马克杯定制</a></li>
                                    <li><a href="#">餐具</a></li>
                                    <li><a href="#">软陶人偶</a></li>
                                    <li><a href="#">拼图定制</a></li>
                                    <li><a href="#">礼品定制</a></li>
                                    <li><a href="#">相册</a></li>
                                    <li><a href="#">笔记本</a></li>
                                    <li><a href="#">钢笔刻字</a></li>
                                    <li><a href="#">手机壳</a></li>
                                    <li><a href="#">照片冲印</a></li>
                                    <li><a href="#">台历</a></li>
                                    <li><a href="#">礼品袋</a></li>
                                    <li><a href="#">抱枕</a></li>
                                    <li><a href="#">iphone壳</a></li>
                                </ul>
                            </li>
                            <li class="__li">
                                <p class="p2"><a class="h3 handware" href="#">五金电子</a><a class="more" href="#">更多></a></p>
                                <ul>
                                    <li><a class="hot" href="#">电子元器件</a></li>
                                    <li><a href="#">万用表</a></li>
                                    <li><a href="#">电动螺丝刀</a></li>
                                    <li><a href="#">管钳子</a></li>
                                    <li><a href="#">电钻</a></li>
                                    <li><a href="#">无尘锯</a></li>
                                    <li><a href="#">电焊机</a></li>
                                    <li><a href="#">角磨机</a></li>
                                    <li><a href="#">切割机</a></li>
                                    <li><a href="#">发电机</a></li>
                                    <li><a href="#">快排阀</a></li>
                                    <li><a href="#">增压泵</a></li>
                                    <li><a href="#">钢珠</a></li>
                                    <li><a href="#">测距仪</a></li>
                                    <li><a href="#">水平仪</a></li>
                                    <li><a href="#">传感器</a></li>
                                    <li><a href="#">电容器</a></li>
                                    <li><a href="#">变压器</a></li>
                                    <li><a href="#">单片机开发板</a></li>
                                    <li><a href="#">智能小车</a></li>
                                    <li><a href="#">机器人套件</a></li>
                                    <li><a href="#">3D打印耗材</a></li>
                                    <li><a href="#">太阳能电池</a></li>
                                    <li><a href="#">GPS</a></li>
                                    <li><a href="#">蓝牙</a></li>
                                    <li><a href="#">WIFI</a></li>
                                    <li><a href="#">LED灯珠</a></li>
                                    <li><a href="#">树莓派</a></li>
                                </ul>
                            </li>
                            <li class="like">
                            </li>
                        </ul>
                    </li>
                    <!-- 15 -->
                    <li class="_li">
                        <p class="p1"><span class="zhan1 iconfont icon-baihuo"></span><a class="a1" href="#">百货</a>/<a href="#">餐厨</a>/<a href="#">家庭保</a><span class="arrow">></span></p>
                        <ul class="right">
                            <li class="__li">
                                <p class="p2"><a class="h3 sears" href="#">百货</a><a class="more" href="#">更多></a></p>
                                <ul>
                                    <li><a class="hot" href="#">遮阳伞</a></li>
                                    <li><a href="#">拖鞋</a></li>
                                    <li><a class="hot" href="#">迷你风扇</a></li>
                                    <li><a href="#">毛巾</a></li>
                                    <li><a href="#">摇扇</a></li>
                                    <li><a href="#">眼罩</a></li>
                                    <li><a href="#">金蛋</a></li>
                                    <li><a class="hot" href="#">礼物</a></li>
                                    <li><a href="#">气球</a></li>
                                    <li><a href="#">喜糖盒</a></li>
                                    <li><a href="#">相册</a></li>
                                    <li><a class="hot" href="#">心机小物</a></li>
                                    <li><a class="hot" href="#">省力拖把</a></li>
                                    <li><a href="#">垃圾袋</a></li>
                                    <li><a href="#">垃圾桶</a></li>
                                    <li><a href="#">干发帽</a></li>
                                    <li><a href="#">晾衣架</a></li>
                                    <li><a href="#">卫生间置物架</a></li>
                                    <li><a href="#">衣架</a></li>
                                    <li><a href="#">化妆包</a></li>
                                    <li><a class="hot" href="#">儿童收纳</a></li>
                                    <li><a href="#">衣柜收纳</a></li>
                                    <li><a href="#">收纳箱</a></li>
                                    <li><a href="#">置物架</a></li>
                                    <li><a href="#">脏衣篮</a></li>
                                </ul>
                            </li>
                            <li class="__li">
                                <p class="p2"><a class="h3 kit" href="#">餐厨</a><a class="more" href="#">更多></a></p>
                                <ul>
                                    <li><a class="hot" href="#">制冰工具</a></li>
                                    <li><a href="#">茶壶</a></li>
                                    <li><a href="#">保温杯</a></li>
                                    <li><a href="#">玻璃杯</a></li>
                                    <li><a href="#">匠人紫砂壶</a></li>
                                    <li><a href="#">马克杯</a></li>
                                    <li><a class="hot" href="#">儿童餐具</a></li>
                                    <li><a href="#">创意餐盘</a></li>
                                    <li><a href="#">吸管杯</a></li>
                                    <li><a href="#">筷子</a></li>
                                    <li><a href="#">碗</a></li>
                                    <li><a href="#">饭盒</a></li>
                                    <li><a class="hot" href="#">滤水壶</a></li>
                                    <li><a href="#">储物罐</a></li>
                                    <li><a class="hot" href="#">全球厨房</a></li>
                                    <li><a href="#">菜板</a></li>
                                    <li><a href="#">刀具</a></li>
                                    <li><a href="#">品牌炒锅</a></li>
                                    <li><a href="#">铸铁锅</a></li>
                                    <li><a href="#">炖汤锅</a></li>
                                    <li><a class="hot" href="#">烘焙</a></li>
                                    <li><a class="hot" href="#">围裙</a></li>
                                    <li><a href="#">洗碗巾</a></li>
                                    <li><a href="#">魔力擦</a></li>
                                    <li><a class="hot" href="#">厨房小工具</a></li>
                                    <li><a href="#">厨房置物架</a></li>
                                    <li><a href="#">围裙</a></li>
                                    <li><a href="#">厨房收纳</a></li>
                                </ul>
                            </li>
                            <li class="__li">
                                <p class="p2"><a class="h3 family" href="#">家庭保健</a><a class="more" href="#">更多></a></p>
                                <ul>
                                    <li><a href="#">计生避孕</a></li>
                                    <li><a href="#">避孕套</a></li>
                                    <li><a href="#">排卵试纸</a></li>
                                    <li><a href="#">听诊</a></li>
                                    <li><a href="#">测温</a></li>
                                    <li><a class="hot" href="#">口罩</a></li>
                                    <li><a href="#">康复器械</a></li>
                                    <li><a href="#">拔罐</a></li>
                                    <li><a href="#">刮痧</a></li>
                                    <li><a href="#">止鼾器</a></li>
                                    <li><a href="#">血糖仪</a></li>
                                    <li><a href="#">急救护理</a></li>
                                    <li><a href="#">病床</a></li>
                                    <li><a href="#">助行器械</a></li>
                                    <li><a href="#">拐杖</a></li>
                                    <li><a class="hot" href="#">轮椅</a></li>
                                    <li><a class="hot" href="#">电子血压计</a></li>
                                </ul>
                            </li>
                            <li class="like">
                            </li>
                        </ul>
                    </li>
                    <!-- 16 -->
                    <li class="_li">
                        <p class="p1"><span class="zhan1 iconfont icon-iconxuexi"></span><a class="a1" href="#">学习</a>/<a href="#">卡券</a>/<a href="#">本地服</a><span class="arrow">></span></p>
                        <ul class="right">
                            <li class="__li">
                                <p class="p2"><a class="h3 study" href="#">学习</a><a class="more" href="#">更多></a></p>
                                <ul>
                                    <li><a class="hot" href="#">考研大纲</a></li>
                                    <li><a class="hot" href="#">会计从业</a></li>
                                    <li><a href="#">新概念</a></li>
                                    <li><a class="hot" href="#">四六级</a></li>
                                    <li><a href="#">雅思托福</a></li>
                                    <li><a href="#">成人学历</a></li>
                                    <li><a class="hot" href="#">专升本</a></li>
                                    <li><a href="#">ps美工技能</a></li>
                                    <li><a class="hot" href="#">考研辅导</a></li>
                                    <li><a class="hot" href="#">外教口语课</a></li>
                                    <li><a href="#">一级建造师</a></li>
                                    <li><a class="hot" href="#">游泳课程</a></li>
                                    <li><a class="hot" href="#">口语一对一</a></li>
                                    <li><a class="hot" href="#">汽车维修</a></li>
                                    <li><a href="#">化妆课程</a></li>
                                    <li><a href="#">电商培训</a></li>
                                    <li><a class="hot" href="#">少儿英语</a></li>
                                    <li><a href="#">公务员考试</a></li>
                                    <li><a class="hot" href="#">中小学辅导</a></li>
                                    <li><a class="hot" href="#">宝宝早教</a></li>
                                    <li><a href="#">健身减肥</a></li>
                                    <li><a href="#">DIY手工</a></li>
                                    <li><a href="#">IOS开发</a></li>
                                    <li><a href="#">JAVA</a></li>
                                </ul>
                            </li>
                            <li class="__li">
                                <p class="p2"><a class="h3 ih" href="#">卡券</a><a class="more" href="#">更多></a></p>
                                <ul>
                                    <li><a class="hot" href="#">超市卡</a></li>
                                    <li><a href="#">沃尔玛</a></li>
                                    <li><a href="#">家乐福</a></li>
                                    <li><a href="#">银泰卡</a></li>
                                    <li><a href="#">面包券</a></li>
                                    <li><a href="#">来伊份券</a></li>
                                    <li><a href="#">粽子券</a></li>
                                    <li><a href="#">熟食/半成品</a></li>
                                    <li><a class="hot" href="#">星巴克</a></li>
                                    <li><a href="#">咖啡</a></li>
                                    <li><a href="#">哈根达斯</a></li>
                                    <li><a href="#">冰淇淋</a></li>
                                    <li><a class="hot" href="#">bigbang演唱会</a></li>
                                    <li><a href="#">罗志祥演唱会</a></li>
                                    <li><a href="#">陈奕迅演唱会</a></li>
                                    <li><a href="#">周杰伦演唱会</a></li>
                                </ul>
                            </li>
                            <li class="__li">
                                <p class="p2"><a class="h3 lc" href="#">本地服务</a><a class="more" href="#">更多></a></p>
                                <ul>
                                    <li><a class="hot" href="#">婚纱摄影</a></li>
                                    <li><a href="#">青岛婚拍</a></li>
                                    <li><a href="#">丽江婚拍</a></li>
                                    <li><a href="#">三亚婚拍</a></li>
                                    <li><a href="#">厦门婚拍</a></li>
                                    <li><a href="#">新娘跟妆</a></li>
                                    <li><a href="#">婚礼司仪</a></li>
                                    <li><a href="#">婚车租赁</a></li>
                                    <li><a href="#">婚礼策划</a></li>
                                    <li><a class="hot" href="#">婚宴预订</a></li>
                                    <li><a href="#">婚纱礼服</a></li>
                                    <li><a href="#">礼服租赁</a></li>
                                    <li><a href="#">家电清洗</a></li>
                                    <li><a class="hot" href="#">家庭保洁</a></li>
                                    <li><a href="#">搬家搬运</a></li>
                                    <li><a href="#">在线洗衣</a></li>
                                    <li><a href="#">上门养车</a></li>
                                    <li><a href="#">跑腿代办</a></li>
                                    <li><a href="#">名企招聘</a></li>
                                    <li><a href="#">上门美甲</a></li>
                                    <li><a href="#">入职体检</a></li>
                                    <li><a href="#">法律咨询</a></li>
                                    <li><a class="hot" href="#">上门按摩</a></li>
                                    <li><a href="#">专业翻译</a></li>
                                </ul>
                            </li>
                            <li class="like">
                            </li>
                        </ul>
                    </li>
                </ul>
            </div>
            <a class="bag" href="#"><img src="img/bag.png"></a>
            <div class="slide">
                <ul class="img">
                    <li>
                        <a href="#"><img src="img/slide1/1.jpg" alt=""></a>
                    </li>
                    <li>
                        <a href="#"><img src="img/slide1/2.jpg" alt=""></a>
                    </li>
                    <li>
                        <a href="#"><img src="img/slide1/3.jpg" alt=""></a>
                    </li>
                    <li>
                        <a href="#"><img src="img/slide1/4.jpg" alt=""></a>
                    </li>
                    <li>
                        <a href="#"><img src="img/slide1/5.jpg" alt=""></a>
                    </li>
                </ul>
                <a class="btnL" href="javascript:;">
                    <</a>
                        <a class="btnR" href="javascript:;">></a>
                        <ul class="btn">
                            <li class="active"></li>
                            <li></li>
                            <li></li>
                            <li></li>
                            <li></li>
                        </ul>
            </div>
            <a class="good-bag" href="#"><img src="img/1.png"></a>
            <div class="slide2">
                <div class="title">
                    <h2>天猫必逛</h2>
                    <p class="intro">热门品牌，天天上天猫！</p>
                    <p class="pos"><span class="num">1</span><span>/6</span></p>
                </div>
                <ul class="img">
                    <li>
                        <!-- 1 -->
                        <a href="#"><img class="img-1 borderR" src="img/slide2/1-1.jpg" alt=""></a>
                        <a href="#"><img class="img-2 borderR borderB" src="img/slide2/1-2.jpg" alt=""></a>
                        <a href="#"><img class="img-2 borderB" src="img/slide2/1-3.jpg" alt=""></a>
                        <a href="#"><img class="img-2  borderR" src="img/slide2/1-4.jpg" alt=""></a>
                        <a href="#"><img class="img-2" src="img/slide2/1-5.jpg" alt=""></a>
                    </li>
                    <li>
                        <!-- 2 -->
                        <a href="#"><img class="img-2 borderR  borderB" src="img/slide2/2-1.jpg" alt=""></a>
                        <a href="#"><img class="img-2 borderR  borderB" src="img/slide2/2-2.jpg" alt=""></a>
                        <a href="#"><img class="img-2 borderB" src="img/slide2/2-3.jpg" alt=""></a>
                        <a href="#"><img class="img-2 borderR" src="img/slide2/2-4.jpg" alt=""></a>
                        <a href="#"><img class="img-2 borderR" src="img/slide2/2-5.jpg" alt=""></a>
                        <a href="#"><img class="img-2" src="img/slide2/2-6.jpg" alt=""></a>
                    </li>
                    <li>
                        <!-- 3 -->
                        <a href="#"><img class="img-2 borderR  borderB" src="img/slide2/3-1.jpg" alt=""></a>
                        <a href="#"><img class="img-2 borderR  borderB" src="img/slide2/3-2.jpg" alt=""></a>
                        <a href="#"><img class="img-2 borderB" src="img/slide2/3-3.jpg" alt=""></a>
                        <a href="#"><img class="img-2 borderR" src="img/slide2/3-4.jpg" alt=""></a>
                        <a href="#"><img class="img-2 borderR" src="img/slide2/3-5.jpg" alt=""></a>
                        <a href="#"><img class="img-2" src="img/slide2/3-6.jpg" alt=""></a>
                    </li>
                    <li>
                        <!-- 4 -->
                        <a href="#"><img class="img-3 borderR  borderB" src="img/slide2/4-1.jpg" alt=""></a>
                        <a href="#"><img class="img-3 borderR  borderB" src="img/slide2/4-2.jpg" alt=""></a>
                        <a href="#"><img class="img-3 borderR  borderB" src="img/slide2/4-3.jpg" alt=""></a>
                        <a href="#"><img class="img-3  borderB" src="img/slide2/4-4.jpg" alt=""></a>
                        <a href="#"><img class="img-3 borderR  borderB" src="img/slide2/4-5.jpg" alt=""></a>
                        <a href="#"><img class="img-3 borderR  borderB" src="img/slide2/4-6.jpg" alt=""></a>
                        <a href="#"><img class="img-3 borderR  borderB" src="img/slide2/4-7.jpg" alt=""></a>
                        <a href="#"><img class="img-3 borderB" src="img/slide2/4-8.jpg" alt=""></a>
                        <a href="#"><img class="img-3 borderR" src="img/slide2/4-9.jpg" alt=""></a>
                        <a href="#"><img class="img-3 borderR" src="img/slide2/4-10.jpg" alt=""></a>
                        <a href="#"><img class="img-3 borderR" src="img/slide2/4-11.jpg" alt=""></a>
                        <a href="#"><img class="img-3" src="img/slide2/4-12.jpg" alt=""></a>
                    </li>
                    <li>
                        <!-- 5 -->
                        <a href="#"><img class="img-4  borderR" src="img/slide2/5-1.jpg" alt=""></a>
                        <a href="#"><img class="img-4" src="img/slide2/5-2.jpg" alt=""></a>
                    </li>
                    <li>
                        <!-- 6 -->
                        <a href="#"><img class="img-4 borderR" src="img/slide2/6-1.png" alt=""></a>
                        <a href="#"><img class="img-4" src="img/slide2/6-2.jpg" alt=""></a>
                    </li>
                </ul>
                <a class="btnL" href="javascript:;">
                    <</a>
                        <a class="btnR" href="javascript:;">></a>
                        <ul class="btn">
                            <li class="active"></li>
                            <li></li>
                            <li></li>
                            <li></li>
                            <li></li>
                            <li></li>
                        </ul>
            </div>
            <div class="hot-today">
                <h3>今日热卖</h3>
                <a href="#"><img src="img/hot-today.png"></a>
            </div>
            <div class="popularity">
                <ul>
                    <li class="li-1">
                        <a href="#">
                            <span class="img-bg"></span>
                            <h2>就爱设计感</h2>
                            <p>我们不平庸</p>
                            <span class="people">人气106215</span>
                        </a>
                    </li>
                    <li class="li-2">
                        <a href="#">
                            <span class="img-bg"></span>
                            <h2>可惜是水瓶</h2>
                            <p>不潮不花钱</p>
                            <span class="people">人气105537</span>
                        </a>
                    </li>
                    <li class="li-3">
                        <a href="#">
                            <span class="img-bg"></span>
                            <h2>韩范小妖精</h2>
                            <p>实力撩获欧巴</p>
                            <span class="people">人气120397</span>
                        </a>
                    </li>
                    <li class="li-4">
                        <a href="#">
                            <span class="img-bg"></span>
                            <h2>名媛贵妇</h2>
                            <p>享受真优雅</p>
                            <span class="people">人气47541</span>
                        </a>
                    </li>
                    <li class="li-5">
                        <a href="#">
                            <span class="img-bg"></span>
                            <h2>复古女郎</h2>
                            <p>上了复古的瘾</p>
                            <span class="people">人气28777</span>
                        </a>
                    </li>
                </ul>
            </div>
            <div class="my-often-visit">
                <h2>我常逛的</h2>
                <a class="more" href="#">更多></a>
                <div class="section section-1">
                    <div class="left">
                        <a class="img-wrap" href="#"><img src="img/often-visit/1.jpg" alt=""></a>
                        <h3>热门TOP</h3>
                        <a href="#">iPhone 6s</a>
                        <a href="#">看片神器</a>
                        <a href="#">自拍杆</a>
                        <a href="#">智能投影仪</a>
                        <a href="#">智能手环</a>
                        <a href="#">智能手表</a>
                        <a href="#">智能路由器</a>
                        <a href="#">智能机器人</a>
                        <a href="#">制氧器</a>
                    </div>
                    <div class="right">
                        <a class="a-1" href="#"><img src="img/often-visit/1-1.jpg" alt=""></a>
                        <a class="a-2" href="#"><img src="img/often-visit/1-2.jpg" alt=""></a>
                        <a class="a-3" href="#">
                            <div class="intro">
                                <h3>今有潮电</h3>
                                <p>等你来看</p>
                            </div>
                            <img src="img/often-visit/1-3.jpg" alt="">
                        </a>
                        <a class="a-4" href="#">
                            <div class="intro">
                                <h3>首发预约</h3>
                                <p>抢先有奖</p>
                            </div>
                            <img src="img/often-visit/1-4.jpg" alt="">
                        </a>
                        <a class="a-5" href="#">
                            <div class="wrap-1">
                                <div class="img-wrap">
                                    <img src="img/often-visit/1-5.jpg" alt="">
                                </div>
                                <div class="wrap-move">
                                    <span>热门</span>
                                    <h3>遥控仿真飞鸟</h3>
                                    <p>完全参照雀鸟的飞行方式设计而成，马达驱动双翼拍打以产生上升的动力。</p>
                                </div>
                            </div>
                        </a>
                        <a class="a-6" href="#">
                            <img src="img/often-visit/1-6.jpg" alt="">
                            <h3>漫威蓝牙耳机</h3>
                        </a>
                        <a class="a-7" href="#">
                            <img src="img/often-visit/1-7.jpg" alt="">
                            <h3>奇葩大集合</h3>
                        </a>
                    </div>
                </div>
                <div class="section section-2">
                    <div class="left">
                        <a class="img-wrap" href="#"><img src="img/often-visit/1.jpg" alt=""></a>
                        <h3>热门TOP</h3>
                        <a href="#">iPhone 6s</a>
                        <a href="#">看片神器</a>
                        <a href="#">自拍杆</a>
                        <a href="#">智能投影仪</a>
                        <a href="#">智能手环</a>
                        <a href="#">智能手表</a>
                        <a href="#">智能路由器</a>
                        <a href="#">智能机器人</a>
                        <a href="#">制氧器</a>
                    </div>
                    <div class="right">
                        <a class="a-1" href="#"><img src="img/often-visit/1-1.jpg" alt=""></a>
                        <a class="a-2" href="#"><img src="img/often-visit/1-2.jpg" alt=""></a>
                        <a class="a-3" href="#">
                            <div class="intro">
                                <h3>今有潮电</h3>
                                <p>等你来看</p>
                            </div>
                            <img src="img/often-visit/1-3.jpg" alt="">
                        </a>
                        <a class="a-4" href="#">
                            <div class="intro">
                                <h3>首发预约</h3>
                                <p>抢先有奖</p>
                            </div>
                            <img src="img/often-visit/1-4.jpg" alt="">
                        </a>
                        <a class="a-5" href="#">
                            <div class="wrap-1">
                                <div class="img-wrap">
                                    <img src="img/often-visit/1-5.jpg" alt="">
                                </div>
                                <div class="wrap-move">
                                    <span>热门</span>
                                    <h3>遥控仿真飞鸟</h3>
                                    <p>完全参照雀鸟的飞行方式设计而成，马达驱动双翼拍打以产生上升的动力。</p>
                                </div>
                            </div>
                        </a>
                        <a class="a-6" href="#">
                            <img src="img/often-visit/1-6.jpg" alt="">
                            <h3>漫威蓝牙耳机</h3>
                        </a>
                        <a class="a-7" href="#">
                            <img src="img/often-visit/1-7.jpg" alt="">
                            <h3>奇葩大集合</h3>
                        </a>
                    </div>
                </div>
                <div class="section section-3">
                    <div class="left">
                        <a class="img-wrap" href="#"><img src="img/often-visit/1.jpg" alt=""></a>
                        <h3>热门TOP</h3>
                        <a href="#">iPhone 6s</a>
                        <a href="#">看片神器</a>
                        <a href="#">自拍杆</a>
                        <a href="#">智能投影仪</a>
                        <a href="#">智能手环</a>
                        <a href="#">智能手表</a>
                        <a href="#">智能路由器</a>
                        <a href="#">智能机器人</a>
                        <a href="#">制氧器</a>
                    </div>
                    <div class="right">
                        <a class="a-1" href="#"><img src="img/often-visit/1-1.jpg" alt=""></a>
                        <a class="a-2" href="#"><img src="img/often-visit/1-2.jpg" alt=""></a>
                        <a class="a-3" href="#">
                            <div class="intro">
                                <h3>今有潮电</h3>
                                <p>等你来看</p>
                            </div>
                            <img src="img/often-visit/1-3.jpg" alt="">
                        </a>
                        <a class="a-4" href="#">
                            <div class="intro">
                                <h3>首发预约</h3>
                                <p>抢先有奖</p>
                            </div>
                            <img src="img/often-visit/1-4.jpg" alt="">
                        </a>
                        <a class="a-5" href="#">
                            <div class="wrap-1">
                                <div class="img-wrap">
                                    <img src="img/often-visit/1-5.jpg" alt="">
                                </div>
                                <div class="wrap-move">
                                    <span>热门</span>
                                    <h3>遥控仿真飞鸟</h3>
                                    <p>完全参照雀鸟的飞行方式设计而成，马达驱动双翼拍打以产生上升的动力。</p>
                                </div>
                            </div>
                        </a>
                        <a class="a-6" href="#">
                            <img src="img/often-visit/1-6.jpg" alt="">
                            <h3>漫威蓝牙耳机</h3>
                        </a>
                        <a class="a-7" href="#">
                            <img src="img/often-visit/1-7.jpg" alt="">
                            <h3>奇葩大集合</h3>
                        </a>
                    </div>
                </div>
                <div class="section section-4">
                    <div class="left">
                        <a class="img-wrap" href="#"><img src="img/often-visit/1.jpg" alt=""></a>
                        <h3>热门TOP</h3>
                        <a href="#">iPhone 6s</a>
                        <a href="#">看片神器</a>
                        <a href="#">自拍杆</a>
                        <a href="#">智能投影仪</a>
                        <a href="#">智能手环</a>
                        <a href="#">智能手表</a>
                        <a href="#">智能路由器</a>
                        <a href="#">智能机器人</a>
                        <a href="#">制氧器</a>
                    </div>
                    <div class="right">
                        <a class="a-1" href="#"><img src="img/often-visit/1-1.jpg" alt=""></a>
                        <a class="a-2" href="#"><img src="img/often-visit/1-2.jpg" alt=""></a>
                        <a class="a-3" href="#">
                            <div class="intro">
                                <h3>今有潮电</h3>
                                <p>等你来看</p>
                            </div>
                            <img src="img/often-visit/1-3.jpg" alt="">
                        </a>
                        <a class="a-4" href="#">
                            <div class="intro">
                                <h3>首发预约</h3>
                                <p>抢先有奖</p>
                            </div>
                            <img src="img/often-visit/1-4.jpg" alt="">
                        </a>
                        <a class="a-5" href="#">
                            <div class="wrap-1">
                                <div class="img-wrap">
                                    <img src="img/often-visit/1-5.jpg" alt="">
                                </div>
                                <div class="wrap-move">
                                    <span>热门</span>
                                    <h3>遥控仿真飞鸟</h3>
                                    <p>完全参照雀鸟的飞行方式设计而成，马达驱动双翼拍打以产生上升的动力。</p>
                                </div>
                            </div>
                        </a>
                        <a class="a-6" href="#">
                            <img src="img/often-visit/1-6.jpg" alt="">
                            <h3>漫威蓝牙耳机</h3>
                        </a>
                        <a class="a-7" href="#">
                            <img src="img/often-visit/1-7.jpg" alt="">
                            <h3>奇葩大集合</h3>
                        </a>
                    </div>
                </div>
            </div>
            <a class="price-99" href="#"><img src="img/my-often-visit/2.png"></a>
            <div id="ifashtion">
                <h2>时尚爆料王</h2>
                <a class="more" href="#">更多></a>
                <div class="part">
                    <!--左-->
                    <div class="L">
                        <div class="title">
                            <a href="#"><h3></h3></a>
                            <span class="iconfont icon-erweima"></span>
                            <img class="showQR" src="img/showQR/1.png" alt="">
                        </div>
                        <div class="wrap">
                            <a class="a-1" href="#">
                                <img src="img/fashion/1-1.jpg" alt="" />
                                <p>仙女就是性冷淡</p>
                            </a>
                            <a class="a-2" href="#">
                                <img src="img/fashion/1-2.jpg" alt="" />
                                <p>卡哇伊捏</p>
                            </a>
                            <a class="a-3" href="#">
                                <img src="img/fashion/1-3.jpg" alt="" />
                                <p>条纹控</p>
                            </a>
                        </div>
                    </div>
                    <!--右-->
                    <div class="R">
                        <div class="title">
                            <a href="#"><h3></h3></a>
                            <span class="iconfont icon-erweima"></span>
                            <img class="showQR" src="img/showQR/2.png" alt="">
                        </div>
                        <div class="wrap">
                            <a class="a-4" href="#">
                                <img src="img/fashion/1-4.jpg" alt="" />
                                <p>专业护目镜</p>
                            </a>
                            <a class="a-5" href="#">
                                <img src="img/fashion/1-5.jpg" alt="" />
                                <p>时尚兔子包</p>
                            </a>
                            <a class="a-6" href="#">
                                <img src="img/fashion/1-6.jpg" alt="" />
                                <p>飞一般的鞋</p>
                            </a>
                            <a class="a-7" href="#">
                                <img src="img/fashion/1-7.jpg" alt="" />
                                <p>复古咖啡壶</p>
                            </a>
                        </div>
                    </div>
                </div>
                <div class="part part-2">
                    <!--左-->
                    <div class="L">
                        <div class="title">
                            <a href="#"><h3></h3></a>
                            <span class="iconfont icon-erweima"></span>
                            <img class="showQR" src="img/showQR/3.png" alt="">
                        </div>
                        <div class="wrap">
                            <a class="a-2-1" href="#">
                                <img src="img/fashion/2-1.jpg" alt="" />
                                <p>唇膏精选</p>
                            </a>
                            <a class="a-2-2" href="#">
                                <img src="img/fashion/2-2.jpg" alt="" />
                                <p>最潮撩汉妆</p>
                            </a>
                            <a class="a-2-3" href="#">
                                <img src="img/fashion/2-3.jpg" alt="" />
                                <p>美发良品</p>
                            </a>
                        </div>
                    </div>
                    <!--右-->
                    <div class="R">
                        <div class="title">
                            <a href="#"><h3></h3></a>
                            <span class="iconfont icon-erweima"></span>
                            <img class="showQR" src="img/showQR/4.png" alt="">
                        </div>
                        <div class="wrap">
                            <a class="a-2-4" href="#">
                                <img src="img/fashion/2-4.jpg" alt="" />
                                <p>百变花样格子</p>
                            </a>
                            <a class="a-2-5" href="#">
                                <img src="img/fashion/2-5.jpg" alt="" />
                                <p>高颜值手提包</p>
                            </a>
                            <a class="a-2-6" href="#">
                                <img src="img/fashion/2-6.jpg" alt="" />
                                <p>麻花辫怎么扎</p>
                            </a>
                            <a class="a-2-7" href="#">
                                <img src="img/fashion/2-7.jpg" alt="" />
                                <p>塌塌米床垫</p>
                            </a>
                        </div>
                    </div>
                </div>
            </div>
            <div id="quality">
                <h2>品质生活家</h2>
                <a class="more" href="#">更多></a>
                <div class="part part1">
                    <!-- 左 -->
                    <div class="left">
                        <div class="title">
                            <a href="#"><h3></h3></a>
                            <span class="iconfont icon-erweima"></span>
                            <img class="showQR" src="img/showQR/5.png" alt="">
                        </div>
                        <div class="content">
                            <a href="#">
                                <img src="img/quality/1-1.jpg" alt="">
                                <h4>正宗牛肉丸</h4>
                                <p>Q弹有嚼劲</p>
                            </a>
                            <a class="float-r" href="#"> <img src="img/quality/1-2.jpg" alt="">
                                <h4>鲜甜石榴</h4>
                                <p>皮薄汁水甜</p>
                            </a>
                        </div>
                        <div class="more-content">
                            <a class="a1" href="#">应季鲜果</a>
                            <a class="a2" href="#">精致糕点</a>
                            <a class="a3" href="#">全球美食</a>
                            <a class="a4" href="#">烘培原料</a>
                            <a class="a5" href="#">麻辣一夏</a>
                            <a class="a6" href="#">生猛海鲜</a>
                        </div>
                    </div>
                    <!-- 右 -->
                    <div class="right">
                        <div class="title">
                            <a href="#"><h3></h3></a>
                            <span class="iconfont icon-erweima"></span>
                            <img class="showQR" src="img/showQR/6.png" alt="">
                        </div>
                        <div class="content">
                            <a class="margin-r margin-b" href="#"><img src="img/quality/1-3.jpg" alt="">
                                <p>设计师的家</p>
                            </a>
                            <a class="margin-b" href="#"><img src="img/quality/1-4.jpg" alt="">
                                <p>青花瓷元素</p>
                            </a>
                            <a class="margin-r" href="#"><img src="img/quality/1-5.jpg" alt="">
                                <p>音乐无处不在</p>
                            </a>
                            <a href="#"><img src="img/quality/1-6.jpg" alt="">
                                <p>浪漫温柔乡</p>
                            </a>
                        </div>
                    </div>
                </div>
                <div class="part part2">
                    <!-- 左 -->
                    <div class="left">
                        <div class="title">
                            <a href="#"><h3></h3></a>
                        </div>
                        <div class="content">
                            <a href="#">
                                <img src="img/quality/2-1.jpg" alt="">
                                <h4>潮牌手表</h4>
                                <p>rumbatime</p>
                            </a>
                            <a class="float-r" href="#"> <img src="img/quality/2-2.jpg" alt="">
                                <h4>热门女鞋</h4>
                                <p>开口笑</p>
                            </a>
                        </div>
                        <div class="more-content">
                            <a class="a1" href="#">春天的包包</a>
                            <a class="a2" href="#">Chloe墨镜</a>
                            <a class="a3" href="#">小白鞋</a>
                            <a class="a4" href="#">水润你</a>
                            <a class="a5" href="#">亚历山大 王</a>
                            <a class="a6" href="#">Gucci酒神</a>
                        </div>
                    </div>
                    <!-- 右 -->
                    <div class="right">
                        <div class="title">
                            <a href="#"><h3></h3></a>
                            <span class="iconfont icon-erweima"></span>
                            <img class="showQR" src="img/showQR/7.png" alt="">
                        </div>
                        <div class="content">
                            <a class="margin-r margin-b" href="#"><img src="img/quality/2-3.jpg" alt="">
                                <p>设计师的家</p>
                            </a>
                            <a class="margin-b" href="#"><img src="img/quality/2-4.jpg" alt="">
                                <p>青花瓷元素</p>
                            </a>
                            <a class="margin-r" href="#"><img src="img/quality/2-5.jpg" alt="">
                                <p>音乐无处不在</p>
                            </a>
                            <a href="#"><img src="img/quality/2-6.jpg" alt="">
                                <p>浪漫温柔乡</p>
                            </a>
                        </div>
                    </div>
                </div>
                <div class="part part3">
                    <!-- 右 -->
                    <div class="right">
                        <div class="title">
                            <a href="#"><h3></h3></a>
                        </div>
                        <div class="content">
                            <a class="margin-r margin-b" href="#"><img src="img/quality/3-3.jpg" alt="">
                                <p>摩登童年</p>
                            </a>
                            <a class="margin-b" href="#"><img src="img/quality/3-4.jpg" alt="">
                                <p>玩具百宝箱</p>
                            </a>
                            <a class="margin-r" href="#"><img src="img/quality/3-5.jpg" alt="">
                                <p>百变童鞋</p>
                            </a>
                            <a href="#"><img src="img/quality/3-6.jpg" alt="">
                                <p>全球母婴嗨购</p>
                            </a>
                        </div>
                    </div>
                    <!-- 左 -->
                    <div class="left">
                        <div class="title">
                            <a href="#"><h3></h3></a>
                            <span class="iconfont icon-erweima"></span>
                            <img class="showQR" src="img/showQR/8.png" alt="">
                        </div>
                        <div class="content">
                            <a href="#">
                                <img src="img/quality/3-1.jpg" alt="">
                                <h4>品牌好房</h4>
                                <p>品牌楼盘更保值</p>
                            </a>
                            <a class="float-r" href="#"> <img src="img/quality/3-2.jpg" alt="">
                                <h4>最新开盘</h4>
                                <p>这些楼盘刚刚开</p>
                            </a>
                        </div>
                        <div class="more-content">
                            <a class="a1" href="#">万科品牌馆</a>
                            <a class="a2" href="#">绿城品牌馆</a>
                            <a class="a3" href="#">万达品牌馆</a>
                            <a class="a4" href="#">海外买房</a>
                            <a class="a5" href="#">实惠二手房</a>
                            <a class="a6" href="#">找租房</a>
                        </div>
                    </div>
                </div>
                <div class="part part4">
                    <!-- 左 -->
                    <div class="left">
                        <div class="title">
                            <a href="#"><h3></h3></a>
                            <span class="iconfont icon-erweima"></span>
                            <img class="showQR" src="img/showQR/9.png" alt="">
                        </div>
                        <div class="content">
                            <a href="#">
                                <img src="img/quality/4-1.jpg" alt="">
                                <h4>打牌车品</h4>
                                <p>改装一族</p>
                            </a>
                            <a class="float-r" href="#"> <img src="img/quality/4-2.jpg" alt="">
                                <h4>国庆出游季</h4>
                                <p>全场1折起</p>
                            </a>
                        </div>
                        <div class="more-content">
                            <a class="a1" href="#">二手车捡漏</a>
                            <a class="a2" href="#">特价好车</a>
                            <a class="a3" href="#">0利率购车</a>
                            <a class="a4" href="#">车品特卖会</a>
                            <a class="a5" href="#">摩托车特惠</a>
                            <a class="a6" href="#">加油卡充值</a>
                        </div>
                    </div>
                    <!-- 右 -->
                    <div class="right">
                        <div class="title">
                            <a href="#"><h3></h3></a>
                        </div>
                        <div class="content">
                            <a class="margin-r margin-b" href="#"><img src="img/quality/4-3.jpg" alt="">
                                <p>足球鞋限时抢</p>
                            </a>
                            <a class="margin-b" href="#"><img src="img/quality/4-4.jpg" alt="">
                                <p>专业健生教练</p>
                            </a>
                            <a class="margin-r" href="#"><img src="img/quality/4-5.jpg" alt="">
                                <p>运动潮穿必搭</p>
                            </a>
                            <a href="#"><img src="img/quality/4-6.jpg" alt="">
                                <p>全球跑鞋必穿</p>
                            </a>
                        </div>
                    </div>
                </div>
            </div>
            <div id="feature">
                <h2>特色玩味控</h2>
                <a class="more" href="#">更多 ></a>
                <div class="section section1">
                    <div class="title">
                        <a href="#"><h3></h3></a>
                        <div class="showQR">
                            <span class="iconfont icon-erweima"></span>
                            <img src="img/feature/QR1.png" alt="">
                        </div>
                    </div>
                    <div class="content">
                        <a class="a1" href="#">
                            <img src="img/feature/1-1.jpg" alt="">
                            <p>智能折叠电动车</p>
                        </a>
                        <a class="a2" href="#">
                            <img src="img/feature/1-2.jpg" alt="">
                            <p>钢铁侠手臂</p>
                        </a>
                        <a class="a3" href="#">
                            <img src="img/feature/1-3.jpg" alt="">
                            <p>只能后视镜</p>
                        </a>
                        <a class="a4" href="#">
                            <img src="img/feature/1-4.jpg" alt="">
                            <p>都爱奇葩物</p>
                        </a>
                    </div>
                </div>
                <div class="section section2">
                    <div class="title">
                        <a href="#"><h3></h3></a>
                        <div class="showQR">
                            <span class="iconfont icon-erweima"></span>
                            <img src="img/feature/QR2.png" alt="">
                        </div>
                    </div>
                    <div class="content">
                        <a class="a1" href="#">
                            <img src="img/feature/2-1.jpg" alt="">
                            <p>折叠电动车</p>
                        </a>
                        <a class="a2" href="#">
                            <img src="img/feature/2-2.jpg" alt="">
                            <p>30岁别看</p>
                        </a>
                        <a class="a3" href="#">
                            <img src="img/feature/2-3.jpg" alt="">
                            <p>撩妹充电器</p>
                        </a>
                        <a class="a4" href="#">
                            <img src="img/feature/2-4.jpg" alt="">
                            <p>萌萌哒吊坠</p>
                        </a>
                    </div>
                </div>
                <div class="section section3">
                    <div class="title">
                        <a href="#"><h3></h3></a>
                        <div class="showQR">
                            <span class="iconfont icon-erweima"></span>
                            <img src="img/feature/QR3.png" alt="">
                        </div>
                    </div>
                    <div class="content">
                        <a class="a1" href="#">
                            <img src="img/feature/3-1.jpg" alt="">
                            <p>英雄联盟</p>
                        </a>
                        <a class="a2" href="#">
                            <img src="img/feature/3-2.jpg" alt="">
                            <p>守望先锋</p>
                        </a>
                        <a class="a3" href="#">
                            <img src="img/feature/3-3.jpg" alt="">
                            <p>魔兽周边</p>
                        </a>
                        <a class="a4" href="#">
                            <img src="img/feature/3-4.jpg" alt="">
                            <p>零姆</p>
                        </a>
                    </div>
                </div>
                <div class="part part1">
                    <div class="title">
                        <a href="#"><h3></h3></a>
                        <div class="showQR">
                            <span class="iconfont icon-erweima"></span>
                            <img src="img/feature/QR7.png" alt="">
                        </div>
                    </div>
                    <div class="content">
                        <a class="margin-r" href="#">
                            <img src="img/feature/7-1.jpg" alt="">
                            <h4>重点大学本科</h4>
                            <p>报名咨询</p>
                        </a>
                        <a href="#">
                            <img src="img/feature/7-2.jpg" alt="">
                            <h4>机动车驾驶证</h4>
                            <p>考驾校一把过</p>
                        </a>
                    </div>
                    <div class="more-content">
                        <a href="#">学历提升</a>
                        <a href="#">新概念英语</a>
                        <a href="#">考研名师</a>
                        <a href="#">DIY手工</a>
                        <a href="#">驾校学车</a>
                        <a href="#">会计从业</a>
                    </div>
                </div>
                <div class="section section4 margin-T">
                    <div class="title">
                        <a href="#"><h3></h3></a>
                        <div class="showQR">
                            <span class="iconfont icon-erweima"></span>
                            <img src="img/feature/QR4.png" alt="">
                        </div>
                    </div>
                    <div class="content">
                        <a class="a1" href="#">
                            <img src="img/feature/4-1.jpg" alt="">
                            <p>纸皮巴旦木</p>
                        </a>
                        <a class="a2" href="#">
                            <img src="img/feature/4-2.jpg" alt="">
                            <p>健康美味必吃</p>
                        </a>
                        <a class="a3" href="#">
                            <img src="img/feature/4-3.jpg" alt="">
                            <p>酸甜多汁鲜果</p>
                        </a>
                        <a class="a4" href="#">
                            <img src="img/feature/4-4.jpg" alt="">
                            <p>纯手工小吃</p>
                        </a>
                    </div>
                </div>
                <div class="section section5 margin-T">
                    <div class="title">
                        <a href="#"><h3></h3></a>
                        <div class="showQR">
                            <span class="iconfont icon-erweima"></span>
                            <img src="img/feature/QR5.png" alt="">
                        </div>
                    </div>
                    <div class="content">
                        <a class="a1" href="#">
                            <img src="img/feature/5-1.jpg" alt="">
                            <p>司法带牌豪车</p>
                        </a>
                        <a class="a2" href="#">
                            <img src="img/feature/5-2.jpg" alt="">
                            <p>翡翠锁骨项链</p>
                        </a>
                        <a class="a3" href="#">
                            <img src="img/feature/5-3.jpg" alt="">
                            <p>苏秀薪瑞手作</p>
                        </a>
                        <a class="a4" href="#">
                            <img src="img/feature/5-4.jpg" alt="">
                            <p>通勤包袋</p>
                        </a>
                    </div>
                </div>
                <div class="section section6 margin-T">
                    <div class="title">
                        <a href="#"><h3></h3></a>
                        <div class="showQR">
                            <span class="iconfont icon-erweima"></span>
                            <img src="img/feature/QR6.png" alt="">
                        </div>
                    </div>
                    <div class="content">
                        <a class="a1" href="#">
                            <img src="img/feature/6-1.jpg" alt="">
                            <p>桌面鱼缸</p>
                        </a>
                        <a class="a2" href="#">
                            <img src="img/feature/6-2.jpg" alt="">
                            <p>水中精灵</p>
                        </a>
                        <a class="a3" href="#">
                            <img src="img/feature/6-3.jpg" alt="">
                            <p>萌萌多肉</p>
                        </a>
                        <a class="a4" href="#">
                            <img src="img/feature/6-4.jpg" alt="">
                            <p>经典花园植物</p>
                        </a>
                    </div>
                </div>
                <div class="part part2 margin-T">
                    <div class="title">
                        <a href="#"><h3></h3></a>
                        <div class="showQR">
                            <span class="iconfont icon-erweima"></span>
                            <img src="img/feature/QR8.png" alt="">
                        </div>
                    </div>
                    <div class="content">
                        <a class="margin-r" href="#">
                            <img src="img/feature/8-1.jpg" alt="">
                            <h4>水泥的温暖照亮</h4>
                            <p>混凝土灯饰制作</p>
                        </a>
                        <a href="#">
                            <img src="img/feature/8-2.jpg" alt="">
                            <h4>那些花儿静绽放</h4>
                            <p>真实与写意间</p>
                        </a>
                    </div>
                    <div class="more-content">
                        <a href="#">意念控制器</a>
                        <a href="#">太阳能电池</a>
                        <a href="#">家用投影仪</a>
                        <a href="#">照片打印机</a>
                        <a href="#">直男工具组</a>
                        <a href="#">3D打印笔</a>
                    </div>
                </div>
            </div>
            <div id="benefits">
                <h2>实惠专业户</h2>
                <a class="more" href="#">更多 ></a>
                <div class="section section1">
                    <div class="left">
                        <div class="title">
                            <a href="#"><h3></h3></a>
                            <div class="showQR">
                                <span class="iconfont icon-erweima"></span>
                                <img src="img/benefits/QR1.png" alt="">
                            </div>
                        </div>
                        <div class="content">
                            <a href="#">
                                <p>乐扣乐扣爆款保温杯 买一送四</p>
                            </a>
                            <span class="price">￥ 57</span>
                            <span class="count">已抢购39件</span>
                        </div>
                    </div>
                    <div class="right">
                        <p>抢购进行中</p>
                        <a href="#"><img src="img/benefits/1.jpg" alt=""></a>
                    </div>
                </div>
                <div class="part part1">
                    <div class="title">
                        <a href="#"><h3></h3></a>
                        <div class="showQR">
                            <span class="iconfont icon-erweima"></span>
                            <img src="img/benefits/QR3.png" alt="">
                        </div>
                    </div>
                    <div class="content">
                        <h4>优质好货</h4>
                        <p>特价专区</p>
                        <a href="#">十元包邮</a>
                        <a class="img" href="#"><img src="img/benefits/3.jpg" alt=""></a>
                    </div>
                </div>
                <div class="part part2">
                    <div class="title">
                        <a href="#"><h3></h3></a>
                        <div class="showQR">
                            <span class="iconfont icon-erweima"></span>
                            <img src="img/benefits/QR4.png" alt="">
                        </div>
                    </div>
                    <div class="content">
                        <h4>秋冬白回来</h4>
                        <p>美白淡斑</p>
                        <a href="#">折上再抵</a>
                        <a class="img" href="#"><img src="img/benefits/4.jpg" alt=""></a>
                    </div>
                </div>
                <div class="part part3">
                    <div class="title">
                        <a href="#"><h3></h3></a>
                        <div class="showQR">
                            <span class="iconfont icon-erweima"></span>
                            <img src="img/benefits/QR5.png" alt="">
                        </div>
                    </div>
                    <div class="content">
                        <h4>0点上新</h4>
                        <p>特价包邮</p>
                        <a href="#">限量必抢</a>
                        <a class="img" href="#"><img src="img/benefits/5.jpg" alt=""></a>
                    </div>
                </div>
                <div class="section section2">
                    <div class="left">
                        <div class="title">
                            <a href="#"><h3></h3></a>
                            <div class="showQR">
                                <span class="iconfont icon-erweima"></span>
                                <img src="img/benefits/QR2.png" alt="">
                            </div>
                        </div>
                        <div class="content">
                            <p class="grab">0.01元疯抢</p>
                            <p>超值付邮领</p>
                            <a href="#">先用后买</a>
                        </div>
                    </div>
                    <div class="right">
                        <p></p>
                        <a href="#"><img src="img/benefits/2.jpg" alt=""></a>
                    </div>
                </div>
                <div class="part part4">
                    <div class="title">
                        <a href="#"><h3></h3></a>
                        <div class="showQR">
                            <span class="iconfont icon-erweima"></span>
                            <img src="img/benefits/QR6.png" alt="">
                        </div>
                    </div>
                    <div class="content">
                        <h4>奢品底价购</h4>
                        <p>网红最爱</p>
                        <a href="#">剁手</a>
                        <a class="img" href="#"><img src="img/benefits/6.jpg" alt=""></a>
                    </div>
                </div>
                <div class="part part5">
                    <div class="title">
                        <a href="#"><h3></h3></a>
                        <div class="showQR">
                            <span class="iconfont icon-erweima"></span>
                            <img src="img/benefits/QR7.png" alt="">
                        </div>
                    </div>
                    <div class="content">
                        <h4>品牌尾货</h4>
                        <p>断色断码抢</p>
                        <a href="#">便宜有好货</a>
                        <a class="img" href="#"><img src="img/benefits/7.jpg" alt=""></a>
                    </div>
                </div>
                <div class="part part6">
                    <div class="title">
                        <a href="#"><h3></h3></a>
                        <div class="showQR">
                            <span class="iconfont icon-erweima"></span>
                            <img src="img/benefits/QR8.png" alt="">
                        </div>
                    </div>
                    <div class="content">
                        <h4>时尚穿搭</h4>
                        <p>全场包邮</p>
                        <a href="#">品牌特卖</a>
                        <a class="img" href="#"><img src="img/benefits/8.jpg" alt=""></a>
                    </div>
                </div>
            </div>
            <div class="startwork-lowprice">
                <a href="#"><img src="img/bar.png" alt=""></a>
            </div>
        </div>
        <div id="side">
            <div class="user">
                <a class="bg-1" href="#"></a>
                <p class="p-1">Hi!你好</p>
                <p class="p-2"><span class="bg-2"></span><a href="#">领淘金币抵钱</a>或去<span><a href="#">会员俱乐部</a></span></p>
                <ul>
                    <li><a href="#">登录</a></li>
                    <li><a href="#">注册</a></li>
                    <li><a href="#">开店</a></li>
                </ul>
            </div>
            <div class="announcement">
                <ul class="ul-1">
                    <li class="li-1 active-1"><a href="#">公告</a>
                        <ul class="ul-2 show">
                            <li><a class="active-2" href="#">9.9天猫全球酒水节启动</a></li>
                            <li><a class="active-2" href="#">10万款酒水等你来干杯</a></li>
                            <li><a class="mt" href="#">天猫超市"订单价对折"</a></li>
                            <li><a class="mt" href="#">女排朱婷上闲鱼学技能</a></li>
                        </ul>
                    </li>
                    <li class="li-1"><a href="#">规则</a>
                        <ul class="ul-2">
                            <li><a class="active-2" href="#">手机号卡商品禁售变更</a></li>
                            <li><a href="#">医疗服务类商品禁售</a></li>
                            <li><a class="mt" href="#">全球购买手市场管理规</a></li>
                            <li><a class="mt" href="#">分期返还类商品禁售</a></li>
                        </ul>
                    </li>
                    <li class="li-1"><a href="#">论坛</a>
                        <ul class="ul-2">
                            <li><a class="active-2" href="#">G20杭州快递影响</a></li>
                            <li><a href="#">杭州"低慢小"禁飞</a></li>
                            <li><a class="mt" href="#">十八纸颠覆家具</a></li>
                            <li><a class="mt" href="#">是赚钱还是骗子</a></li>
                        </ul>
                    </li>
                    <li class="li-1"><a href="#">安全</a>
                        <ul class="ul-2">
                            <li><a class="active-2" href="#">小心被骗子买家盯上</a></li>
                            <li><a class="active-2" href="#">为什么搜不到你宝贝</a></li>
                            <li><a class="mt" href="#">代理生态净化启动</a></li>
                            <li><a class="mt" href="#">新手卖家自杀式玩法</a></li>
                        </ul>
                    </li>
                    <li class="li-1 no-mr"><a href="#">公益</a>
                        <ul class="ul-2">
                            <li><a class="active-2" href="#">阿里捐赠700万元救灾</a></li>
                            <li><a href="#">阿里与残联出助残政策</a></li>
                            <li><a class="mt" href="#">公益宝贝卖家发票索取</a></li>
                            <li><a class="mt" href="#">公益机构淘宝开店攻略</a></li>
                        </ul>
                    </li>
                </ul>
            </div>
            <div class="recharge">
                <ul class="ul-1 clear">
                    <!-- 充话费 -->
                    <li class="li-1"><a href="#"><span class="iconfont icon-shouji"></span><span class="text">充话费</span></a>
                        <ul class="ul-2-1 ul-show clear">
                            <li class="li-2 li-2-1 li-2-first act"><a href="#">充话费</a>
                                <form class="formShow" action="#">
                                    <div class="input-wrap">
                                        <input class="input-number" type="text"><span class="input-number-next iconfont icon-tongxunlu"></span>
                                        <input class="choose-count" type="button"><span class="choose-count-next iconfont icon-jiantouxia"></span>
                                    </div>
                                    <p>售价￥<span>49-49.8</span></p>
                                    <input class="instant" type="button" value="立即充值">
                                </form>
                            </li>
                            <li class="li-2 li-2-2"><a href="#">充流量</a>
                                <form action="#">
                                    <div class="input-wrap">
                                        <input class="input-number" type="text"><span class="input-number-next iconfont icon-tongxunlu"></span>
                                        <input class="type" type="button" value="全国流量"><span class="type-next iconfont icon-jiantouxia"></span>
                                        <input class="old-number" type="button"><span class="old-number-next iconfont icon-jiantouxia"></span>
                                    </div>
                                    <p>售价￥<span>49-49.8</span></p>
                                    <input class="instant" type="button" value="立即充值">
                                </form>
                            </li>
                            <li class="li-2 li-2-3"><a href="#">充固话</a>
                                <form action="#">
                                    <div class="input-wrap">
                                        <input class="choose-1" type="radio" name="operator" value="电信"><span class="choose-1-next">电信</span>
                                        <input class="choose-2" type="radio" name="operator" value="联通"><span class="choose-2-next">联通</span>
                                        <input class="input-fixed" type="text"><span class="input-fixed-next iconfont icon-tongxunlu"></span>
                                        <input class="choose-count" type="button" value="50元"><span class="choose-count-next iconfont icon-jiantouxia"></span>
                                    </div>
                                    <input class="instant" type="button" value="立即充值">
                                    <p>售价￥<span>49-49.8</span></p>
                                </form>
                            </li>
                            <li class="li-2 li-2-4"><a href="#">充宽带</a>
                                <form action="#">
                                    <div class="input-wrap">
                                        <input class="telecom" type="button" value="电信/城市"><span class="telecom-next iconfont icon-jiantouxia"></span>
                                        <input class="input-number" type="text" value="请输入宽带账号"><span class="input-number-next iconfont icon-tongxunlu"></span>
                                        <input class="choose-count" type="button" value="50元"><span class="choose-count-next iconfont icon-jiantouxia"></span>
                                    </div>
                                    <input class="instant" type="button" value="立即充值">
                                    <p>售价￥<span>49-49.8</span></p>
                                </form>
                            </li>
                            <li class="close"><a href="javascript:;">×</a></li>
                        </ul>
                    </li>
                    <!-- 游戏 -->
                    <li class="li-1"><a href="#"><span class="iconfont icon-youxi"></span><span class="text act">游戏</span></a>
                        <ul class="ul-2-2 ul-show clear">
                            <li class="li-2 li-2-1 act"><a href="#">点卡</a>
                                <form class="formShow" action="#">
                                    <div class="input-wrap">
                                        <h6>游戏</h6>
                                        <input class="input-name" type="text"><span class="input-name-next iconfont icon-youxicaidan"></span>
                                        <h6 class="no-border-top">面值</h6>
                                        <input class="choose-count" type="button" value="10元"><span class="choose-count-next iconfont icon-jiantouxia"></span>
                                        <input class="choose-1" type="radio" name="type"><span class="choose-1-next">自动充值</span>
                                        <input class="choose-2" type="radio" name="type"><span class="choose-2-next">购买卡密</span>
                                        <input class="instant" type="button" value="立即充值">
                                        <p><a href="#">超值游戏礼包马上领取！</a></p>
                                    </div>
                                </form>
                            </li>
                            <li class="li-2 li-2-2"><a href="#">QQ</a>
                                <form action="#">
                                    <div class="input-wrap">
                                        <input class="input-QQ" type="text">
                                        <input class="type" type="button" value="Q币"><span class="type-next iconfont icon-jiantouxia"></span>
                                        <input class="count" type="button" value="5个"><span class="count-next iconfont icon-jiantouxia"></span>
                                        <p><i>￥</i><span>4.8</span></p>
                                        <input class="instant" type="button" value="立刻充值">
                                        <p class="more"><a href="#">更多精彩，尽在淘宝游戏</a></p>
                                    </div>
                                </form>
                            </li>
                            <li class="li-2 li-2-3"><a href="#">网页游戏</a>
                                <ul class="games">
                                    <li class="datianshizhijian first">
                                        <a class="a-1" href="#"></a>
                                    </li>
                                    <li class="gongchengluedi">
                                        <a class="a-1" href="#"></a>
                                    </li>
                                    <li class="nvshenlianmeng">
                                        <a class="a-1" href="#"></a>
                                    </li>
                                    <li class="fengyunwushuang"><a class="a-2" href="#">风云无双</a></li>
                                    <li class="lieyan"><a class="a-2" href="#">烈焰</a></li>
                                    <li class="dezhoupuke"><a class="a-2" href="#">德州扑克</a></li>
                                    <li class="wuyichuanqi"><a class="a-2" href="#">武易传奇</a></li>
                                    <li class="rexuesanguoer"><a class="a-2" href="#">热血三国2</a></li>
                                    <li class="qijilaile"><a class="a-2" href="#">奇迹来了</a></li>
                                </ul>
                            </li>
                            <li class="close"><a href="javascript:;">×</a></li>
                        </ul>
                    </li>
                    <!-- 旅行 -->
                    <li class="li-1"><a href="#"><span class="iconfont icon-zhifeiji"></span><span class="text act">旅行</span></a>
                        <ul class="ul-2-3 ul-show clear">
                            <li class="li-2 li-2-1 first act"><a href="#">国内机票</a>
                                <form class="formShow" action="#">
                                    <div class="input-wrap">
                                        <input class="type" type="radio" name="type"><span class="form form-1">单程</span>
                                        <input class="type" type="radio" name="type"><span class="form form-2">往返</span>
                                        <p class="tip">港澳台请选择国际机票</p>
                                        <span class="start">出发</span>
                                        <input class="choose-city" type="button" value="城市"><span class="choose-city-next iconfont icon-zuobiao"></span><span class="you">→</span>
                                        <span class="arrive">到达</span>
                                        <input class="choose-city" type="button" value="城市"><span class="choose-city-next iconfont icon-zuobiao"></span>
                                        <span class="start start-">出发</span>
                                        <input class="date" type="button" value="日期"><span class="date-next iconfont icon-riqi"></span>
                                        <input class="search" type="button" value="查找">
                                        <p class="favorable"><a href="#">国内机票满减30元，整点速抢！</a></p>
                                    </div>
                                </form>
                            </li>
                            <li class="li-2 li-2-2"><a href="#">国际机票</a>
                                <form action="#">
                                    <div class="input-wrap">
                                        <input class="type" type="radio" name="type"><span class="form form-1">单程</span>
                                        <input class="type" type="radio" name="type"><span class="form form-2">往返</span>
                                        <span class="start">出发</span>
                                        <input class="choose-city" type="button" value="城市"><span class="choose-city-next iconfont icon-zuobiao"></span><span class="you">→</span>
                                        <span class="arrive">到达</span>
                                        <input class="choose-city" type="button" value="城市"><span class="choose-city-next iconfont icon-zuobiao"></span>
                                        <span class="start start-">出发</span>
                                        <input class="date" type="button" value="日期"><span class="date-next iconfont icon-riqi"></span>
                                        <input class="search" type="button" value="查找">
                                        <p class="favorable"><a href="#">国际机票满减50元，整点速抢！</a></p>
                                    </div>
                                </form>
                            </li>
                            <li class="li-2 li-2-3"><a href="#">酒店客栈</a>
                                <form action="#">
                                    <div class="input-wrap">
                                        <input class="type" type="radio" name="type"><span class="form form-1">国内/港澳台</span>
                                        <input class="type" type="radio" name="type"><span class="form form-2">海外</span>
                                        <span class="check">入住</span>
                                        <input class="choose-city" type="button" value="北京"><span class="choose-city-next iconfont icon-zuobiao"></span>
                                        <input class="location" type="text" value="酒店/地标">
                                        <span class="check check-">入住</span>
                                        <input class="date" type="button" value="2016-9-06"><span class="date-next iconfont icon-riqi"></span>
                                        <span class="leave leave-">离店</span>
                                        <input class="date" type="button" value="2016-9-08"><span class="date-next date-next- iconfont icon-riqi"></span>
                                        <input class="search" type="button" value="搜索">
                                        <p class="favorable"><a href="#">五星酒店低价住</a></p>
                                    </div>
                                </form>
                            </li>
                            <li class="li-2 li-2-4"><a href="#">度假门票</a>
                                <form action="#">
                                    <div class="input-wrap">
                                        <input class="type" type="radio" name="type"><span class="form form-1">度假</span>
                                        <input class="type" type="radio" name="type"><span class="form form-2">门票</span>
                                        <span class="start">出发</span>
                                        <input class="choose-city" type="button" value="城市"><span class="choose-city-next iconfont icon-zuobiao"></span>
                                        <span class="arrive">到达</span>
                                        <input class="choose-city" type="button" value="城市/景点"><span class="choose-city-next choose-city-next-no iconfont icon-zuobiao"></span>
                                        <input class="search" type="button" value="搜索">
                                        <p class="favorable"><a href="#">看这里，机票团购价，旅行更划算</a></p>
                                    </div>
                                </form>
                            </li>
                            <li class="li-2 li-2-5"><a href="#">火车票</a>
                                <form action="#">
                                    <div class="input-wrap">
                                        <span class="start">出发</span>
                                        <input class="choose-city" type="button" value="北京"><span class="choose-city-next iconfont icon-zuobiao"></span>
                                        <span class="arrive">到达</span>
                                        <input class="choose-city" type="button" value="城市/景点"><span class="choose-city-next choose-city-next-no iconfont icon-zuobiao"></span>
                                        <span class="start start-">出发</span>
                                        <input class="date" type="button" value="日期"><span class="date-next iconfont icon-riqi"></span>
                                        <input class="search" type="button" value="查找">
                                    </div>
                                </form>
                            </li>
                            <li class="close"><a href="javascript:;">×</a></li>
                        </ul>
                    </li>
                    <!-- 保险 -->
                    <li class="li-1"><a href="#"><span class="iconfont icon-baoxian"></span><span class="text act">保险</span></a>
                        <ul class="ul-2-4 ul-show clear">
                            <li class="li-2 li-2-1  act"><a href="#">车险</a>
                                <form class="formShow" action="#">
                                    <div class="input-wrap">
                                        <span class="hot-city">热门城市</span>
                                        <input class="choose-city" type="text" value="请选择城市"><span class="choose-city-next"></span>
                                        <span class="insure-company">保险公司</span>
                                        <input class="choose-type" type="text" value="人保车险"><span class="choose-type-next"></span>
                                        <input class="instant" type="button" value="立刻报价">
                                        <input class="fast" type="button" value="快速续保">
                                        <a class="active" href="#">车险活动</a>
                                    </div>
                                </form>
                            </li>
                            <li class="li-2 li-2-2"><a href="#">意外险</a>
                                <form action="#">
                                    <div class="input-wrap">
                                        <span class="insure-type">保险类型</span>
                                        <input class="avi-accident" type="text" value="航空意外"><span class="avi-accident-next iconfont icon-jiantouxia"></span>
                                        <span class="insure-time">保险期间</span>
                                        <input class="choose-time" type="text" value="1年以内"><span class="choose-time-next iconfont icon-jiantouxia"></span>
                                        <input class="instant" type="button" value="查看适合的保险">
                                    </div>
                                </form>
                            </li>
                            <li class="li-2 li-2-3"><a href="#">健康险</a>
                                <form action="#">
                                    <div class="input-wrap">
                                        <span class="insure-type">保障类型</span>
                                        <input class="illness" type="text" value="重大疾病"><span class="illness-next iconfont icon-jiantouxia"></span>
                                        <span class="fea-insure">特色保障</span>
                                        <input class="insure-xubao" type="text" value="可保证续保"><span class="insure-xubao-next iconfont icon-jiantouxia"></span>
                                        <input class="instant" type="button" value="查看适合的保险">
                                        <a class="most-complete" href="#">最全人寿险</a>
                                    </div>
                                </form>
                            </li>
                            <li class="li-2 li-2-4"><a href="#">旅行险</a>
                                <form action="#">
                                    <div class="input-wrap">
                                        <span class="go-location">出行地区</span>
                                        <input class="churchyard" type="text" value="境内"><span class="churchyard-next iconfont icon-jiantouxia"></span>
                                        <span class="go-time">出行天数</span>
                                        <input class="choose-time" type="text" value="7天及以下"><span class="choose-time-next iconfont icon-jiantouxia"></span>
                                        <input class="instant" type="button" value="查看适合的保险">
                                    </div>
                                </form>
                            </li>
                            <li class="li-2 li-2-5"><a href="#">财产险</a>
                                <form action="#">
                                    <div class="input-wrap">
                                        <span class="fea-insure">特色保障</span>
                                        <input class="choose-type" type="text" value="水管爆裂"><span class="choose-type-next iconfont icon-jiantouxia"></span>
                                        <input class="instant" type="button" value="查看适合的保险">
                                    </div>
                                </form>
                            </li>
                            <li class="close"><a href="javascript:;">×</a></li>
                        </ul>
                    </li>
                    <li class="li-1-u"><a href="#"><span class="iconfont icon-caipiao"></span><span class="text act">彩票</span></a></li>
                    <li class="li-1-u"><a href="#"><span class="iconfont icon-dianying"></span><span class="text act">电影</span></a></li>
                    <li class="li-1-u"><a href="#"><span class="iconfont icon-waimai"></span><span class="text act">点外卖</span></a></li>
                    <li class="li-1-u"><a href="#"><span class="iconfont icon-yuanbao"></span><span class="text act">理财</span></a></li>
                    <li class="li-1-u"><a href="#"><span class="iconfont icon-xiaolian"></span><span class="text act">找服务</span></a></li>
                    <li class="li-1-u"><a href="#"><span class="iconfont icon-yinle"></span><span class="text act">音乐</span></a></li>
                    <li class="li-1-u"><a href="#"><span class="iconfont icon-shuidianmeijiaofei"></span><span class="text act">水电煤</span></a></li>
                    <li class="li-1-u"><a href="#"><span class="iconfont icon-huochepiao"></span><span class="text act">火车票</span></a></li>
                </ul>
            </div>
            <div class="aliAPP">
                <h3>阿里APP</h3><a class="more" href="#" javascript:;>更多></a>
                <ul>
                    <li class="mLeft">
                        <a href="#"><img src="img/aliAPP/1.png" alt=""></a>
                    </li>
                    <li>
                        <a href="#"><img src="img/aliAPP/2.png" alt=""></a>
                    </li>
                    <li>
                        <a href="#"><img src="img/aliAPP/3.png" alt=""></a>
                    </li>
                    <li>
                        <a href="#"><img src="img/aliAPP/4.png" alt=""></a>
                    </li>
                    <li>
                        <a href="#"><img src="img/aliAPP/5.png" alt=""></a>
                    </li>
                    <li class="mLeft">
                        <a href="#"><img src="img/aliAPP/6.png" alt=""></a>
                    </li>
                    <li>
                        <a href="#"><img src="img/aliAPP/7.png" alt=""></a>
                    </li>
                    <li>
                        <a href="#"><img src="img/aliAPP/8.png" alt=""></a>
                    </li>
                    <li>
                        <a href="#"><img src="img/aliAPP/9.png" alt=""></a>
                    </li>
                    <li>
                        <a href="#"><img src="img/aliAPP/10.png" alt=""></a>
                    </li>
                </ul>
            </div>
            <div id="headline">
                <div class="title">
                    <h2></h2>
                    <a href="#" class="more">更多></a>
                </div>
                <a href="#" class="content clear">
                    <div class="wrap">
                        <div class="content-1">
                            <img src="img/headline/bg1.png" alt="">
                            <h3>深秋待产包都要准备哪些东西</h3>
                            <p>待产包是准爸妈们都需要准备好的，但是待产包都要准备哪些东西呢？很</p>
                        </div>
                        <div class="content-2"> <img src="img/headline/bg2.png" alt="">
                            <h3>胖脸女生，如何改造精致小v</h3>
                            <p>在这个以瘦为美的时代，许多妹子都为自己圆圆的脸蛋感到苦恼：和朋友</p>
                        </div>
                        <div class="content-3">
                            <img src="img/headline/bg3.png" alt="">
                            <h3>女人胖点才好，不信胖mm们看</h3>
                            <p>胖一点的女人才可爱，她自带萌感，圆圆的苹果脸好想伸手捏。不像锥子</p>
                        </div>
                    </div>
                </a>
            </div>
            <div id="goodGoods">
                <h2></h2>
                <ul class="content">
                    <li>
                        <a href="#">
                            <img src="img/goodGoods/1.png" alt="">
                            <h3>短袖连衣裙</h3>
                            <p>经典的撞色大圆领设计，微露性感的锁骨线条，同时又</p>
                            <span>255人说好</span>
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <img src="img/goodGoods/2.png" alt="">
                            <h3>Gourmet 2015 春季系</h3>
                            <p>人气鞋履品牌Gourmet一向以天马行空的创意而闻名，日</p>
                            <span>58人说好</span>
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <img src="img/goodGoods/3.png" alt="">
                            <h3>手工雕花茶几</h3>
                            <p>整体造型设计传承了法式经典风格，加以进口榉木材质</p>
                            <span>185人说好</span>
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <img src="img/goodGoods/4.png" alt="">
                            <h3>印花连衣裙</h3>
                            <p>可爱的娃娃领领口设计，衬托出娇美气质，缤纷的花朵</p>
                            <span>255人说好</span>
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <img src="img/goodGoods/5.png" alt="">
                            <h3>印花连身裙</h3>
                            <p>时尚的卡通印花设计，打造摩登简约风格，展现慢慢设</p>
                            <span>54人说好</span>
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <img src="img/goodGoods/6.png" alt="">
                            <h3>【黑品诺干红】澳洲进</h3>
                            <p>澳大利亚原瓶进口，黑品诺干红，酒体呈现优雅的宝石</p>
                            <span>598人说好</span>
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <img src="img/goodGoods/7.png" alt="">
                            <h3>kenzo 2015春夏新品圆</h3>
                            <p>kenzo 一发箍LV.MH旗下的一个只有快乐色彩和浪漫想象</p>
                            <span>17人说好</span>
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <img src="img/goodGoods/8.png" alt="">
                            <h3>法国Chantecaille花妍唇</h3>
                            <p>Chantecaille香提卡花妍防晒护唇膏、色调鲜明，闪润</p>
                            <span>76人说好</span>
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <img src="img/goodGoods/9.png" alt="">
                            <h3>高街原创印花个性男女</h3>
                            <p>个性波动线条印花撞色满印身，深浅变化，前卫大胆</p>
                            <span>32人说好</span>
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <img src="img/goodGoods/10.png" alt="">
                            <h3>简约纯色背心</h3>
                            <p>圆领设计，简洁大方，肩部的四线密拷是美妙的小细节</p>
                            <span>78人说好</span>
                        </a>
                    </li>
                </ul>
                <a class="exchange" href="#">
                    <span class="iconfont icon-shuaxin"></span>
                    <p>换一组看看</p>
                </a>
            </div>
            <div id="goodShop">
                <h2></h2>
                <ul>
                    <li>
                        <a href="#">
                            <h3>每日推荐—1天3波</h3>
                            <p>一个月被关注了3132次，一定有好东西！</p>
                            <img class="img1" src="img/goodShop/1-1.png" alt="">
                            <img class="imgLeft" src="img/goodShop/1-2.png" alt="">
                            <img src="img/goodShop/1-3.png" alt="">
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <h3>吃吃吃</h3>
                            <p>好评率100%，神店！</p>
                            <img class="img1" src="img/goodShop/2-1.png" alt="">
                            <img class="imgLeft" src="img/goodShop/2-2.png" alt="">
                            <img src="img/goodShop/2-3.png" alt="">
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <h3>生活家—爱的杂货铺</h3>
                            <p>好评率99.91%,神店！</p>
                            <img class="img1" src="img/goodShop/3-1.png" alt="">
                            <img class="imgLeft" src="img/goodShop/3-2.png" alt="">
                            <img src="img/goodShop/3-3.png" alt="">
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <h3>包包控</h3>
                            <p>好评率100%，神店！</p>
                            <img class="img1" src="img/goodShop/4-1.png" alt="">
                            <img class="imgLeft" src="img/goodShop/4-2.png" alt="">
                            <img src="img/goodShop/4-3.png" alt="">
                        </a>
                    </li>
                </ul>
                <a href="#" class="seeMore">
                    <span class="iconfont icon-yanjing"></span>
                    <p>查看更多好店</p>
                </a>
            </div>
            <div id="shunfengbaoyou">
                <h2>今日热卖</h2>
                <a href="#"><img src="img/shunfengbaoyou.png" alt=""></a>
            </div>
        </div>
    </div>
    <div id="hotSale">
        <div class="title">
            <h2>热卖单品</h2>
            <ul>
                <li><a href="#">音箱</a></li><span class="iconfont icon-shuxian"></span>
                <li><a href="#">客厅灯</a></li><span class="iconfont icon-shuxian"></span>
                <li><a href="#">床垫</a></li><span class="iconfont icon-shuxian"></span>
                <li><a href="#">沙发垫</a></li><span class="iconfont icon-shuxian"></span>
                <li><a href="#">冲锋衣</a></li><span class="iconfont icon-shuxian"></span>
                <li><a href="#">孕妇裤</a></li><span class="iconfont icon-shuxian"></span>
                <li><a href="#">拉杆箱</a></li><span class="iconfont icon-shuxian"></span>
                <li><a href="#">电脑椅</a></li><span class="iconfont icon-shuxian"></span>
                <li><a href="#">牛仔裤</a></li><span class="iconfont icon-shuxian"></span>
                <li><a href="#">收纳箱</a></li><span class="iconfont icon-shuxian"></span>
                <li><a href="#">沙发</a></li><span class="iconfont icon-shuxian"></span>
                <li><a href="#">衣柜</a></li><span class="iconfont icon-shuxian"></span>
                <li><a href="#">电脑桌</a></li><span class="iconfont icon-shuxian"></span>
                <li><a href="#">男内裤</a></li><span class="iconfont icon-shuxian"></span>
                <li><a href="#">运动装</a></li><span class="iconfont icon-shuxian"></span>
                <li><a href="#">鞋柜</a></li><span class="iconfont icon-shuxian"></span>
                <li><a href="#">窗帘</a></li><span class="iconfont icon-shuxian"></span>
                <li><a href="#">妈妈装</a></li><span class="iconfont icon-shuxian"></span>
                <li><a href="#">椅子</a></li><span class="iconfont icon-shuxian"></span>
                <li><a href="#">围巾</a></li><span class="iconfont icon-shuxian"></span>
                <li><a href="#">茶几</a></li><span class="iconfont icon-shuxian"></span>
                <li><a href="#">t恤女</a></li><span class="iconfont icon-shuxian"></span>
            </ul>
        </div>
        <div class="part part1">
            <div class="left">
                <a class="goods1" href="#">
                    <img src="img/hotSale/1-1.png" alt="">
                    <span class="price">￥ 388.00</span>
                    <span class="count">月销5笔</span>
                    <p>Accurian公司顶级之作，外观时尚稳重，声音精准，动态大，密度质感极强，理性及深厚的音...</p>
                    <span class="assess">评价 0</span>
                    <span class="collect">收藏 1994</span>
                </a>
                <div class="shade">
                    <div class="top"></div>
                    <div class="bottom"></div>
                </div>
                <p class="shade-p">原装有源低音炮 特价</p>
                <a class="shade-a" href="#">去看看</a>
            </div>
            <div class="right">
                <a class="goods2" href="">
                    <img src="img/hotSale/1-2.png" alt="">
                    <span class="price">￥ 800.00</span>
                    <span class="count">月销5笔</span>
                </a>
                <a class="goods3" href="">
                    <img src="img/hotSale/1-3.png" alt="">
                    <span class="price">￥ 5500.00</span>
                    <span class="count">月销5笔</span>
                </a>
                <!-- shade2 -->
                <div class="shade2">
                    <div class="top"></div>
                    <div class="bottom"></div>
                </div>
                <p class="shade-p2">"超值促销"低音炮</p>
                <a class="shade-a2" href="#">去看看</a>
                <!-- shade3 -->
                <div class="shade3">
                    <div class="top"></div>
                    <div class="bottom"></div>
                </div>
                <p class="shade-p3">喇叭 热卖宝贝</p>
                <a class="shade-a3" href="#">去看看</a>
            </div>
        </div>
        <div class="part part2">
            <div class="left">
                <a class="goods1" href="#">
                    <img src="img/hotSale/2-1.png" alt="">
                    <span class="price">￥ 278.00</span>
                    <span class="baoyou">包邮</span>
                    <span class="xinpin">新品</span>
                    <span class="count">月销69笔</span>
                    <p>中国好宝贝，走过路过不要错过咯~~</p>
                    <span class="assess">评价 0</span>
                    <span class="collect">收藏 364</span>
                </a>
                <div class="shade">
                    <div class="top"></div>
                    <div class="bottom"></div>
                </div>
                <p class="shade-p">香萱 粗跟靴子 超值专享</p>
                <a class="shade-a" href="#">去看看</a>
            </div>
            <div class="right">
                <a class="goods2" href="">
                    <img src="img/hotSale/2-2.png" alt="">
                    <span class="price">￥ 89.00</span>
                    <span class="baoyou">包邮</span>
                    <span class="count">月销162笔</span>
                </a>
                <a class="goods3" href="">
                    <img src="img/hotSale/2-3.png" alt="">
                    <span class="price">￥ 198.00</span>
                    <span class="count">月销3笔</span>
                </a>
                <!-- shade2 -->
                <div class="shade2">
                    <div class="top"></div>
                    <div class="bottom"></div>
                </div>
                <p class="shade-p2">纯绒体验：携善伊 毛线</p>
                <a class="shade-a2" href="#">去看看</a>
                <!-- shade3 -->
                <div class="shade3">
                    <div class="top"></div>
                    <div class="bottom"></div>
                </div>
                <p class="shade-p3">专属优惠 波斯顿 低音炮</p>
                <a class="shade-a3" href="#">去看看</a>
            </div>
        </div>
        <div class="part part3">
            <div class="left">
                <a class="goods1" href="#">
                    <img src="img/hotSale/3-1.png" alt="">
                    <span class="price">$ 789.00</span>
                    <span class="baoyou">包邮</span>
                    <span class="count">月销38笔</span>
                    <p>箱体采用高密度复合板材净重量达到</p>
                    <span class="assess">评价 0</span>
                    <span class="collect">收藏 2768</span>
                    <div class="shade">
                        <div class="top"></div>
                        <div class="bottom"></div>
                    </div>
                    <p class="shade-p">诺普声 低音炮 促销特惠</p>
                    <a class="shade-a" href="#">去看看</a>
                </a>
            </div>
            <div class="right">
                <a class="goods2" href="">
                    <img src="img/hotSale/3-2.png" alt="">
                    <span class="price">￥ 99.00</span>
                    <span class="baoyou">包邮</span>
                    <span class="count">月销1029笔</span>
                </a>
                <a class="goods3" href="">
                    <img src="img/hotSale/3-3.png" alt="">
                    <span class="price">￥ 590.00</span>
                    <span class="count">月销5笔</span>
                </a>
                <!-- shade2 -->
                <div class="shade2">
                    <div class="top"></div>
                    <div class="bottom"></div>
                </div>
                <p class="shade-p2">邦致 男士皮鞋 感恩回馈</p>
                <a class="shade-a2" href="#">去看看</a>
                <!-- shade3 -->
                <div class="shade3">
                    <div class="top"></div>
                    <div class="bottom"></div>
                </div>
                <p class="shade-p3">狂欢特价：全新大炮</p>
                <a class="shade-a3" href="#">去看看</a>
            </div>
        </div>
    </div>
    <div id="hotSaleBottom">
        <img src="img/hotSaleBottom/1.png" alt="">
        <img src="img/hotSaleBottom/2.png" alt="">
        <img src="img/hotSaleBottom/3.png" alt="">
    </div>
    <div id="guessYouLike">
        <div class="title">
            <h2>猜你喜欢</h2>
            <p>实时推荐最适合你的宝贝</p>
        </div>
        <ul>
            <!-- 1 -->
            <li>
                <a href="#">
                    <div class="wrap">
                        <div class="content">
                            <img src="" alt="">
                            <p>Nina出口法国家具 超美仿古单人沙发扶手椅棕色 条纹最后一个现货</p>
                            <span class="price">￥2249.1</span>
                        </div>
                        <!-- 遮罩 -->
                        <div class="shade"></div>
                        <!-- 遮罩内的文字内容 -->
                        <div class="seeMore">
                            <h3>找相似</h3>
                            <p>发现更多相似的宝贝</p>
                        </div>
                    </div>
                </a>
            </li>
            <!-- 2 -->
            <li>
                <a href="#">
                    <div class="wrap">
                        <div class="content">
                            <img src="img/guessYouLike/1.png" alt="">
                            <p>Nina出口法国家具 超美仿古单人沙发扶手椅棕色 条纹最后一个现货</p>
                            <span class="price">￥2249.1</span>
                            <span class="count">销量:1</span>
                        </div>
                        <!-- 遮罩 -->
                        <div class="shade"></div>
                        <!-- 遮罩内的文字内容 -->
                        <div class="seeMore">
                            <h3>找相似</h3>
                            <p>发现更多相似的宝贝</p>
                        </div>
                    </div>
                </a>
            </li>
            <li>
                <a href="#">
                    <div class="wrap">
                        <div class="content">
                            <img src="img/guessYouLike/1.png" alt="">
                            <p>Nina出口法国家具 超美仿古单人沙发扶手椅棕色 条纹最后一个现货</p>
                            <span class="hot">HOT</span>
                            <span class="price">￥2249.1</span>
                            <span class="count">销量:1</span>
                        </div>
                        <!-- 遮罩 -->
                        <div class="shade"></div>
                        <!-- 遮罩内的文字内容 -->
                        <div class="seeMore">
                            <h3>找相似</h3>
                            <p>发现更多相似的宝贝</p>
                        </div>
                    </div>
                </a>
            </li>
            <li>
                <a href="#">
                    <div class="wrap">
                        <div class="content">
                            <img src="img/guessYouLike/1.png" alt="">
                            <p>Nina出口法国家具 超美仿古单人沙发扶手椅棕色 条纹最后一个现货</p>
                            <span class="price">￥2249.1</span>
                        </div>
                        <!-- 遮罩 -->
                        <div class="shade"></div>
                        <!-- 遮罩内的文字内容 -->
                        <div class="seeMore">
                            <h3>找相似</h3>
                            <p>发现更多相似的宝贝</p>
                        </div>
                    </div>
                </a>
            </li>
            <li>
                <a href="#">
                    <div class="wrap">
                        <div class="content">
                            <img src="img/guessYouLike/1.png" alt="">
                            <p>Nina出口法国家具 超美仿古单人沙发扶手椅棕色 条纹最后一个现货</p>
                            <span class="price">￥2249.1</span>
                        </div>
                        <!-- 遮罩 -->
                        <div class="shade"></div>
                        <!-- 遮罩内的文字内容 -->
                        <div class="seeMore">
                            <h3>找相似</h3>
                            <p>发现更多相似的宝贝</p>
                        </div>
                    </div>
                </a>
            </li>
            <li>
                <a href="#">
                    <div class="wrap">
                        <div class="content">
                            <img src="img/guessYouLike/1.png" alt="">
                            <p>Nina出口法国家具 超美仿古单人沙发扶手椅棕色 条纹最后一个现货</p>
                            <span class="price">￥2249.1</span>
                        </div>
                        <!-- 遮罩 -->
                        <div class="shade"></div>
                        <!-- 遮罩内的文字内容 -->
                        <div class="seeMore">
                            <h3>找相似</h3>
                            <p>发现更多相似的宝贝</p>
                        </div>
                    </div>
                </a>
            </li>
            <li>
                <a href="#">
                    <div class="wrap">
                        <div class="content">
                            <img src="img/guessYouLike/1.png" alt="">
                            <p>Nina出口法国家具 超美仿古单人沙发扶手椅棕色 条纹最后一个现货</p>
                            <span class="price">￥2249.1</span>
                        </div>
                        <!-- 遮罩 -->
                        <div class="shade"></div>
                        <!-- 遮罩内的文字内容 -->
                        <div class="seeMore">
                            <h3>找相似</h3>
                            <p>发现更多相似的宝贝</p>
                        </div>
                    </div>
                </a>
            </li>
            <li>
                <a href="#">
                    <div class="wrap">
                        <div class="content">
                            <img src="img/guessYouLike/1.png" alt="">
                            <p>Nina出口法国家具 超美仿古单人沙发扶手椅棕色 条纹最后一个现货</p>
                            <span class="price">￥2249.1</span>
                        </div>
                        <!-- 遮罩 -->
                        <div class="shade"></div>
                        <!-- 遮罩内的文字内容 -->
                        <div class="seeMore">
                            <h3>找相似</h3>
                            <p>发现更多相似的宝贝</p>
                        </div>
                    </div>
                </a>
            </li>
            <li>
                <a href="#">
                    <div class="wrap">
                        <div class="content">
                            <img src="img/guessYouLike/1.png" alt="">
                            <p>Nina出口法国家具 超美仿古单人沙发扶手椅棕色 条纹最后一个现货</p>
                            <span class="price">￥2249.1</span>
                        </div>
                        <!-- 遮罩 -->
                        <div class="shade"></div>
                        <!-- 遮罩内的文字内容 -->
                        <div class="seeMore">
                            <h3>找相似</h3>
                            <p>发现更多相似的宝贝</p>
                        </div>
                    </div>
                </a>
            </li>
            <li>
                <a href="#">
                    <div class="wrap">
                        <div class="content">
                            <img src="img/guessYouLike/1.png" alt="">
                            <p>Nina出口法国家具 超美仿古单人沙发扶手椅棕色 条纹最后一个现货</p>
                            <span class="price">￥2249.1</span>
                        </div>
                        <!-- 遮罩 -->
                        <div class="shade"></div>
                        <!-- 遮罩内的文字内容 -->
                        <div class="seeMore">
                            <h3>找相似</h3>
                            <p>发现更多相似的宝贝</p>
                        </div>
                    </div>
                </a>
            </li>
            <li>
                <a href="#">
                    <div class="wrap">
                        <div class="content">
                            <img src="img/guessYouLike/1.png" alt="">
                            <p>Nina出口法国家具 超美仿古单人沙发扶手椅棕色 条纹最后一个现货</p>
                            <span class="price">￥2249.1</span>
                        </div>
                        <!-- 遮罩 -->
                        <div class="shade"></div>
                        <!-- 遮罩内的文字内容 -->
                        <div class="seeMore">
                            <h3>找相似</h3>
                            <p>发现更多相似的宝贝</p>
                        </div>
                    </div>
                </a>
            </li>
            <li>
                <a href="#">
                    <div class="wrap">
                        <div class="content">
                            <img src="img/guessYouLike/1.png" alt="">
                            <p>Nina出口法国家具 超美仿古单人沙发扶手椅棕色 条纹最后一个现货</p>
                            <span class="price">￥2249.1</span>
                        </div>
                        <!-- 遮罩 -->
                        <div class="shade"></div>
                        <!-- 遮罩内的文字内容 -->
                        <div class="seeMore">
                            <h3>找相似</h3>
                            <p>发现更多相似的宝贝</p>
                        </div>
                    </div>
                </a>
            </li>
            <li>
                <a href="#">
                    <div class="wrap">
                        <div class="content">
                            <img src="img/guessYouLike/1.png" alt="">
                            <p>Nina出口法国家具 超美仿古单人沙发扶手椅棕色 条纹最后一个现货</p>
                            <span class="price">￥2249.1</span>
                        </div>
                        <!-- 遮罩 -->
                        <div class="shade"></div>
                        <!-- 遮罩内的文字内容 -->
                        <div class="seeMore">
                            <h3>找相似</h3>
                            <p>发现更多相似的宝贝</p>
                        </div>
                    </div>
                </a>
            </li>
            <li>
                <a href="#">
                    <div class="wrap">
                        <div class="content">
                            <img src="img/guessYouLike/1.png" alt="">
                            <p>Nina出口法国家具 超美仿古单人沙发扶手椅棕色 条纹最后一个现货</p>
                            <span class="price">￥2249.1</span>
                        </div>
                        <!-- 遮罩 -->
                        <div class="shade"></div>
                        <!-- 遮罩内的文字内容 -->
                        <div class="seeMore">
                            <h3>找相似</h3>
                            <p>发现更多相似的宝贝</p>
                        </div>
                    </div>
                </a>
            </li>
            <li>
                <a href="#">
                    <div class="wrap">
                        <div class="content">
                            <img src="img/guessYouLike/1.png" alt="">
                            <p>Nina出口法国家具 超美仿古单人沙发扶手椅棕色 条纹最后一个现货</p>
                            <span class="price">￥2249.1</span>
                        </div>
                        <!-- 遮罩 -->
                        <div class="shade"></div>
                        <!-- 遮罩内的文字内容 -->
                        <div class="seeMore">
                            <h3>找相似</h3>
                            <p>发现更多相似的宝贝</p>
                        </div>
                    </div>
                </a>
            </li>
            <li>
                <a href="#">
                    <div class="wrap">
                        <div class="content">
                            <img src="img/guessYouLike/1.png" alt="">
                            <p>Nina出口法国家具 超美仿古单人沙发扶手椅棕色 条纹最后一个现货</p>
                            <span class="price">￥2249.1</span>
                        </div>
                        <!-- 遮罩 -->
                        <div class="shade"></div>
                        <!-- 遮罩内的文字内容 -->
                        <div class="seeMore">
                            <h3>找相似</h3>
                            <p>发现更多相似的宝贝</p>
                        </div>
                    </div>
                </a>
            </li>
            <li>
                <a href="#">
                    <div class="wrap">
                        <div class="content">
                            <img src="img/guessYouLike/1.png" alt="">
                            <p>Nina出口法国家具 超美仿古单人沙发扶手椅棕色 条纹最后一个现货</p>
                            <span class="price">￥2249.1</span>
                        </div>
                        <!-- 遮罩 -->
                        <div class="shade"></div>
                        <!-- 遮罩内的文字内容 -->
                        <div class="seeMore">
                            <h3>找相似</h3>
                            <p>发现更多相似的宝贝</p>
                        </div>
                    </div>
                </a>
            </li>
            <li>
                <a href="#">
                    <div class="wrap">
                        <div class="content">
                            <img src="img/guessYouLike/1.png" alt="">
                            <p>Nina出口法国家具 超美仿古单人沙发扶手椅棕色 条纹最后一个现货</p>
                            <span class="price">￥2249.1</span>
                        </div>
                        <!-- 遮罩 -->
                        <div class="shade"></div>
                        <!-- 遮罩内的文字内容 -->
                        <div class="seeMore">
                            <h3>找相似</h3>
                            <p>发现更多相似的宝贝</p>
                        </div>
                    </div>
                </a>
            </li>
            <li>
                <a href="#">
                    <div class="wrap">
                        <div class="content">
                            <img src="img/guessYouLike/1.png" alt="">
                            <p>Nina出口法国家具 超美仿古单人沙发扶手椅棕色 条纹最后一个现货</p>
                            <span class="price">￥2249.1</span>
                        </div>
                        <!-- 遮罩 -->
                        <div class="shade"></div>
                        <!-- 遮罩内的文字内容 -->
                        <div class="seeMore">
                            <h3>找相似</h3>
                            <p>发现更多相似的宝贝</p>
                        </div>
                    </div>
                </a>
            </li>
            <li>
                <a href="#">
                    <div class="wrap">
                        <div class="content">
                            <img src="img/guessYouLike/1.png" alt="">
                            <p>Nina出口法国家具 超美仿古单人沙发扶手椅棕色 条纹最后一个现货</p>
                            <span class="price">￥2249.1</span>
                        </div>
                        <!-- 遮罩 -->
                        <div class="shade"></div>
                        <!-- 遮罩内的文字内容 -->
                        <div class="seeMore">
                            <h3>找相似</h3>
                            <p>发现更多相似的宝贝</p>
                        </div>
                    </div>
                </a>
            </li>
            <li>
                <a href="#">
                    <div class="wrap">
                        <div class="content">
                            <img src="img/guessYouLike/1.png" alt="">
                            <p>Nina出口法国家具 超美仿古单人沙发扶手椅棕色 条纹最后一个现货</p>
                            <span class="price">￥2249.1</span>
                        </div>
                        <!-- 遮罩 -->
                        <div class="shade"></div>
                        <!-- 遮罩内的文字内容 -->
                        <div class="seeMore">
                            <h3>找相似</h3>
                            <p>发现更多相似的宝贝</p>
                        </div>
                    </div>
                </a>
            </li>
            <li>
                <a href="#">
                    <div class="wrap">
                        <div class="content">
                            <img src="img/guessYouLike/1.png" alt="">
                            <p>Nina出口法国家具 超美仿古单人沙发扶手椅棕色 条纹最后一个现货</p>
                            <span class="price">￥2249.1</span>
                        </div>
                        <!-- 遮罩 -->
                        <div class="shade"></div>
                        <!-- 遮罩内的文字内容 -->
                        <div class="seeMore">
                            <h3>找相似</h3>
                            <p>发现更多相似的宝贝</p>
                        </div>
                    </div>
                </a>
            </li>
            <li>
                <a href="#">
                    <div class="wrap">
                        <div class="content">
                            <img src="img/guessYouLike/1.png" alt="">
                            <p>Nina出口法国家具 超美仿古单人沙发扶手椅棕色 条纹最后一个现货</p>
                            <span class="price">￥2249.1</span>
                        </div>
                        <!-- 遮罩 -->
                        <div class="shade"></div>
                        <!-- 遮罩内的文字内容 -->
                        <div class="seeMore">
                            <h3>找相似</h3>
                            <p>发现更多相似的宝贝</p>
                        </div>
                    </div>
                </a>
            </li>
            <li>
                <a href="#">
                    <div class="wrap">
                        <div class="content">
                            <img src="img/guessYouLike/1.png" alt="">
                            <p>Nina出口法国家具 超美仿古单人沙发扶手椅棕色 条纹最后一个现货</p>
                            <span class="price">￥2249.1</span>
                        </div>
                        <!-- 遮罩 -->
                        <div class="shade"></div>
                        <!-- 遮罩内的文字内容 -->
                        <div class="seeMore">
                            <h3>找相似</h3>
                            <p>发现更多相似的宝贝</p>
                        </div>
                    </div>
                </a>
            </li>
            <li>
                <a href="#">
                    <div class="wrap">
                        <div class="content">
                            <img src="img/guessYouLike/1.png" alt="">
                            <p>Nina出口法国家具 超美仿古单人沙发扶手椅棕色 条纹最后一个现货</p>
                            <span class="price">￥2249.1</span>
                        </div>
                        <!-- 遮罩 -->
                        <div class="shade"></div>
                        <!-- 遮罩内的文字内容 -->
                        <div class="seeMore">
                            <h3>找相似</h3>
                            <p>发现更多相似的宝贝</p>
                        </div>
                    </div>
                </a>
            </li>
            <li>
                <a href="#">
                    <div class="wrap">
                        <div class="content">
                            <img src="img/guessYouLike/1.png" alt="">
                            <p>Nina出口法国家具 超美仿古单人沙发扶手椅棕色 条纹最后一个现货</p>
                            <span class="price">￥2249.1</span>
                        </div>
                        <!-- 遮罩 -->
                        <div class="shade"></div>
                        <!-- 遮罩内的文字内容 -->
                        <div class="seeMore">
                            <h3>找相似</h3>
                            <p>发现更多相似的宝贝</p>
                        </div>
                    </div>
                </a>
            </li>
            <li>
                <a href="#">
                    <div class="wrap">
                        <div class="content">
                            <img src="img/guessYouLike/1.png" alt="">
                            <p>Nina出口法国家具 超美仿古单人沙发扶手椅棕色 条纹最后一个现货</p>
                            <span class="price">￥2249.1</span>
                        </div>
                        <!-- 遮罩 -->
                        <div class="shade"></div>
                        <!-- 遮罩内的文字内容 -->
                        <div class="seeMore">
                            <h3>找相似</h3>
                            <p>发现更多相似的宝贝</p>
                        </div>
                    </div>
                </a>
            </li>
            <li>
                <a href="#">
                    <div class="wrap">
                        <div class="content">
                            <img src="img/guessYouLike/1.png" alt="">
                            <p>Nina出口法国家具 超美仿古单人沙发扶手椅棕色 条纹最后一个现货</p>
                            <span class="price">￥2249.1</span>
                        </div>
                        <!-- 遮罩 -->
                        <div class="shade"></div>
                        <!-- 遮罩内的文字内容 -->
                        <div class="seeMore">
                            <h3>找相似</h3>
                            <p>发现更多相似的宝贝</p>
                        </div>
                    </div>
                </a>
            </li>
            <li>
                <a href="#">
                    <div class="wrap">
                        <div class="content">
                            <img src="img/guessYouLike/1.png" alt="">
                            <p>Nina出口法国家具 超美仿古单人沙发扶手椅棕色 条纹最后一个现货</p>
                            <span class="price">￥2249.1</span>
                        </div>
                        <!-- 遮罩 -->
                        <div class="shade"></div>
                        <!-- 遮罩内的文字内容 -->
                        <div class="seeMore">
                            <h3>找相似</h3>
                            <p>发现更多相似的宝贝</p>
                        </div>
                    </div>
                </a>
            </li>
            <li>
                <a href="#">
                    <div class="wrap">
                        <div class="content">
                            <img src="img/guessYouLike/1.png" alt="">
                            <p>Nina出口法国家具 超美仿古单人沙发扶手椅棕色 条纹最后一个现货</p>
                            <span class="price">￥2249.1</span>
                        </div>
                        <!-- 遮罩 -->
                        <div class="shade"></div>
                        <!-- 遮罩内的文字内容 -->
                        <div class="seeMore">
                            <h3>找相似</h3>
                            <p>发现更多相似的宝贝</p>
                        </div>
                    </div>
                </a>
            </li>
            <li>
                <a href="#">
                    <div class="wrap">
                        <div class="content">
                            <img src="img/guessYouLike/1.png" alt="">
                            <p>Nina出口法国家具 超美仿古单人沙发扶手椅棕色 条纹最后一个现货</p>
                            <span class="price">￥2249.1</span>
                        </div>
                        <!-- 遮罩 -->
                        <div class="shade"></div>
                        <!-- 遮罩内的文字内容 -->
                        <div class="seeMore">
                            <h3>找相似</h3>
                            <p>发现更多相似的宝贝</p>
                        </div>
                    </div>
                </a>
            </li>
            <li>
                <a href="#">
                    <div class="wrap">
                        <div class="content">
                            <img src="img/guessYouLike/1.png" alt="">
                            <p>Nina出口法国家具 超美仿古单人沙发扶手椅棕色 条纹最后一个现货</p>
                            <span class="price">￥2249.1</span>
                        </div>
                        <!-- 遮罩 -->
                        <div class="shade"></div>
                        <!-- 遮罩内的文字内容 -->
                        <div class="seeMore">
                            <h3>找相似</h3>
                            <p>发现更多相似的宝贝</p>
                        </div>
                    </div>
                </a>
            </li>
            <li>
                <a href="#">
                    <div class="wrap">
                        <div class="content">
                            <img src="img/guessYouLike/1.png" alt="">
                            <p>Nina出口法国家具 超美仿古单人沙发扶手椅棕色 条纹最后一个现货</p>
                            <span class="price">￥2249.1</span>
                        </div>
                        <!-- 遮罩 -->
                        <div class="shade"></div>
                        <!-- 遮罩内的文字内容 -->
                        <div class="seeMore">
                            <h3>找相似</h3>
                            <p>发现更多相似的宝贝</p>
                        </div>
                    </div>
                </a>
            </li>
            <li>
                <a href="#">
                    <div class="wrap">
                        <div class="content">
                            <img src="img/guessYouLike/1.png" alt="">
                            <p>Nina出口法国家具 超美仿古单人沙发扶手椅棕色 条纹最后一个现货</p>
                            <span class="price">￥2249.1</span>
                        </div>
                        <!-- 遮罩 -->
                        <div class="shade"></div>
                        <!-- 遮罩内的文字内容 -->
                        <div class="seeMore">
                            <h3>找相似</h3>
                            <p>发现更多相似的宝贝</p>
                        </div>
                    </div>
                </a>
            </li>
            <li>
                <a href="#">
                    <div class="wrap">
                        <div class="content">
                            <img src="img/guessYouLike/1.png" alt="">
                            <p>Nina出口法国家具 超美仿古单人沙发扶手椅棕色 条纹最后一个现货</p>
                            <span class="price">￥2249.1</span>
                        </div>
                        <!-- 遮罩 -->
                        <div class="shade"></div>
                        <!-- 遮罩内的文字内容 -->
                        <div class="seeMore">
                            <h3>找相似</h3>
                            <p>发现更多相似的宝贝</p>
                        </div>
                    </div>
                </a>
            </li>
            <li>
                <a href="#">
                    <div class="wrap">
                        <div class="content">
                            <img src="img/guessYouLike/1.png" alt="">
                            <p>Nina出口法国家具 超美仿古单人沙发扶手椅棕色 条纹最后一个现货</p>
                            <span class="price">￥2249.1</span>
                        </div>
                        <!-- 遮罩 -->
                        <div class="shade"></div>
                        <!-- 遮罩内的文字内容 -->
                        <div class="seeMore">
                            <h3>找相似</h3>
                            <p>发现更多相似的宝贝</p>
                        </div>
                    </div>
                </a>
            </li>
            <li>
                <a href="#">
                    <div class="wrap">
                        <div class="content">
                            <img src="img/guessYouLike/1.png" alt="">
                            <p>Nina出口法国家具 超美仿古单人沙发扶手椅棕色 条纹最后一个现货</p>
                            <span class="price">￥2249.1</span>
                        </div>
                        <!-- 遮罩 -->
                        <div class="shade"></div>
                        <!-- 遮罩内的文字内容 -->
                        <div class="seeMore">
                            <h3>找相似</h3>
                            <p>发现更多相似的宝贝</p>
                        </div>
                    </div>
                </a>
            </li>
            <li>
                <a href="#">
                    <div class="wrap">
                        <div class="content">
                            <img src="img/guessYouLike/1.png" alt="">
                            <p>Nina出口法国家具 超美仿古单人沙发扶手椅棕色 条纹最后一个现货</p>
                            <span class="price">￥2249.1</span>
                        </div>
                        <!-- 遮罩 -->
                        <div class="shade"></div>
                        <!-- 遮罩内的文字内容 -->
                        <div class="seeMore">
                            <h3>找相似</h3>
                            <p>发现更多相似的宝贝</p>
                        </div>
                    </div>
                </a>
            </li>
            <li>
                <a href="#">
                    <div class="wrap">
                        <div class="content">
                            <img src="img/guessYouLike/1.png" alt="">
                            <p>Nina出口法国家具 超美仿古单人沙发扶手椅棕色 条纹最后一个现货</p>
                            <span class="price">￥2249.1</span>
                        </div>
                        <!-- 遮罩 -->
                        <div class="shade"></div>
                        <!-- 遮罩内的文字内容 -->
                        <div class="seeMore">
                            <h3>找相似</h3>
                            <p>发现更多相似的宝贝</p>
                        </div>
                    </div>
                </a>
            </li>
            <li>
                <a href="#">
                    <div class="wrap">
                        <div class="content">
                            <img src="img/guessYouLike/1.png" alt="">
                            <p>Nina出口法国家具 超美仿古单人沙发扶手椅棕色 条纹最后一个现货</p>
                            <span class="price">￥2249.1</span>
                        </div>
                        <!-- 遮罩 -->
                        <div class="shade"></div>
                        <!-- 遮罩内的文字内容 -->
                        <div class="seeMore">
                            <h3>找相似</h3>
                            <p>发现更多相似的宝贝</p>
                        </div>
                    </div>
                </a>
            </li>
            <li>
                <a href="#">
                    <div class="wrap">
                        <div class="content">
                            <img src="img/guessYouLike/1.png" alt="">
                            <p>Nina出口法国家具 超美仿古单人沙发扶手椅棕色 条纹最后一个现货</p>
                            <span class="price">￥2249.1</span>
                        </div>
                        <!-- 遮罩 -->
                        <div class="shade"></div>
                        <!-- 遮罩内的文字内容 -->
                        <div class="seeMore">
                            <h3>找相似</h3>
                            <p>发现更多相似的宝贝</p>
                        </div>
                    </div>
                </a>
            </li>
            <li>
                <a href="#">
                    <div class="wrap">
                        <div class="content">
                            <img src="img/guessYouLike/1.png" alt="">
                            <p>Nina出口法国家具 超美仿古单人沙发扶手椅棕色 条纹最后一个现货</p>
                            <span class="price">￥2249.1</span>
                        </div>
                        <!-- 遮罩 -->
                        <div class="shade"></div>
                        <!-- 遮罩内的文字内容 -->
                        <div class="seeMore">
                            <h3>找相似</h3>
                            <p>发现更多相似的宝贝</p>
                        </div>
                    </div>
                </a>
            </li>
            <li>
                <a href="#">
                    <div class="wrap">
                        <div class="content">
                            <img src="img/guessYouLike/1.png" alt="">
                            <p>Nina出口法国家具 超美仿古单人沙发扶手椅棕色 条纹最后一个现货</p>
                            <span class="price">￥2249.1</span>
                        </div>
                        <!-- 遮罩 -->
                        <div class="shade"></div>
                        <!-- 遮罩内的文字内容 -->
                        <div class="seeMore">
                            <h3>找相似</h3>
                            <p>发现更多相似的宝贝</p>
                        </div>
                    </div>
                </a>
            </li>
            <li>
                <a href="#">
                    <div class="wrap">
                        <div class="content">
                            <img src="img/guessYouLike/1.png" alt="">
                            <p>Nina出口法国家具 超美仿古单人沙发扶手椅棕色 条纹最后一个现货</p>
                            <span class="price">￥2249.1</span>
                        </div>
                        <!-- 遮罩 -->
                        <div class="shade"></div>
                        <!-- 遮罩内的文字内容 -->
                        <div class="seeMore">
                            <h3>找相似</h3>
                            <p>发现更多相似的宝贝</p>
                        </div>
                    </div>
                </a>
            </li>
            <li>
                <a href="#">
                    <div class="wrap">
                        <div class="content">
                            <img src="img/guessYouLike/1.png" alt="">
                            <p>Nina出口法国家具 超美仿古单人沙发扶手椅棕色 条纹最后一个现货</p>
                            <span class="price">￥2249.1</span>
                        </div>
                        <!-- 遮罩 -->
                        <div class="shade"></div>
                        <!-- 遮罩内的文字内容 -->
                        <div class="seeMore">
                            <h3>找相似</h3>
                            <p>发现更多相似的宝贝</p>
                        </div>
                    </div>
                </a>
            </li>
            <li>
                <a href="#">
                    <div class="wrap">
                        <div class="content">
                            <img src="img/guessYouLike/1.png" alt="">
                            <p>Nina出口法国家具 超美仿古单人沙发扶手椅棕色 条纹最后一个现货</p>
                            <span class="price">￥2249.1</span>
                        </div>
                        <!-- 遮罩 -->
                        <div class="shade"></div>
                        <!-- 遮罩内的文字内容 -->
                        <div class="seeMore">
                            <h3>找相似</h3>
                            <p>发现更多相似的宝贝</p>
                        </div>
                    </div>
                </a>
            </li>
            <li>
                <a href="#">
                    <div class="wrap">
                        <div class="content">
                            <img src="img/guessYouLike/1.png" alt="">
                            <p>Nina出口法国家具 超美仿古单人沙发扶手椅棕色 条纹最后一个现货</p>
                            <span class="price">￥2249.1</span>
                        </div>
                        <!-- 遮罩 -->
                        <div class="shade"></div>
                        <!-- 遮罩内的文字内容 -->
                        <div class="seeMore">
                            <h3>找相似</h3>
                            <p>发现更多相似的宝贝</p>
                        </div>
                    </div>
                </a>
            </li>
            <li>
                <a href="#">
                    <div class="wrap">
                        <div class="content">
                            <img src="img/guessYouLike/1.png" alt="">
                            <p>Nina出口法国家具 超美仿古单人沙发扶手椅棕色 条纹最后一个现货</p>
                            <span class="price">￥2249.1</span>
                        </div>
                        <!-- 遮罩 -->
                        <div class="shade"></div>
                        <!-- 遮罩内的文字内容 -->
                        <div class="seeMore">
                            <h3>找相似</h3>
                            <p>发现更多相似的宝贝</p>
                        </div>
                    </div>
                </a>
            </li>
            <li>
                <a href="#">
                    <div class="wrap">
                        <div class="content">
                            <img src="img/guessYouLike/1.png" alt="">
                            <p>Nina出口法国家具 超美仿古单人沙发扶手椅棕色 条纹最后一个现货</p>
                            <span class="price">￥2249.1</span>
                        </div>
                        <!-- 遮罩 -->
                        <div class="shade"></div>
                        <!-- 遮罩内的文字内容 -->
                        <div class="seeMore">
                            <h3>找相似</h3>
                            <p>发现更多相似的宝贝</p>
                        </div>
                    </div>
                </a>
            </li>
            <li>
                <a href="#">
                    <div class="wrap">
                        <div class="content">
                            <img src="img/guessYouLike/1.png" alt="">
                            <p>Nina出口法国家具 超美仿古单人沙发扶手椅棕色 条纹最后一个现货</p>
                            <span class="price">￥2249.1</span>
                        </div>
                        <!-- 遮罩 -->
                        <div class="shade"></div>
                        <!-- 遮罩内的文字内容 -->
                        <div class="seeMore">
                            <h3>找相似</h3>
                            <p>发现更多相似的宝贝</p>
                        </div>
                    </div>
                </a>
            </li>
            <li>
                <a href="#">
                    <div class="wrap">
                        <div class="content">
                            <img src="img/guessYouLike/1.png" alt="">
                            <p>Nina出口法国家具 超美仿古单人沙发扶手椅棕色 条纹最后一个现货</p>
                            <span class="price">￥2249.1</span>
                        </div>
                        <!-- 遮罩 -->
                        <div class="shade"></div>
                        <!-- 遮罩内的文字内容 -->
                        <div class="seeMore">
                            <h3>找相似</h3>
                            <p>发现更多相似的宝贝</p>
                        </div>
                    </div>
                </a>
            </li>
            <li>
                <a href="#">
                    <div class="wrap">
                        <div class="content">
                            <img src="img/guessYouLike/1.png" alt="">
                            <p>Nina出口法国家具 超美仿古单人沙发扶手椅棕色 条纹最后一个现货</p>
                            <span class="price">￥2249.1</span>
                        </div>
                        <!-- 遮罩 -->
                        <div class="shade"></div>
                        <!-- 遮罩内的文字内容 -->
                        <div class="seeMore">
                            <h3>找相似</h3>
                            <p>发现更多相似的宝贝</p>
                        </div>
                    </div>
                </a>
            </li>
            <li>
                <a href="#">
                    <div class="wrap">
                        <div class="content">
                            <img src="img/guessYouLike/1.png" alt="">
                            <p>Nina出口法国家具 超美仿古单人沙发扶手椅棕色 条纹最后一个现货</p>
                            <span class="price">￥2249.1</span>
                        </div>
                        <!-- 遮罩 -->
                        <div class="shade"></div>
                        <!-- 遮罩内的文字内容 -->
                        <div class="seeMore">
                            <h3>找相似</h3>
                            <p>发现更多相似的宝贝</p>
                        </div>
                    </div>
                </a>
            </li>
            <li>
                <a href="#">
                    <div class="wrap">
                        <div class="content">
                            <img src="img/guessYouLike/1.png" alt="">
                            <p>Nina出口法国家具 超美仿古单人沙发扶手椅棕色 条纹最后一个现货</p>
                            <span class="price">￥2249.1</span>
                        </div>
                        <!-- 遮罩 -->
                        <div class="shade"></div>
                        <!-- 遮罩内的文字内容 -->
                        <div class="seeMore">
                            <h3>找相似</h3>
                            <p>发现更多相似的宝贝</p>
                        </div>
                    </div>
                </a>
            </li>
            <li>
                <a href="#">
                    <div class="wrap">
                        <div class="content">
                            <img src="img/guessYouLike/1.png" alt="">
                            <p>Nina出口法国家具 超美仿古单人沙发扶手椅棕色 条纹最后一个现货</p>
                            <span class="price">￥2249.1</span>
                        </div>
                        <!-- 遮罩 -->
                        <div class="shade"></div>
                        <!-- 遮罩内的文字内容 -->
                        <div class="seeMore">
                            <h3>找相似</h3>
                            <p>发现更多相似的宝贝</p>
                        </div>
                    </div>
                </a>
            </li>
            <li>
                <a href="#">
                    <div class="wrap">
                        <div class="content">
                            <img src="img/guessYouLike/1.png" alt="">
                            <p>Nina出口法国家具 超美仿古单人沙发扶手椅棕色 条纹最后一个现货</p>
                            <span class="price">￥2249.1</span>
                        </div>
                        <!-- 遮罩 -->
                        <div class="shade"></div>
                        <!-- 遮罩内的文字内容 -->
                        <div class="seeMore">
                            <h3>找相似</h3>
                            <p>发现更多相似的宝贝</p>
                        </div>
                    </div>
                </a>
            </li>
            <li>
                <a href="#">
                    <div class="wrap">
                        <div class="content">
                            <img src="img/guessYouLike/1.png" alt="">
                            <p>Nina出口法国家具 超美仿古单人沙发扶手椅棕色 条纹最后一个现货</p>
                            <span class="price">￥2249.1</span>
                        </div>
                        <!-- 遮罩 -->
                        <div class="shade"></div>
                        <!-- 遮罩内的文字内容 -->
                        <div class="seeMore">
                            <h3>找相似</h3>
                            <p>发现更多相似的宝贝</p>
                        </div>
                    </div>
                </a>
            </li>
            <li>
                <a href="#">
                    <div class="wrap">
                        <div class="content">
                            <img src="img/guessYouLike/1.png" alt="">
                            <p>Nina出口法国家具 超美仿古单人沙发扶手椅棕色 条纹最后一个现货</p>
                            <span class="price">￥2249.1</span>
                        </div>
                        <!-- 遮罩 -->
                        <div class="shade"></div>
                        <!-- 遮罩内的文字内容 -->
                        <div class="seeMore">
                            <h3>找相似</h3>
                            <p>发现更多相似的宝贝</p>
                        </div>
                    </div>
                </a>
            </li>
            <li>
                <a href="#">
                    <div class="wrap">
                        <div class="content">
                            <img src="img/guessYouLike/1.png" alt="">
                            <p>Nina出口法国家具 超美仿古单人沙发扶手椅棕色 条纹最后一个现货</p>
                            <span class="price">￥2249.1</span>
                        </div>
                        <!-- 遮罩 -->
                        <div class="shade"></div>
                        <!-- 遮罩内的文字内容 -->
                        <div class="seeMore">
                            <h3>找相似</h3>
                            <p>发现更多相似的宝贝</p>
                        </div>
                    </div>
                </a>
            </li>
            <li>
                <a href="#">
                    <div class="wrap">
                        <div class="content">
                            <img src="img/guessYouLike/1.png" alt="">
                            <p>Nina出口法国家具 超美仿古单人沙发扶手椅棕色 条纹最后一个现货</p>
                            <span class="price">￥2249.1</span>
                        </div>
                        <!-- 遮罩 -->
                        <div class="shade"></div>
                        <!-- 遮罩内的文字内容 -->
                        <div class="seeMore">
                            <h3>找相似</h3>
                            <p>发现更多相似的宝贝</p>
                        </div>
                    </div>
                </a>
            </li>
            <li>
                <a href="#">
                    <div class="wrap">
                        <div class="content">
                            <img src="img/guessYouLike/1.png" alt="">
                            <p>Nina出口法国家具 超美仿古单人沙发扶手椅棕色 条纹最后一个现货</p>
                            <span class="price">￥2249.1</span>
                        </div>
                        <!-- 遮罩 -->
                        <div class="shade"></div>
                        <!-- 遮罩内的文字内容 -->
                        <div class="seeMore">
                            <h3>找相似</h3>
                            <p>发现更多相似的宝贝</p>
                        </div>
                    </div>
                </a>
            </li>
            <li>
                <a href="#">
                    <div class="wrap">
                        <div class="content">
                            <img src="img/guessYouLike/1.png" alt="">
                            <p>Nina出口法国家具 超美仿古单人沙发扶手椅棕色 条纹最后一个现货</p>
                            <span class="price">￥2249.1</span>
                        </div>
                        <!-- 遮罩 -->
                        <div class="shade"></div>
                        <!-- 遮罩内的文字内容 -->
                        <div class="seeMore">
                            <h3>找相似</h3>
                            <p>发现更多相似的宝贝</p>
                        </div>
                    </div>
                </a>
            </li>
            <li>
                <a href="#">
                    <div class="wrap">
                        <div class="content">
                            <img src="img/guessYouLike/1.png" alt="">
                            <p>Nina出口法国家具 超美仿古单人沙发扶手椅棕色 条纹最后一个现货</p>
                            <span class="price">￥2249.1</span>
                        </div>
                        <!-- 遮罩 -->
                        <div class="shade"></div>
                        <!-- 遮罩内的文字内容 -->
                        <div class="seeMore">
                            <h3>找相似</h3>
                            <p>发现更多相似的宝贝</p>
                        </div>
                    </div>
                </a>
            </li>
            <li>
                <a href="#">
                    <div class="wrap">
                        <div class="content">
                            <img src="img/guessYouLike/1.png" alt="">
                            <p>Nina出口法国家具 超美仿古单人沙发扶手椅棕色 条纹最后一个现货</p>
                            <span class="price">￥2249.1</span>
                        </div>
                        <!-- 遮罩 -->
                        <div class="shade"></div>
                        <!-- 遮罩内的文字内容 -->
                        <div class="seeMore">
                            <h3>找相似</h3>
                            <p>发现更多相似的宝贝</p>
                        </div>
                    </div>
                </a>
            </li>
            <li>
                <a href="#">
                    <div class="wrap">
                        <div class="content">
                            <img src="img/guessYouLike/1.png" alt="">
                            <p>Nina出口法国家具 超美仿古单人沙发扶手椅棕色 条纹最后一个现货</p>
                            <span class="price">￥2249.1</span>
                        </div>
                        <!-- 遮罩 -->
                        <div class="shade"></div>
                        <!-- 遮罩内的文字内容 -->
                        <div class="seeMore">
                            <h3>找相似</h3>
                            <p>发现更多相似的宝贝</p>
                        </div>
                    </div>
                </a>
            </li>
        </ul>
        <div class="end">END</div>
    </div>
    <div id="end">
        <div class="help-wrap">
            <div class="help">
                <div class="consumer-guarantee-service">
                    <h2>消费者保障</h2>
                    <a href="#">保障范围</a>
                    <a href="#">退货退款流程</a>
                    <a href="#">服务中心</a>
                    <a href="#">更多特色服务</a>
                </div>
                <div class="new-hand">
                    <h2>新手上路</h2>
                    <a href="#">新手专区</a>
                    <a href="#">消费警示</a>
                    <a href="#">交易安全</a>
                    <a href="#">24小时在线帮助</a>
                    <a href="#">免费开店</a>
                </div>
                <div class="type-of-payment">
                    <h2>付款方式</h2>
                    <a href="#">快捷支付</a>
                    <a href="#">信用卡</a>
                    <a href="#">余额宝</a>
                    <a href="#">蚂蚁花呗</a>
                    <a href="#">货到付款</a>
                </div>
                <div class="taobao-char">
                    <h2>淘宝特色</h2>
                    <a href="#">手机淘宝</a>
                    <a href="#">旺信</a>
                    <a href="#">大众评审</a>
                    <a href="#">B格指南</a>
                </div>
            </div>
        </div>
        <div class="link-wrap">
            <div class="link">
                <ul class="ul-1">
                    <li><a href="#">阿里巴巴集团</a></li><span class="iconfont icon-shuxian"></span>
                    <li><a href="#">淘宝网</a></li><span class="iconfont icon-shuxian"></span>
                    <li><a href="#">天猫</a></li><span class="iconfont icon-shuxian"></span>
                    <li><a href="#">聚划算</a></li><span class="iconfont icon-shuxian"></span>
                    <li><a href="#">全球速卖通</a></li><span class="iconfont icon-shuxian"></span>
                    <li><a href="#">阿里巴巴国际交易市场</a></li><span class="iconfont icon-shuxian"></span>
                    <li><a href="#">1688</a></li><span class="iconfont icon-shuxian"></span>
                    <li><a href="#">阿里妈妈</a></li><span class="iconfont icon-shuxian"></span>
                    <li><a href="#">阿里旅行 去啊</a></li><span class="iconfont icon-shuxian"></span>
                    <li><a href="#">阿里云计算</a></li><span class="iconfont icon-shuxian"></span>
                    <li><a href="#">YunOS</a></li><span class="iconfont icon-shuxian"></span>
                    <li><a href="#">阿里通信</a></li><span class="iconfont icon-shuxian"></span>
                    <li><a href="#">一淘</a></li><span class="iconfont icon-shuxian"></span>
                    <li><a href="#">万网</a></li><span class="iconfont icon-shuxian"></span>
                    <li><a href="#">高德</a></li><span class="iconfont icon-shuxian"></span>
                    <li><a href="#">UC</a></li><span class="iconfont icon-shuxian"></span>
                    <li><a href="#">友盟</a></li>
                </ul>
                <ul class="ul-2">
                    <li><a href="#">虾米</a></li><span class="iconfont icon-shuxian"></span>
                    <li><a href="#">阿里星球</a></li><span class="iconfont icon-shuxian"></span>
                    <li><a href="#">来往</a></li><span class="iconfont icon-shuxian"></span>
                    <li><a href="#">钉钉</a></li><span class="iconfont icon-shuxian"></span>
                    <li><a href="#">支付宝</a></li><span class="iconfont icon-shuxian"></span>
                    <li><a href="#">优酷</a></li><span class="iconfont icon-shuxian"></span>
                    <li><a href="#">土豆</a></li><span class="iconfont icon-shuxian"></span>
                    <li><a href="#">阿里健康</a></li><span class="iconfont icon-shuxian"></span>
                    <li><a href="#">阿里影业</a></li><span class="iconfont icon-shuxian"></span>
                    <li><a href="#">阿里体育</a></li><span class="iconfont icon-shuxian"></span>
                    <li><a href="#">网商银行</a></li><span class="iconfont icon-shuxian"></span>
                </ul>
            </div>
        </div>
        <div class="trail-wrap">
            <div class="trail">
                <ul class="ul-1">
                    <li><a href="#">关于淘宝</a></li>
                    <li><a href="#">合作伙伴</a></li>
                    <li><a href="#">营销中心</a></li>
                    <li><a href="#">廉正举报</a></li>
                    <li><a href="#">联系客服</a></li>
                    <li><a href="#">开放平台</a></li>
                    <li><a href="#">诚征英才</a></li>
                    <li><a href="#">联系我们</a></li>
                    <li><a href="#">网站地图</a></li>
                    <li><a href="#">法律声明</a></li>
                    <li><a href="#">知识产权</a></li>
                    <li>
                        <p>© 2003-2016 Taobao.com 版权所有</p>
                    </li>
                </ul>
                <ul class="ul-2">
                    <li>
                        <p>网络文化经营许可证：</p>
                    </li>
                    <li><a href="#">浙网文[2013]0268-027号</a></li><span class="iconfont icon-shuxian"></span>
                    <li>
                        <p>增值电信业务经营许可证：</p>
                    </li>
                    <li><a href="#">浙B2-20080224</a></li><span class="iconfont icon-shuxian"></span>
                    <li>
                        <p>信息网络传播视听节目许可证：1109364号</p>
                    </li><span class="iconfont icon-shuxian"></span>
                    <li>
                        <p>互联网违法和不良信息举报电话:0571-81683755 blxx@list.alibaba-inc.com</p>
                    </li>
                </ul>
                <ul class="ul-3">
                    <li>
                        <a href="#"><img src="img/trail/1.png" alt=""></a>
                    </li>
                    <li>
                        <a href="#"><img src="img/trail/2.png" alt=""></a>
                    </li>
                    <li>
                        <a href="#"><img src="img/trail/3.png" alt=""></a>
                    </li>
                    <li>
                        <a href="#"><img src="img/trail/4.png" alt=""></a>
                    </li>
                    <li>
                        <a href="#"><img src="img/trail/5.png" alt=""></a>
                    </li>
                    <li>
                        <a href="#"><img src="img/trail/6.png" alt=""></a>
                    </li>
                    <li>
                        <a href="#"><img src="img/trail/7.png" alt=""></a>
                    </li>
                    <li>
                        <a href="#"><img src="img/trail/8.png" alt=""></a>
                    </li>
                    <li>
                        <a href="#"><img src="img/trail/9.png" alt=""></a>
                    </li>
                    <li>
                        <a href="#"><img src="img/trail/10.png" alt=""></a>
                    </li>
                </ul>
            </div>
        </div>
    </div>
    <!-- 引入js文件 -->
    <script type="text/javascript" src="js/move.js"></script>
    <script type="text/javascript" src="js/QR.js"></script>
    <script type="text/javascript" src="js/fixed-nav.js"></script>
    <script type="text/javascript" src="js/fixed-search.js"></script>
    <!-- <script type="text/javascript" src="js/often-visit.js"></script> -->
    <script type="text/javascript" src="js/side-nav.js"></script>
    <script type="text/javascript" src="js/slide1.js"></script>
    <script type="text/javascript" src="js/slide2.js"></script>
    <script type="text/javascript" src="js/search.js"></script>
    <script type="text/javascript" src="js/head.js"></script>
    <script type="text/javascript" src="js/side-announcement.js"></script>
    <script type="text/javascript" src="js/side-recharge.js"></script>
    <script type="text/javascript" src="js/popularity.js"></script>
    <script type="text/javascript" src="js/my-often-visit.js"></script>
    <script type="text/javascript" src="js/quality.js"></script>
    <script type="text/javascript" src="js/headline.js"></script>
    <script type="text/javascript" src="js/hotSale.js"></script>
    <script type="text/javascript" src="js/guessYouLike.js"></script>
</body>


</html>
