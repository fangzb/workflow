# workflow
日常开发流水账

1.TabLayout + ViewPager中的Fragment里面又包含TabLayout + ViewPager 这种情况下用getChildFragmentManager，而不要用 getSupportFragmentManager或 getFragmentManager

2.静态方法访问非静态成员变量可以在形参列表中添加一个对象，通过对象的引用调用对应的变量。

3.svn 提示更新format, 需要访问svn版本下载地址更新svn版本。

4.路由框架的使用

5.图文混排 给接口传输之前先转换成html样式，之后通过ImageSpan来放置图片，再创建一个SpannableString对象，以便插入用ImageSpan对象封装的图像，最后用ImageSpan对象替换你指定的字符串，完成EditText的图文混排

6.七牛图片存储SDK 上传UploadManager uploadManager = new UploadManager(config)。需要关注一下config对象
