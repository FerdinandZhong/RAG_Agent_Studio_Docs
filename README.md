# RAG Agent Studios Documentation

This repository hosts the documentation site for RAG & Agent Studios, built with MkDocs Material and deployed on GitHub Pages.

## Quick Start

```bash
python -m venv .venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

### Local Development

Start the development server:
```bash
mkdocs serve
```

The site will be available at `http://127.0.0.1:8000`

### Building the Site

Generate static files:
```bash
mkdocs build
```

Output will be in the `site/` directory.

## 📖 Documentation

The documentation is organized into the following sections:

- **RAG Studio** - Complete guide for building RAG-based chatbots
  - Knowledge base creation and management
  - Document upload and indexing
  - Chat interface and query functionality
  - Advanced features (HyDE, O-RAG, Metadata Augmented RAG)
  - Monitoring and HITL capabilities


## 🚢 Deployment

The site deploys automatically via GitHub Actions when changes are pushed to the main branch.

### Manual Deployment

```bash
mkdocs gh-deploy
```

## 🎨 Customization

### Theme Configuration

The site uses Material for MkDocs with the following features:
- Light/dark mode toggle
- Navigation tabs and sections
- Search with suggestions and highlighting
- Code copy functionality

Edit `mkdocs.yml` to customize:
- Site colors (primary/accent)
- Navigation structure
- Feature flags
- Extensions

### Adding New Pages

1. Create a new `.md` file in the `docs/` directory
2. Add the page to the `nav` section in `mkdocs.yml`:

```yaml
nav:
  - Home: index.md
  - RAG Studio: RAG_studio.md
  - Your New Page: your_page.md
```

### Adding Images

1. Place images in `docs/images/`
2. Reference in markdown:
```markdown
![Alt text](images/your-image.png)
```

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Make your changes
4. Test locally with `mkdocs serve`
5. Commit your changes (`git commit -m 'Add amazing feature'`)
6. Push to the branch (`git push origin feature/amazing-feature`)
7. Open a Pull Request

### Documentation Guidelines

- Use clear, concise language
- Include code examples where appropriate
- Add screenshots/diagrams for visual features
- Follow the existing documentation structure
- Test all links and images

## 📋 Requirements

See `requirements.txt` for the full list of dependencies:
- mkdocs-material - Material theme for MkDocs
- Additional dependencies as needed

## 🔗 Links

- **Live Documentation**: https://ferdinandzhong.github.io/RAG_Agent_Studio_Docs/
- **GitHub Repository**: https://github.com/FerdinandZhong/RAG_Agent_Studio_Docs
- **MkDocs Documentation**: https://www.mkdocs.org/
- **Material for MkDocs**: https://squidfunk.github.io/mkdocs-material/

