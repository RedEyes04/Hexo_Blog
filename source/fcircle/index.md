---
title: 朋友圈
comments: false
aside: false

---
<style>
h1 {
    display: none;
}
div#page {
    background: none !important;
    box-shadow: none;
    padding: 0;
    border: none;
}
#random-article:hover {
    border: var(--style-border-hover)!important;
}
.card:hover {
    border: var(--style-border-hover)!important;
}
#random-article {
    display: none!important;
}
#friend-circle-lite-root {
    margin-top: 10px;
}
</style>
<link rel="stylesheet" href="https://friend.redeyes.top/main/fclite.css">
<div class="author-content author-content-item fcirclePage single" style="background:url(https://bucket.redeyes.top/2024/10/12/670a68cfbb540.webp) center /cover no-repeat!important">
    <div class="card-content">
        <div class="author-content-item-tips">看看朋友们的文章📚</div><span class="author-content-item-title">朋友⭕️</span>
        <div class="content-bottom">
            <div class="tips"></div>
        </div>
        <div class="banner-button-group"><a class="banner-button" style="padding: 8px 12px;" onclick="pjax.loadUrl(&quot;/about&quot;)" data-pjax-state=""><i class="anzhiyufont anzhiyu-icon-arrow-circle-right" style="font-size:22px;margin-right:.25rem"></i><span class="banner-button-text">关于本人</span></a></div>
    </div>
</div>
<div class="title-h2-a">
    <div class="title-h2-a-left">
        <h2 style="padding-top:0;margin:.6rem 0 .6rem">🎣 钓鱼</h2><a class="random-post-start no-text-decoration" href="javascript:fetchRandomPost();" data-pjax-state="" style="transition-duration: 0.3s; transform: rotate(5400deg); opacity: 1;"><i class="anzhiyufont anzhiyu-icon-arrow-rotate-right"></i></a>
    </div>
    <div class="title-h2-a-right"><a class="random-post-all no-text-decoration" href="/link/" data-pjax-state="">全部友链</a></div>
</div>
<div id="random-post"></div>
<div class="title-h2-a">
    <div class="title-h2-a-left">
        <h2>🐟 鱼塘</h2>
    </div>
</div>
<div id="friend-circle-lite-root"></div>
<script>
    if (typeof UserConfig === 'undefined') {
        var UserConfig = {
            private_api_url: 'https://friend.redeyes.top/',
            page_turning_number: 20,
            error_img: 'https://bucket.redeyes.top/2024/10/08/6704fcec56163.gif',
        }
    }
</script>
<script src="/js/anzhiyu/random_friends_post.js"></script>
<script src="https://friend.redeyes.top//main/fclite.js"></script>