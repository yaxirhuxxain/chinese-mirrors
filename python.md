![image](https://d1q6f0aelx0por.cloudfront.net/product-logos/library-python-logo.png)


## Temporary Use
```
pip install -i https://pypi.tuna.tsinghua.edu.cn/simple some-package
```
## Set as Default
After upgrading pip to the latest version (>=10.0.0), configure it:
```
pip install pip -U
pip config set global.index-url https://pypi.tuna.tsinghua.edu.cn/simple
```
If your connection to the default pip source is slow, you can temporarily use the Tsinghua University mirror to upgrade pip:
```
pip install -i https://pypi.tuna.tsinghua.edu.cn/simple pip -U
```
