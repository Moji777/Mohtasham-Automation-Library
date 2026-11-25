# Capability matrix

| Reference | Capability | Existing implementation | Action |
|---|---|---|---|
| n8n | Orchestration | Not audited | Keep existing deployment; use Switch and Execute Sub-workflow for routing. |
| Ollama | Local inference | Not audited | Reuse one model endpoint; benchmark Persian responses. |
| AutoGPT | Planning | Not audited | Evaluate bounded planning and retries; no autonomous external writes. |
| Stable-Diffusion | Interior image drafts | Not audited | Optional worker; check VRAM and model licenses. |
| Dify | Knowledge and support | Not audited | Compare retrieval and evaluation with existing n8n before deploying. |
| Open-WebUI | Assistant interface | Not audited | Optional authenticated UI; avoid duplicate dashboards. |
| Langflow | Visual AI graphs | Not audited | Compare routing with n8n; avoid duplicate runtimes. |
| LangChain | Agent logic | Not audited | Use only needed libraries; check existing n8n AI nodes first. |
| ComfyUI | Visual content pipeline | Not audited | Run on demand; prefer small models and draft outputs. |
| Browser-Use | Public market research | Not audited | Use isolated browser; no credentials, bypasses or unapproved submissions. |
