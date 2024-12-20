services:
  - type: web
    name: my-telegram-bot
    env: python
    buildCommand: pip install -r requirements.txt  # 安装依赖
    startCommand: python main.py  # 启动命令