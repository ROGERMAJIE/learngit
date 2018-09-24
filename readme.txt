创建版本库
mkdir learngit
cd learngit
pwd
把这个目录变成Git可以管理的仓库
git init
添加文件
git add <file>
提交
git commit -m <message>
显示从最近到最远的提交日志
git log
版本回退（上一个版本就是HEAD^，上上一个版本就是HEAD^^，
当然往上100个版本写100个^比较容易数不过来，所以写成HEAD~100。）
git reset --hard HEAD^
记录每次的执行命令
git reflog
















