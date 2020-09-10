# pyspider


官网的pyspider是最香的

phantomjs需要配置环境变量

关闭防火墙

1、启动报错

    raise ValueError("Invalid configuration:\n  - " + "\n  - ".join(errors))
ValueError: Invalid configuration:
  - Deprecated option 'domaincontroller': use 'http_authenticator.domain_control
ler' instead.

解决方法：

将wsgidav替换为2.4.1
•# python -m pip install wsgidav==2.4.1

2
ImportError: cannot import name 'DispatcherMiddleware'

python -m pip install werkzeug==0.16.1
