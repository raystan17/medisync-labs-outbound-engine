# Outbound Engine

Lightweight outbound messaging system for MediSync Labs investor outreach.

## Workspace (password protected)

Open the **workspace** to view investors, LinkedIn DMs, templates, and generated output in one place.

**Local:** Run `workspace/serve.bat` or `python -m http.server 8080`, then open http://localhost:8080/

**Deploy:** See [DEPLOY.md](DEPLOY.md) to push to GitHub and deploy on Vercel.

**Password:** pillow123 (for you and Brock)

## Generate messages

```bash
pip install -r requirements.txt
python scripts/generate_messages.py
```
