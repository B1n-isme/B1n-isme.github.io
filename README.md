# Linh Nguyen-Truc - AI Engineer Portfolio

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-brightgreen)](https://b1n-isme.github.io/)
[![Hugo](https://img.shields.io/badge/Hugo-Static%20Site%20Generator-blue)](https://gohugo.io/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

Welcome to my professional portfolio showcasing my journey as an AI Engineer and Computer Science student. This portfolio highlights my expertise in **Machine Learning**, **Computer Vision**, **Natural Language Processing**, and **Full-Stack Development**.

## 🚀 Live Portfolio

Visit my live portfolio at: **[View Portfolio](https://b1n-isme.github.io/)**

## 👨‍💻 About Me

I'm a passionate Computer Science student at **Vietnamese-German University (VGU)** with hands-on experience in AI and Machine Learning. Currently working as an **AI Engineer Intern** at **TMA Solutions**, where I'm developing innovative solutions for gesture recognition and multi-modal data processing.

### Key Highlights
- 🎓 **Bachelor's Student** in Computer Science and Engineering (GPA: 8.9/10)
- 🌍 **International Experience** - Double degree program at Frankfurt University of Applied Sciences
- 💼 **AI Engineer Intern** at TMA Solutions (Feb 2025 - May 2025)
- 🏆 **Merit Scholarship** recipient (50 million VND total)
- 🌐 **Bilingual** - English (IELTS 6.5) and German

## 🛠️ Technical Skills

### Programming Languages
- **Python** (PyTorch, TensorFlow, scikit-learn, XGBoost, OpenCV)
- **SQL** (PostgreSQL, MySQL)
- **R**, **Java**, **C++**
- **JavaScript**, **HTML**, **CSS**

### AI/ML Frameworks
- **Deep Learning**: PyTorch, TensorFlow, Keras
- **Computer Vision**: OpenCV, YOLOv8, Ultralytics
- **NLP**: LangChain, HuggingFace, Sentence Transformers
- **Time Series**: Nixtla statsforecast, neuralforecast
- **Vector Databases**: Pinecone

### Tools & Technologies
- **Development**: Git, GitHub, Jupyter Notebooks, VS Code
- **Cloud**: Pinecone, cloud deployment
- **Web**: Chainlit, Flask, FastAPI
- **Data**: pandas, numpy, matplotlib, seaborn

## 📁 Portfolio Structure

```
portfolio/
├── content/
│   ├── _index.md              # Homepage
│   ├── projects/              # Project showcases
│   │   ├── bitcoin-forecasting.md
│   │   ├── yellow-flies-detection.md
│   │   └── journeybot-rag-chatbot.md
│   ├── cv/                    # Background information
│   │   ├── _index.md
│   │   ├── _education.md
│   │   └── _experience.md
│   └── skills/                # Technical skills
│       └── _index.md
├── static/
│   ├── css/
│   │   └── daynight.css       # Custom styling (deprecated)
│   └── images/                # Portfolio images
├── themes/barks/              # Hugo theme
├── hugo.toml                  # Site configuration
└── README.md
```

## 🎯 Featured Projects

### 1. Multi-Horizon Bitcoin Price Forecasting
**Machine Learning | Time Series | PyTorch Lightning**

- Built comprehensive forecasting system across 5 time horizons
- Implemented expanding-window cross-validation
- Automated model selection (statistical + neural models)
- Achieved horizon-specific performance insights

### 2. Yellow Flies Detection using YOLOv8
**Computer Vision | Object Detection | YOLO**

- Developed lightweight YOLOv8n architecture for edge deployment
- Comprehensive performance evaluation with precision, recall, mAP
- Real-time detection capabilities for images and videos
- Production-ready model deployment

### 3. JourneyBot RAG Chatbot Website
**NLP | RAG | Web Development**

- Intelligent travel assistant with personalized recommendations
- Advanced RAG pipeline with PDF processing and vector embeddings
- Modern web interface with responsive design
- Pinecone vector database integration

## 🚀 Local Development

### Prerequisites
- [Hugo](https://gohugo.io/installation/) (Extended version)
- [Git](https://git-scm.com/)

### Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/B1n-isme/portfolio.git
   cd portfolio
   ```

2. **Install Hugo (if not already installed)**
   ```bash
   # macOS
   brew install hugo
   
   # Windows (using Chocolatey)
   choco install hugo-extended
   
   # Linux
   sudo apt-get install hugo
   ```

3. **Start the development server**
   ```bash
   hugo server -D
   ```

4. **Open your browser**
   Navigate to `http://localhost:1313`

### Building for Production

```bash
# Build the site
hugo

# The built site will be in the 'public' directory
```

## 🌐 GitHub Pages Deployment

This portfolio is automatically deployed to GitHub Pages using GitHub Actions. The deployment workflow:

1. **Automatic Build**: Triggers on every push to the main branch
2. **Hugo Build**: Generates static site using Hugo
3. **Deploy**: Publishes to GitHub Pages

### Manual Deployment

If you need to deploy manually:

1. **Build the site**
   ```bash
   hugo
   ```

2. **Push to GitHub**
   ```bash
   git add .
   git commit -m "Update portfolio"
   git push origin main
   ```

3. **Enable GitHub Pages**
   - Go to repository Settings
   - Navigate to Pages section
   - Select source as "GitHub Actions"

## 🎨 Customization

### Theme
This portfolio uses the [Barks Hugo theme](https://github.com/EmielH/tale-hugo). You can customize:

- **Colors**: Use theme SCSS variables in `themes/barks/assets/styles.scss` (daynight.css no longer used)
- **Layout**: Modify files in `themes/barks/layouts/`
   - For tags/categories pages, edit minimal templates in `themes/barks/layouts/_default/{taxonomy,terms}.html`
- **Content**: Update markdown files in `content/`

### Adding New Projects

1. Create a new markdown file in `content/projects/`
2. Use the following frontmatter template:
   ```yaml
   ---
   title: "Project Name"
   date: 2024-12-01T10:00:00+07:00
   draft: false
   tags: ["Tag1", "Tag2", "Tag3"]
   tech_stack: ["Tech1", "Tech2", "Tech3"]
   github_link: "https://github.com/username/repo"
   demo_link: "https://demo-link.com"
   ---
   ```

## 📞 Contact

- **Email**: [10421088@student.vgu.edu.vn](mailto:10421088@student.vgu.edu.vn)
- **LinkedIn**: [linkedin.com/in/linh-nguyen-truc-166a66186](https://linkedin.com/in/linh-nguyen-truc-166a66186)
- **GitHub**: [github.com/B1n-isme](https://github.com/B1n-isme)
- **Phone**: +84 867 102 612

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [Hugo](https://gohugo.io/) - Static site generator
- [Barks Theme](https://github.com/EmielH/tale-hugo) - Hugo theme
- [GitHub Pages](https://pages.github.com/) - Hosting platform

---

**Thank you for visiting my portfolio!** Feel free to reach out if you'd like to collaborate or have any questions about my work.
