==================
sing-box-subscribe
==================

.. highlight:: bash


利用
======

填寫 ``./providers.json``

::

    uv venv
    uv pip install -r .\requirements.txt
    uv run main.py


注意, 從 Clash 配置轉換, 推薦先使用模板 3、 ``config_template_no_groups_tun_VN`` 也就是全局代理沒有規則, 因為  ``[[outbounds]]`` 中非 ``detour`` 的 ``tag`` 要與 ``outbounds`` 名稱匹配, 不確定給定的 ``clash.config.yaml`` 中有哪些 ``tag``, 再以此調整自己的模板

也可使用我的私人配置 4、 ``nanarino-config``

輸入數字迴車即可
