# ollama Gitpod demo

`ollama` should be up and running while you read this.

Open a Python REPL (`python` in the console, then _Enter_) and try the following code:

```python
import json
import requests

body = {
    "model": "llama3.2",
    "prompt": "Do all Dikarya exhibit 'clamp connections' in their hyphal development?",
    "stream": False,
}

response = requests.post("http://localhost:11434/api/generate", json=body)
resp_json = response.json()

resp_short = {k: f"{str(v)[:30]} ..." for k, v in resp_json.items()}
print("Response (shortened):")
print(json.dumps(resp_short, indent=2))

print("\nAnswer:")
print(resp_json["response"])
```

You may also want to inspect the following files:

- `.gitpod_logs/setup_before.log`, `.gitpod_logs/setup_init.log`; and, most importantly,
- `.gitpod_logs/ollama_stdout.log` and `.gitpod_logs/ollama_stderr.log`.

This is all.
