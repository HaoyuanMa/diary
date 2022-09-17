- image
    ```html

    <center>
    <img style="border-radius: 0.3125em;
    box-shadow: 0 2px 4px 0 rgba(34,36,38,.12),0 2px 10px 0 rgba(34,36,38,.08);" 
    src="{{ site.data.images.qhbr[0] }}">
    <br>
    <div style="color:orange; border-bottom: 1px solid #d9d9d9;
    display: inline-block;
    color: #999;
    padding: 2px;">这里输入题注</div>
</center>
<br>
    
    ```

```
<div>
{{ site.data.images.pre }}
{{ site.data.images.base_url }}/
{{ page.category }}/{{ page.sub_dir }}
{{ page.slug }}
0
{{ page.image_postfix }}
{{ site.data.images.mid }}
注释
{{ site.data.images.post }}
</div>
```

