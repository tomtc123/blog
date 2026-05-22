---
icon: lucide/zap
title: FastAPIcloud部署
date: 2026-05-20
categories:
  - 技术
  - Python
---

# FastAPIcloud

## 1.创建项目
```bash title="bash"
uv init myapp
uv venv
uv add "fastapi[standard]"
```

```python title="main.py"
from fastapi import FastAPI

app = FastAPI()

@app.get("/")
def main():
    return {"message": "Hello, World!"}
```
## 2.启动测试
```bash title="bash"
fastapi dev
```
## 3.部署
测试没问题就可以部署到FastAPIcloud
```bash title="bash"
fastapi login
fastapi deploy
```

```
Deploying to FastAPI Cloud...
🚀 Preparing for liftoff! Almost there...
✅ Deployment successful!
🐔 Ready the chicken! Your app is ready at https://myapp.fastapicloud.dev
```

