生成项目
安装express代码生成

    npm install -g express-generator

生成项目

    express -e 201601blog

进入目录并安装依赖

cd 201601blog && npm install
设置环境变量并启动服务器

SET DEBUG=201601blog:* & npm start
通过浏览器访问

http://localhost:3000
提交代码
初始化仓库

    git init

添加文件到暂存区

    git add -A

提交到历史区

    git commit -m"init"

添加远程仓库

    git remote add origin https://github.com/zhufengnodejs/201601blog.git

推送到远程仓库

    git push origin master
