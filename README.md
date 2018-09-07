#GradleProject3

#部署不成功：
#原因之一：jar包没有放进去
#解决： file - project-structure  -  module -    web-INF 下  加入 lib  将jar放进lib中即可。

# 项目git 第一次时：
# 在gitHub 新建 repository  名称随意，这里为：gradleProject3
 git init
 git add .
 git commit -a -m "全部文件"
 git remote add origin git@github.com:lichunyuyu/gradleProject3.git
 git push -u origin master

#fatal: 'orgin' does not appear to be a git repository
# fatal: Could not read from remote repository.
git remote -v   查看远端地址
origin  git@github.com:lichunyuyu/gradleProject3.git (fetch)
origin  git@github.com:lichunyuyu/gradleProject3.git (push)

git config --list  查看配置





