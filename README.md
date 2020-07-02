## tkitJson

一个json操作库

### 安装
```

pip install tkitJson
```
or
```

pip install tkitJson  -i https://pypi.org/simple/
```

### 使用


```

pip install tkitJson  -i https://pypi.org/simple/
```

Json数据存储

```
import tkitJson
data=[{"item":111},{"item":111},{"item":111},{"item":111}]
Tjson=tkitJson.Json("data.json")
#添加数据
Tjson.save(data)

new_data=Tjson.load()
print(new_data)


```
Json配置文件

```
import tkitJson
data=[{"item":111},{"item":111},{"item":111},{"item":111}]
Tjson=tkitJson.Json("data.json")
#添加数据
Tjson.save(data)

new_data=Tjson.load()
print(new_data)


```



