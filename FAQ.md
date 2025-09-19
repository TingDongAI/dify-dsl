# FAQ

## 源码启动如何重置管理员密码？
如果你通过源码部署，你可以运行以下命令行重置密码。
```shell
cd api
uv run flask reset-password
```
请按照提示输入邮箱地址和新密码，例如：
```plaintext
(base) (.venv) PS D:\dify\dify-1.7.1\api> uv run flask reset-password
2025-09-19 16:28:05,550 INFO [utils.py:164]  NumExpr defaulting to 12 threads.
D:\dify\dify-1.7.1\api\controllers\web\remote_files.py:7: UserWarning: To use python-magic guess MIMETYPE, you need to run `pip install python-magic-bin`
  from controllers.common import helpers
Email: huige@test.com
New password: difyai0988
Password confirm: difyai0988
Password reset successfully.
```
