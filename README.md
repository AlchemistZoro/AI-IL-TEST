采用什么模型需要提前先定好，模型保存在saved文件夹下。
当前采用的模型文件为：9b1519a4f2.pth。

模型百度网盘[链接](https://pan.baidu.com/s/1YtpYZVkAMdjncot6F_5HEw)，提取密码：4y9g

运行：
1. 进入项目目录。
2. 在input项目目录中，添加：code_tree.json,train.json文件
3. 创建output文件目录。
4. 将训练号的模型添加至saved路径下。
5. 安装依赖```pip install -r requirements.txt``
6. 运行程序：
```
python main.py --train_batch 32 --valid_batch 64 --model_path hfl/chinese-roberta-wwm-ext --train_rate 0.8 --content_size 300 --input_dir ./input/test.json
```

