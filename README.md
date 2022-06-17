# 1.打包虚拟环境安装的包

> 使用pipenv创建的虚拟环境

## 1.生成方法

### 1.安装pipreqs

```python
pip install pipreqs
```

### 2.文件生成

```python
pipreqs ./ --encoding=utf8 
```



## 2.另外部署

```python
//虚拟环境
pipenv install -r requirements.txt
//主环境
pip install -r requirements.txt
```

