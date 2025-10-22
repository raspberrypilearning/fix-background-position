你可以固定元素的背景图像，以便其他内容在其前面滚动。

这是在 CSS 中通过向元素的选择器添加 `background-attachment: fixed` 属性来实现的。

下面是一个示例：

--- code ---
---
language: css
filename:
line_numbers: true
line_number_start: 1
line_highlights: 4
---

.garden {
  background-image: url("garden.jpeg");
  background-size: cover;
  background-attachment: fixed;
}

--- /code ---

![一张 gif 图片，显示背景图像固定，其他内容在其前面滚动。](images/background-attachment-fixed.gif)
