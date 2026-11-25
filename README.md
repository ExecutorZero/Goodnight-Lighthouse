# 晚安灯塔 · Goodnight Lighthouse

> ⚠️ **内容警告 / Content Warning**
>
> 本页面包含**闪光、突脸（jump scare）、失真音效**等恐怖要素。
> 如果你有心脏病、癫痫（尤其是光敏性癫痫）或类似疾病，**请不要打开它**。
>
> This site contains **flashing lights, jump scares, and unsettling audio**.
> If you have a heart condition, photosensitive epilepsy, or a similar condition,
> **please do not open it**.
一个粗糙模仿游戏官网的模拟恐怖（analog horror）网页。
A crude imitation of a video game's official website — an analog horror experience.
- **==注意：本网页使用了AI辅助创作，如在意请退出，本作品仅仅是因为作者的梦境与脑洞发散而创造，本人代码水平不怎么高==**
- ***==A note on how this was made: AI tools were used in the making of this page. If that's not your thing, no hard feelings — you're welcome to close the tab. This whole thing exists because of a dream and an imagination that got out of hand. Also, my coding skills are, frankly, not great.==***
### 感谢喜欢！**Thanks for playing — and for liking it!**

**更新了英文版，现在右下角可以在中文 / English之间切换，也可以随时关掉声音。**

**Added an English version: switch languages and toggle sound from the bottom-right corner.**

---

## **声明**

本项目为**虚构作品**，用于网页叙事，起源于作者的一时兴起。

其中出现的游戏、工作室、价格、玩家留言、坐标与事件**均为虚构**，与任何真实存在的游戏、公司或地点无关。

页面中的恐怖元素仅为氛围营造，不针对任何个人或群体。
## 许可

代码可自由学习、修改、二次创作。

如果搬到自己的站上，换个名字以及在此基础上略做修改会更有意思——毕竟这座灯塔只属于它自己。

如果有修改与二创麻烦大家标明原仓库和灵感来源，谢谢大家喜欢！

---

## 关于本网页
看起来是一个治愈系独立游戏《晚安灯塔》的官网：手绘的灯塔、玩家好评、原价￥88折后￥66的首发预购。

整站是**一个 HTML 文件**，没有任何依赖、没有外部请求、离线可跑。

- **用电脑打开**，请戴上耳机
- 它按照你滑动过的区块推进剧情
- 音量键在右下角，默认是开启，可以关闭，内含音效和音乐
- 如果网页卡住，试着刷新后读一遍<strong><em>《访客须知》</em></strong>寻找脱困方法：）

---

## 技术说明

- 单个 HTML，内联 CSS / JS，不加载任何外部字体、图片或库
- 画面为手写 SVG 与 CSS 渐变
- Web Audio API 实时合成（低频嗡鸣、和声垫、音乐盒、呼吸声），没有音频文件
- `speechSynthesis` 朗读 “hello” 系列台词
- `IntersectionObserver` 监听区块进入视口，按位置触发变化；颜色随滚动进度插值
- 尊重系统 `prefers-reduced-motion` 设置，会关闭抖动与部分动画

---

## 浏览器支持

推荐 **Chrome / Edge / Firefox 最新版**，桌面端体验最佳。

Safari 也能跑，但语音合成（speechSynthesis）的可用性和音色因系统而异。
手机上可以打开，但排版和闪光的观感会打折扣。推荐还是使用电脑。

经过测试手机版打开会无法切换界面...游戏体验折半了啊，因此最好还是使用电脑。

---

<details>
<summary>卡住了？点这里（含轻微剧透）</summary>

- 页面出现黑屏、只有“晚安”两个字的时候，别急着关标签页
- 等几秒，屏幕上方会浮出一行提示
- 它指向<strong><em>《***访客须知***》</em></strong>里的某一条
- 它指明的，就是你的出口？

</details>


