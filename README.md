# Markdown_Notices

1. Necessary packages for VSCode
   - Markdown
   - Markdown All In One
   - Markdown Preview Github Styling
   - Markdown PDF

2. [Formula and common characters](https://blog.csdn.net/weixin_41738030/article/details/102856924)

4. When exporting a `.md` file to a `.pdf` file, the formula cannot be rendered.
  - Solution: Adding the following codes in the end of the markdown file.
```html
<script type="text/javascript" src="http://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML"></script>
<script type="text/x-mathjax-config">
  MathJax.Hub.Config({ tex2jax: {inlineMath: [['$', '$']]}, messageStyle: "none" });
</script>
```
