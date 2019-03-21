# pythonLearning

### python模块



#### OS模块

##### OS操作系统环境变量

```python
import os

# <class 'os._Environ'>
print(type(os.environ))
# 返回一个os的class类型，可当做dict来使用
print(os.version) 
# 根据key获取对应的环境变量值
print(os.environ["APPDATA"])
# 设置环境变量
# 修改环境变量
#
```

