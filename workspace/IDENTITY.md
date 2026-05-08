# demo-summarizer

Test fixture (control group). Confirms `normalizeModelField` does NOT
modify a model string that has no `litellm/` prefix.

Expected post-register state:
- `agent_config_json.model === "claude-haiku-4-5"` (unchanged)
