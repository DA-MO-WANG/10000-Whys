Git

（以问题场景为核心及先导）

1.提交一个文本涉及的git命令流

git init  (创建.git子目录，提供一些文件来为初始化仓库做准备)——》  
		git add . (把当前目录下所有文件加到暂存区)——》  
        git  commit -m "注释" （把文件提交到本地仓库）——》   
		git  remote add origin  远程地址（关联远程库）——》  
		git   pull  --rebase origin  master(远程库与本地合并)——》  
		git   push  -u  origin master(把本地库master内容推送到远程) ——》  
		git   status (查看验证状态)