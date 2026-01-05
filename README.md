# Card Value Scanner – App Support Site

Support website for Card Value Scanner, an AI-powered card scanning app that helps you digitize and analyze card information.

## ⚠️ Data Privacy Notice

**Card Value Scanner processes card images ONLY for information extraction.** This app does NOT store card data permanently, collect payment information, or perform financial transactions. All processing is for informational purposes only.

## Privacy Highlights

- **No permanent storage** – card images are processed temporarily and not retained
- **2D image only** – only the image file you upload is processed
- **Secure processing** – images are sent to our secure backend to be processed by an LLM
- **Not permanently stored** – images are not saved in databases or used for training

## Pages

- `index.html` – Main support page with FAQs
- `privacy.html` – Privacy Policy (emphasizes image handling)
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
