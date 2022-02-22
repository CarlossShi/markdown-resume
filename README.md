# markdown-resume

Markdown简历模板

# 如何使用

1. 下载[Typora](https://typora.io/) (也可使用其他), 但不保证导出效果与下文一致.
2. 修改`resume.md`中的内容:

   - 将照片放入`assets`文件夹中, 并相应修改`<img src="assets/id-photo.jpg" style="float:right" width="100" height="100"/>`中的名称及长宽, 建议设置高度大于100, 否则文字无法对齐;
   - 补充剩余内容.
3. 添加表情:

   - 在Markdown语言中添加表情. 首先在[Emoji Cheat Sheet](https://www.webfx.com/tools/emoji-cheat-sheet/)中找到想要的表情, 如mortar board:mortar_board: , 其名称为mortar_board, 随后直接键入`:mortar_board:`.

   - 在HTML语言中添加表情. 首先在[Full Emoji List](https://unicode.org/emoji/charts/full-emoji-list.html)中找到想要的表情, 如desktop computer<span style="font-size:18px">&#x1F5A5;</span>, 其代码为[U+1F5A5](https://unicode.org/emoji/charts/full-emoji-list.html#1f5a5), 随后将`1F5A5`填至相应位置, 如`<span style="font-size:18px">&#x1F5A5;</span>`; 若无法找到想要的表情, 则在[Simple Icons](https://simpleicons.org/)等网站中寻找并下载至`assets`文件夹中, 如下载`github.svg`<img src="assets/github.svg" width="18px">, 并相应修改`img src="assets/github.svg" width="18px">`中的名称即大小.
4. 导出:
   1. 进入`文件 → 偏好设置 → 导出`;
   2. 按底部加号:heavy_plus_sign:, 选择`PDF (Typora / Webkit)`后点击`添加`, 并将其命名为`PDF-CV`;
   3. 设置`页边距`为`自定义`, 设置`上下左右侧页边距`依次为`14, -10, 2, 2`;
   4. 选择`主题`为`Github, Newsprint, Whitey`中的其中一个, 推荐使用`Github`主题, 也可在[Typora Themes](https://theme.typora.io/)中下载其他主题;
   5. 依次点击`文件 → 导出 → PDF-CV`即可导出`pdf`文件.


# 效果

依次选择`Github, Newsprint, Whitey`主题, 按照上述设置导出后的简历效果如下:

| ![resume-github](resume-github.png) | ![resume-newsprint](resume-newsprint.png) | ![resume-whitey](resume-whitey.png) |
| ----------------------------------- | ----------------------------------------- | ----------------------------------- |

# Acknowledgments

- [超级简历 - WonderCV](https://www.wondercv.com/)
- [CyC2018](https://github.com/CyC2018)/**[Markdown-Resume](https://github.com/CyC2018/Markdown-Resume)**
- [Chinese Resume Template（中文简历模板）](https://www.overleaf.com/latex/templates/chinese-resume-template-zhong-wen-jian-li-mo-ban/fbdypsjmgwbb)

