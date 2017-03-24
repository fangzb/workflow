# workflow
日常开发流水账

1.TabLayout + ViewPager中的Fragment里面又包含TabLayout + ViewPager 这种情况下用getChildFragmentManager，而不要用 getSupportFragmentManager或 getFragmentManager

2.静态方法访问非静态成员变量可以在形参列表中添加一个对象，通过对象的引用调用对应的变量。

3.svn 提示更新format, 需要访问svn版本下载地址更新svn版本。

4.路由框架的使用

5.图文混排 给接口传输之前先转换成html样式，之后通过ImageSpan来放置图片，再创建一个SpannableString对象，以便插入用ImageSpan对象封装的图像，最后用ImageSpan对象替换你指定的字符串，完成EditText的图文混排

6.七牛图片存储SDK 上传UploadManager uploadManager = new UploadManager(config)。需要关注一下config对象

7.ClipDrawable运用

8.svn创建新分支需要在settings.gradle文件中添加 include ':分支名称' ，将新分支设定为一个工程

9.HashMap做缓存处理

10.ViewHolder技术只是将需要缓存的元素封装好，view的setTag方法才是将这些缓存起来供下次调用。VH就是个静态类，与缓存无关。

11.Fragment中onCreateView方法若外部成员变量引用，则需要判空。

12。尽量保证一个方法的行数，多去琢磨如何更精简。
13.拆解任务，更小粒度去逐步攻破。

14.修改代码要谨慎，今天同事略疏忽大意，暴增了bug率。

15.Android Studio SVN合并代码，通过右击项目Subversion --> Integrate Directory 代码合并的方向是：从Source2(分支) ---->Source1(主干) 的，点击ok就能合并，如果有冲突，相应的去解决就行。

16.svn合并点时候如果branch分支把master分支覆盖了，需要通过svn merge -r 当前版本:需要恢复的版本 全路径 之后通过svn commit -m "提交日志信息".
