# oneslide
一个markdown在线制作精美PPT在线工具

[效果预览](https://jirengu.github.io/new-oneslide/dist)

## 使用方法
鼠标放在屏幕左上角，展示配置按钮，点开即可使用

## 特点

1. 完全使用Markdown语法，制作PPT极致便捷
2. 各种主题和精美特效，使用极其方便
3. 支持图片上传
4. 支持远程拉取Markdown线上文件
5. 支持本地存储
6. 开箱即用，无需注册，无后端，无隐私泄漏
7. 支持移动端、下载PDF、旁白模式等

## 说明

- 一个#表示一级标题，同时其下的内容表示左右分页里一页的内容
- 两个#表示二级标题，同时其下的内容表示左右分页里一页的内容
- 三个#表示三级标题，同时其下的内容表示上下分页里一页的内容
- 文件上传后可自动得到`![](https://imgs.xiedaimala.com/LIjzPBygsVKz98q2eojsADUuyrxX1fUz/%25E9%25A5%25A5%25E4%25BA%25BA%25E8%25B0%25B7%2520logo.png)   <!-- .element: style="height:100px; " --> `这种地址，其中`<!-- .element: style="height:100px; " -->`表示给当前图片设置样式，也可添加其它属性
- 如想使用特殊效果，可参考范例
  - 如代码后的 `[7-9|10-12|12-15]`表示代码可按行分段亮亮展示
  - 标题下的`<!-- .slide: data-auto-animate -->` 表示当前页面如果切到下一页，相同的部分会有过渡动画，不同的部分会展示。总之可出现很棒的效果
  - 文字后的`<!-- .element: class="fragment" -->`表示给当前元素添加class，`fragment`这个class能让元素一步一步展示，而不是一次性展示
  - 如果想给元素添加样式，可以举一反三如`<!-- .element: style="color:red" -->`
  - 标题下的`<!-- .slide: class="column-2" -->` 可让当前页面两栏展示
  - `*内容*` 会让内容文字更小。 也可以用`<small>内容</small>`
  - 预置了一些常用的颜色标签，如`<yellow>`、`<red>`、`<green>`、`<grey>`等

尽情体验吧！


## 最后
本项目基于Reveal.js开发，开发者：若愚@饥人谷。
