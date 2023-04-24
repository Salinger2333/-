# 目的:使用github将大二作业上传至GitHub仓库中
## 参考资料: 掘金小册
## 步骤:
1. 创建仓库
2. clone至本地
3. 创建hello git文件,并使用add命令假如暂存区,commit添加注释,最后push至远程仓库
4. clone到本地另一个目录,模拟多人协作
5. 更改another目录上的hello git文件,并提交,切换到原目录进行pull操作,此时两边目录都是一样的了
6. 简单的该模式容易导致冲突,需要要到更好的模式:branch
7. HEAD、master与branch
	引用：commit的快捷方式
	HEAD：当前commit的引用
	创建、切换、删除branch
8. push的本质：把当前branch的位置（即它指向哪个commit）上传到远程仓库，并把它路径上的commits一并上传
9. push本地分支时要指定远程仓库的别名和目标branch的名字：
`git checkout feature1`
`git push origin feature1`
10. pull的内部操作其实是把远程仓库取到本地后（使用的是 fetch），再用一次 merge 来把远端仓库的新 commits合并到本地
11. merge:合并commits

	
