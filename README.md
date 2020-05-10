# hupu_blog

### 更改了几处地方就可以了

#### pom.xml增加下面的代码


```
<dependency>
    <groupId>net.sf.json-lib</groupId>
    <artifactId>json-lib</artifactId>
    <version>2.4</version>
    <classifier>jdk15</classifier>
</dependency>
```

#### 修改com.blog.service.impl.InitComponent
```
//加一个this
this.applicationContext = applicationContext;
```

#### 修改数据库

```
//修改密码
<property name="password" value="123456"/>
```
#### 后台默认密码改了下

不知道默认密码所以我自己改了一下

后台登陆：

```
admin/123456
```

