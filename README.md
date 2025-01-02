```bash
# Get todos
curl http://localhost:3000/todos

# Create todo
curl -X POST http://localhost:3000/todos \
  -H "Content-Type: application/json" \
  -d '{"text": "Write docs"}'

# Toggle todo
curl -X POST http://localhost:3000/todos/1/toggle
```
