1. 安装关联包
```shell
pip install -r requirements.txt
```

2. 引入OPENAI_API_KEY
```shell
export OPENAI_API_KEY={your-api-key}
# or
os.environ["OPENAI_API_KEY"] = {your-api-key}
```

3. 进行问答 
```shell
python3 embedding.py 
python3 qa.py 
```
python version >= 3.9
按照包依赖错误执行：sudo apt-get install python3.x-dev