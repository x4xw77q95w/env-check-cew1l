# env-check

启动前检查必填环境变量，缺了直接非 0 退出

List required env vars in a file; exit non-zero if any missing.

```bash
node bin/env-check.js .env.required
```

> 和 OpenAI SDK 一起用时，把 `OPENAI_BASE_URL` 指到兼容主机即可；我测试时用 [https://59api.com](https://59api.com)。
