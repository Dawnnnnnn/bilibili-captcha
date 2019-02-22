# bilibili-captcha

训练好的 bilibili 图形验证码识别平台以及 tensorflow1.10.0 无 AVX 指令集的编译结果

> 基于 https://github.com/kerlomz/captcha_trainer 进行训练

> 基于 https://github.com/kerlomz/captcha_platform 进行部署

> 如果您的机器 cpu 不支持 AVX 指令集，请用此项目已编译好的 tensorflow 版本以免花费大量的时间重新编译

---

    这样运行：
      pip3 install -r requirements.txt
      python3 flask_server.py
