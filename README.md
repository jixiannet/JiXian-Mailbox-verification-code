# 安装
```bash
python -m pip install JixianVerificationCodeEmail
```
或者
```bash
pip install JixianVerificationCodeEmail
```
# 使用
```python
from JixianVerificationCodeEmail import *
smtp = Send_Verification_Code_Email(smtp_server, username, password, smtp_port)
print(smtp.send(email_to))
```
