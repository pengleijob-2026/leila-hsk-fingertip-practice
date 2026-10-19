# 蕾姐中文 · 指尖练习（课后作业）

公开站点（GitHub Pages）：

**https://pengleijob-2026.github.io/leila-hsk-fingertip-practice/**

学生用手机或电脑打开上面的链接即可，无需安装 App。

## 三个练习

| 页面 | 说明 |
|------|------|
| [指尖开花](./flower.html) | 摄像头 + 手势，指尖开花 |
| [汉字绽放](./hsk-chars.html) | 五指认字 + 拼音/英文 + 朗读 |
| [笔顺描红](./hsk-stroke.html) | 笔顺演示 + 描红（鼠标 / 食指笔） |

## 学生怎么用

1. 用 **Chrome** 或 **Safari** 打开首页链接。
2. 第一次使用摄像头时点 **允许**。
3. 笔顺页也可点「不用摄像头」，用鼠标 / 触屏练笔顺。

## 老师怎么发作业

把本课汉字写进链接参数即可，例如：

```
https://pengleijob-2026.github.io/leila-hsk-fingertip-practice/hsk-stroke.html?chars=你,好,学&title=HSK1第X课
```

- `chars`：逗号分隔的汉字（也可用中文逗号）
- `title`：可选，显示在页面提示 / 标题里

汉字绽放页同样支持：`hsk-chars.html?chars=花,爱,你,好,学&title=第1课`

## 网络说明

页面通过 CDN 加载 MediaPipe / Hanzi Writer，**需要能访问外网**。GitHub Pages 为 HTTPS，摄像头权限可用。若模型一直加载失败，请检查是否挡住 `cdn.jsdelivr.net` 或 `storage.googleapis.com`。
