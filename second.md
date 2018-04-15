# 郑曼霓第二周周记
1. git GitHub
2. markdown
3. java
4. 数据结构

---

## git GitHub
- 网上看git安装设置教材
- 在C盘创建了一个版本库，pwd可以查看当前目录
- 在根目录创建一个文本文件并对他进行编写
- 查看
- [ ] git stutus---查看文本状态
- [ ] git diff------查看修改内容
- [ ] git ls-files--查看被提交过的文件，便于后面删除文件
- 提交上传本地仓库
- [ ] git add ==文本名==----进行添加在暂存区
- [ ] git commit -m ==文本名==----进行提交
- 分支
- [ ]  git branch   -----------------查看分支
- [ ]  git branch ==分支名== ---------创建分支
- [ ]  git  checkout ==分支名==-------切换分支
- [ ]  git checkout -b ==分支名==----创建并切换分支
- [ ]  git merge ==分支名==----------合并到当前分支
- [ ]  git branch -d ==分支名==------删除分支
- [ ]  git branch -D ==分支名==-------强制删除分支
- 将本地版本库关联到远程库并推送内容
- [ ]  git push -u origin master--
- 删除
- [ ]  git rm ==文件名==-------删除某一文件
- [ ]  想要删除远程库里的文件 rm后 下命令提交并且push到远程
> 1.git rm ==文件名==
2.git commit -m ==文件名==
3.git push origin master

---
## markdown
- 简单了解什么是markdown
- 在我第二次周记创作中 明显感受到它的优点 比如排版清晰
- ![image](https://note.youdao.com/yws/public/resource/6a6f9c86b9bffcca05b0a7569a282cf5/xmlnote/8C1B66DFDBA6414188BB3FAF9B815E1C/208)
- 还有比较好的，能够实时保存和同步
- ![image](https://note.youdao.com/yws/public/resource/6a6f9c86b9bffcca05b0a7569a282cf5/xmlnote/628081BFCD764193AD03251B40110AB4/216)

---
## java
- 看了一点马老师的视频
- 感悟
- [ ] 类名要见名知意,名字大小写规范。例如方法名开头小写，类名开头大写，驼峰法等等
- [ ] 注意基本数据类型的转化，默认类型，强制转化
- [ ] 面向对象的设计思想就要求一个程序要看到的是对象，对象的一些属性，对象之间的关系
- 注意事项
1. 调用对象的非静态方法要实例化一个对象（new）
2. this关键字 指对当前对象的引用
- [ ]  ( this.i = i 是点不是空格)
- [ ] 重名这时就用this（存在方法里）
3. static关键字
- [ ] 静态变量在datasegment里
- [ ] 不用实例化对象也能访问：类名.变量名
4. 权限修饰符（private default protected public）
- [ ] 注意：int i，   默认default（包中其他类可以访问）
5. 继承（extends）
- [ ] 单继承
- [ ] 继承后拥有父类所有成员（成员变量和方法）但是能不能用就是另一回事（权限修饰）
- [ ] 子类构造必须调用父类构造方法。用super（参数）放在方法第一行，如果没有显示调用默认调用父类无参构造方法，父类没有无参构造方法出错
6. 方法重写
- [ ] 复制（名称 参数 返回类型）
- [ ] 不能有比父类更严格的访问权限

---
## 数据结构
实在惭愧，这个星期没有看
![image](https://note.youdao.com/yws/public/resource/6a6f9c86b9bffcca05b0a7569a282cf5/xmlnote/8C2A881A3E314EBAA2A50576E3D90A16/399)