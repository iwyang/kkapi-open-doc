---
icon: edit
date: 2022-02-27
category:
  - ISpeak
title: 初始化参数
---



```typescript
// 初始化函数参数定义
export interface initOptions {
  // 绑定的标签
  el?: string
  // api地址
  api: string
  // ispeak作者
  author: string
  // 每页speak显示的条数
  pageSize?: number
  // 懒加载失败时显示的图像
  fail_img?: string
  // loading的图片
  loading_img?: string
  // speak页面路径
  speakPage?: string
  githubClientId?: string
  // 第一个评论的类型
  initCommentName?: string
  // 评论选项
  initCommentOptions?: any

  // 全局对象类型的评论
  globalCommentName?: string
  // 评论选项
  globalCommentOptions?: any
}

```

