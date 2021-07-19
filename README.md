# Waterfall-Flow-Gallery
Waterfall flow gallery page. 瀑布流画廊页面。

# Features & 功能
Automatically adjust the appropriate layout according to the size of the images, and have a responsive side navigation menu. Support lazy loading of images, click on images to zoom, download pictures, and copy text.

根据图片的尺寸自动调整合适的排版，拥有响应式侧边导航菜单。支持延迟加载图片，点击图片放大，下载图片，复制文本。

# Demo & 演示

[瀑布流画廊页面](https://dev-coco.github.io/other/Waterfall-Flow-Gallery)

# Setup & 设置
```html
<div class="block" >
    <!-- Put an image link between the quotes in data-src. -->
    <img class="yall_lazy" data-src="">
    
    <!-- Put the image download link between the quotation marks in window.open. -->
    <button onclick="window.open('')">下载</button>
    
    <!-- Put the copied text between the quotation marks of data-clipboard-text. -->
    <!-- Put the displayed text in the middle of the p element.-->
    <p class="text" data-clipboard-text=""></p>
</div>
```

