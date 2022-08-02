## 参考
- https://github.com/gohugoio/hugo
- https://github.com/Track3/hermit

## 编译运行打包
```bash
# 1. 下载渲染主题
git clone https://github.com/Track3/hermit.git theme/hermit

# 2. 编译预览
hugo server -D

# 3. 在public下生成静态文件
hugo -D
```

<!-- ```bash
cd content

# 获取文章源码
git clone https://github.com/garysdevil/ITNote
rm -rf ethereum/contract-code

git clone https://github.com/garysdevil/BlockchainNote

git clone https://github.com/garysdevil/ThinkingNote
cd ThinkingNote
cp -R SoulNote/Essay/thinking_released_2021/* ./
cp -R SoulNote/Essay/thinking_released_2022/* ./
``` -->

1. 将count.js里的代码追加进public/js/bundle.min*文件内

## hugo教程
### 参数讲解
```bash
# -D 表示草稿也编译
```