# Yihan Zhou - Career Portfolio

This repository contains the source code for my personal career portfolio website, hosted at [yiihann.github.io](https://yiihann.github.io).

## About

I’m a Machine Learning Engineer on TikTok’s E-commerce LIVE team, where I build LLM-powered recommendation systems. My work on LLMs for recommendation (LLM4Rec) includes continued pretraining (CPT), supervised fine-tuning (SFT), and chain-of-thought (CoT) approaches.

This website showcases my projects, work experience, and professional accomplishments.

## Website

🌐 **Live Site**: [https://yiihann.github.io](https://yiihann.github.io)

## Local Development

To run this site locally:

1. **Install Hugo** (Extended version):
   ```bash
   # macOS
   brew install hugo
   
   # Or download from https://gohugo.io/installation/
   ```

2. **Clone the repository**:
   ```bash
   git clone https://github.com/yiihann/yiihann.github.io.git
   cd yiihann.github.io
   ```

3. **Install dependencies**:
   ```bash
   # Install Node.js dependencies (for Tailwind CSS and Pagefind)
   pnpm install
   
   # Download Hugo modules
   hugo mod download
   ```

4. **Run the development server**:
   ```bash
   hugo server
   ```

5. **View the site**: Open [http://localhost:1313](http://localhost:1313) in your browser

## Project Structure

- `content/` - Website content (projects, blog posts, experience, etc.)
- `data/authors/` - Author profile information
- `config/` - Hugo configuration files
- `static/` - Static assets (images, PDFs, etc.)
- `assets/` - Processed assets (media files)
- `layouts/` - Custom layout templates

## Building

To build the site for production:

```bash
hugo --minify && pnpm run pagefind
```

The generated site will be in the `public/` directory.

## Deployment

This site is automatically deployed to GitHub Pages via GitHub Actions. Simply push changes to the `main` branch and the site will rebuild automatically.

## Credits

This website is built using [HugoBlox](https://hugoblox.com/) and the Academic CV template, customized for a professional career portfolio.

## License

Content on this website is © Yihan Zhou. All rights reserved.

---

**Contact**: [yihan.zhou427@gmail.com](mailto:yihan.zhou427@gmail.com) | [Website](https://yiihann.github.io) | [GitHub](https://github.com/yiihann) | [LinkedIn](https://www.linkedin.com/in/yihan-zhou-zoe020427/)
