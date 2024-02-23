# Markdown_Notices

1. When exporting .md to .pdf file, the formula cannot be rendered.
  - Solution: Adding the following codes in the end of the markdown file.
```html
<script type="text/javascript" src="http://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML"></script>
<script type="text/x-mathjax-config">
  MathJax.Hub.Config({ tex2jax: {inlineMath: [['$', '$']]}, messageStyle: "none" });
</script>
```
2. 
