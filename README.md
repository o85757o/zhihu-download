# zhihu-download
## 将知乎专栏文章转换为 Markdown 文件保存到本地


最近想构建一个本地知识库。

需要从知乎下载文章、专栏、回答，并以 Markdown 格式保存到本地。

自己写了个脚本，

可以判断给定 url 的类型，是文章、专栏还是回答，三种类型的处理方式不同；
然后将图片保存至本地，并将转换的 Markdown 中图片 url 更换为本地路径，使图片可以在本地显示。

---

运行代码
```
python app.py
```
![image](https://github.com/chenluda/zhihu-download/assets/45784833/60e0d85b-8f48-493f-ac1f-e87e2f0738a2)
