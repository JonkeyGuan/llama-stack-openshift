# Example: DeepSeek Chat Completion Request

```bash
curl -X POST http://deepseek.apps.example.com/v1/chat/completions \
  -H "Content-Type: application/json" \
  -d '{
    "model": "DeepSeek-R1-Distill-Qwen-32B",
    "messages": [{"role": "user", "content": "What is AI?"}],
    "temperature": 0.1,
    "max_tokens": 512
  }'
```
