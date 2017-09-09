# 使用
```
<div id="post-id">
            <div class="ui-layout-east" data-mode="edit">
              <article class="markdown-body" id="preview" data-open-title="Hide Preview" data-closed-title="Show Preview"></article> <!-- 实时预览 -->
            </div>
        </div>
```
```
var a = "";
        var url = contextPath;
                $.get(url + "/personalBlog/post/" + blogId, function (res, status) {
                                var body = res.body;
                                            a = eval(body).content;
                                                        mdc.init(a, 0);
                                                                });
                        $("#post-id").attr("data-mode", "view");
```



# FIXME
1. 费半天劲，找到入口，使用时， 速度慢的一塌糊涂！



# Doc
1. 文件地址
> C:\Users\your-user-name\AppData\Local\youdao\ynote\markdown
