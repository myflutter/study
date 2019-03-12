### flutter创建项目时，项目名称得全是小写
### flutter修改android部分启动图标在mipmap,在launch_background.xml
- 不能带有图标文件的后缀名，默认是ic_launcher
```
 <item>
        <bitmap
            android:gravity="center"
            android:src="@mipmap/ic_launcher" />
    </item>
```