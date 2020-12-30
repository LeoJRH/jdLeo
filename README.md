使用说明：
pip install -r requirements.txt -i https://pypi.tuna.tsinghua.edu.cn/simple/

_JdTdudfp，即可从输出的Json中获取eid和fp。

sku_id已经按照茅台的填好。 cookies_string 现在已经不需要填写了 DEFAULT_USER_AGENT 可以用默认的。谷歌浏览器也可以浏览器地址栏中输入about:version 查看USER_AGENT替换

配置一下时间

jd_spider_requests.py文件中搜索self.seckill_num = 2，将2改为1


（图片）
$ sudo apt-get install qrencode zbar-tools # 安装二维码解析和生成的工具，用于读取二维码并在命令行输出。
$ zbarimg qr_code.pn
