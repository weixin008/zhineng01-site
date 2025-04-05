# 知能AI导航站说明文档

## 部署更新

1. 本地修改后推送:
```bash
git add .
git commit -m "更新内容说明"
git push origin main
```
2.等待 GitHub Pages 自动部署(通常需要1-2分钟)
## 添加广告位置示例
1. 搜索框上方
```html
<!-- 搜索框上方 -->
<div class="header-big post-top css-color mb-4" id="search-bg" style="">
    <!-- 广告位1 -->
    <div class="ad-container">
        <script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-xxxxx"
             crossorigin="anonymous"></script>
        <ins class="adsbygoogle"
             style="display:block"
             data-ad-client="ca-pub-xxxxx"
             data-ad-slot="xxxxx"
             data-ad-format="auto"
             data-full-width-responsive="true"></ins>
        <script>
             (adsbygoogle = window.adsbygoogle || []).push({});
        </script>
    </div>
    
    <div style="font-size:12px">
        <h1 style="font-size:18px;text-align: center;">知能 AI导航</h1>
    </div>
</div>
```
3.分类区域之间:
```html
<div class="row">
    <!-- 原有分类内容 -->
    
    <!-- 广告位2 -->
    <div class="col-12 mb-4">
        <div class="ad-container">
            <script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-xxxxx"
                 crossorigin="anonymous"></script>
            <ins class="adsbygoogle"
                 style="display:block"
                 data-ad-client="ca-pub-xxxxx"
                 data-ad-slot="xxxxx"
                 data-ad-format="auto"
                 data-full-width-responsive="true"></ins>
            <script>
                 (adsbygoogle = window.adsbygoogle || []).push({});
            </script>
        </div>
    </div>
    
    <!-- 下一个分类内容 -->
</div>
```
## 注意事项
1. 广告代码中的 client-id 和 slot-id 需要替换为自己的
2. 建议不要放置过多广告,以免影响用户体验
3. 可以通过 CSS 调整广告容器样式
4. 推送前本地测试确保页面布局正常
