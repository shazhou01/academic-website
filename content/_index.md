---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  # 第一个区块：显示个人简历和个人信息部分
  - block: resume-biography-3
    content:
      # 指定要显示的用户个人资料，这个值对应于 `content/authors/` 文件夹中的文件夹名
      username: admin
      # 可选字段：在简历部分显示的文本内容，目前为空
      text: ""
      # 是否在简历部分下方显示一个行动按钮（可选）
      button:
        # 按钮上显示的文字
        text: Download CV
        # 按钮链接的目标文件路径，指向简历的 PDF 文件
        url: uploads/resume.pdf
    design:
      # 设置区块的 CSS 类，应用于样式设计
      css_class: dark
      background:
        # 背景颜色设定为黑色
        color: black
        image:
          # 背景图片文件名，该文件需要存放在 `assets/media/` 文件夹中
          filename: stacked-peaks.svg
          # 图片亮度调整，1.0 表示不改变亮度
          filters:
            brightness: 1.0
          # 图片覆盖整个背景区域
          size: cover
          # 图片在背景中的位置设为居中
          position: center
          # 是否启用视差效果（滚动时背景移动的效果），这里设为 false
          parallax: false
---

