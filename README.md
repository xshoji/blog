# blog

My blog by hugo.

# Post articles

```
# 0. git clone ( with submodules )
git clone https://github.com/xshoji/blog
cd blog
git submodule update --init --recursive
cd blog


# 1. Create new article
hugo new posts/20200924_article-name.md


# 2. Write article
vim vim content/posts/20200924_article-name.md


# 3. Check the article on browser by localhost
hugo server -D


# 4. Set draft flag to "false"
---
...
draft: false
...
---


# 5. Generate html
hugo


# 6. Commit and push
git add . && git commit -am "Updates" && git push
```

# References

> The world’s fastest framework for building websites ｜ Hugo  
> https://gohugo.io/

> Bare Hugo Theme ｜ Hugo Themes  
> https://themes.gohugo.io/bare-hugo-theme/
