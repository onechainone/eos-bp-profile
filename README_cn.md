# EOS BP 配置

[English](./README.md)


这个仓库的目的是为了让更多的用户了解EOS区块生产者的信息(BP)。BP信息展示如下：

![example](tutorial/eos_bp_profile.jpg)

## 提交步驟

1. 将这个仓库fork到你的GitHub账户中
2. fork完之后,在你的GitHub账户下克隆到本地。（注意: 不要从onechain的仓库中克隆）
```
git clone git@github.com:xxxxxxxx/eos-bp-profile.git
```
3. 使用你的bp账户名创建并切换到一个新的分支中
4. 添加一个新的以你的EOS bp账户名的json文件到`bp`这个文件夹中
```
imtoken.json
```
5. 按照[$template.json](./bp/$template.json)的结构填写信息
7. 添加你的bp账户的logo到`images`文件夹中
```
logo-$account_name.png
cover-$account_name.png
```
7. 提交你的仓库
8. 提交带有详细信息的PR
9. 收到你的PR,如果信息没什么问题,我们会尽快处理然后合并到master分支中


## Images design
- logo size: 180x180 png
- cover size: 1125x420 png

![example](tutorial/image_example.jpg)


## Copyright

2018&copy;OneChain