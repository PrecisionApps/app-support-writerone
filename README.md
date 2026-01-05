# Book Writer One – App Support Site

Support website for Book Writer One, an AI-powered writing app that helps you create and organize book content.

## ⚠️ Data Privacy Notice

**Book Writer One processes text content ONLY for writing assistance.** This app does NOT store user content permanently, collect personal information beyond what's necessary for functionality, or share data with third parties without consent. All processing is for writing enhancement purposes only.

## Privacy Highlights

- **No permanent storage** – text content is processed temporarily and not retained
- **Local processing** – content is processed on-device where possible
- **Secure backend** – when cloud processing is used, it's encrypted and temporary
- **Not permanently stored** – content is not saved in databases or used for training without consent

## Pages

- `index.html` – Main support page with FAQs
- `privacy.html` – Privacy Policy (emphasizes content handling)
- `terms.html` – Terms of Service (data privacy disclaimers throughout)
- `404.html` – Error page

## Quick Deploy (GitHub Pages)

1. Create a new repo (public)
2. Add these files
3. GitHub → Settings → Pages → Deploy from branch: `main` / `/ (root)`
4. Site goes live at `https://<username>.github.io/<repo>/`

## Local Preview

```bash
python3 -m http.server 8080
```

No build step required – static HTML + CSS for maximum speed.

## Contact

Developer: Kaan YILDIZ
Email: kaanyildiz.iosdev@gmail.com
