git init    创建git版本库
git add     添加文件到git仓库，不加参数的话需要填写指定的文件名
git commit  把添加的文件提交一个版本  -m 填写描述字符
git status  查看git仓库的状态，有东西没有提交会有提示
git diff    查看文件哪里被修改过的
git log     查看git版本修改历史 添加参数  --pretty=oneline  可以简化输出
git reset   回到制定的版本号  --hard 固定参数  HEAD代表当前的版本 ^表示上一个版本可以叠加过个^  可以用commit id替换HEAD
git reflog  查看所有的git版本历史
git checkout --   撤销工作区的修改  -- readme.txt  两个-
阿斯利康和大叔的撒的挥洒的