# Open Source AI Presentation

A comprehensive presentation about Open Source AI, Granite models, and InstructLab, built with [reveal.js](https://revealjs.com/).

## 📖 About

This presentation covers:

- **Open Source AI Models**: Understanding what makes an AI model truly "open source"
- **Granite Models**: IBM's suite of open-source AI models including:
  - Granite 3.2 (Language Models)
  - Granite Vision (Computer Vision)
  - Granite Guardian (Safety & Moderation) 
  - Granite Embedding (Text Embeddings)
  - Granite Time Series (Forecasting)
  - Granite Code (Code Generation)
- **InstructLab**: An opinionated workflow for fine-tuning models
- **RAG vs Fine Tuning**: Understanding the differences and use cases
- **Agentic Workflows**: Introduction to AI agent frameworks
- **Real-world Use Cases**: Practical applications and examples

## 🚀 Quick Start

### Prerequisites

- [Node.js](https://nodejs.org/) (version 18 or higher)
- npm or yarn package manager

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/jjasghar/open-source-ai-slides.git
   cd open-source-ai-slides
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Build the presentation:
   ```bash
   npm run build
   ```

4. Start the development server:
   ```bash
   npm start
   # or
   npm run dev
   ```

5. Open your browser and navigate to `http://localhost:8000`

## 📚 Usage

### Development

- **Start development server**: `npm start` or `npm run dev`
- **Build for production**: `npm run build`
- **Run tests**: `npm test`

The development server includes live reload, so any changes to the presentation will automatically refresh the browser.

### Presentation Controls

- **Navigate**: Use arrow keys, space bar, or click navigation arrows
- **Overview mode**: Press `Esc` to see all slides at once
- **Speaker notes**: Press `S` to open speaker view in a separate window
- **Full screen**: Press `F` to enter full screen mode
- **Help**: Press `?` to see all keyboard shortcuts

### Customization

#### Themes

The presentation uses the "black" theme by default. To change themes, edit the CSS link in `index.html`:

```html
<link rel="stylesheet" href="dist/theme/[THEME_NAME].css">
```

Available themes: `beige`, `black`, `blood`, `league`, `moon`, `night`, `serif`, `simple`, `sky`, `solarized`, `white`

#### Content

Edit the presentation content directly in `index.html`. The presentation is structured using reveal.js sections:

```html
<section>
    <h1>Slide Title</h1>
    <p>Slide content</p>
</section>
```

For nested slides (vertical navigation):
```html
<section>
    <section>
        <h1>Main Slide</h1>
    </section>
    <section>
        <h2>Sub Slide</h2>
    </section>
</section>
```

## 🖼️ Images

The presentation includes several images in the `images/` directory:

- **granite-*.png**: Granite branding and QR codes
- **hugging-face-models.png**: Screenshot of Hugging Face model statistics  
- **mof.jpg**: Model Openness Framework diagram
- **opensource-workshop.png**: Workshop promotional image
- **IMG_2011.jpg**: Teaching AI at STEM Night
- **jj-github-link.png**: QR code to this repository

## 🔗 Related Resources

- [Granite Models Documentation](https://www.ibm.com/granite/docs/)
- [InstructLab Project](https://instructlab.ai/)
- [Open Source AI Workshop](https://ibm.github.io/opensource-ai-workshop/)
- [Granite Workshop](https://ibm.github.io/granite-workshop/)
- [Model Openness Framework](https://www.partnershiponai.org/modelopenness/)

### Featured Frameworks

- [Bee Framework](https://i-am-bee.github.io/beeai-framework/#/) - IBM's agentic AI framework
- [CrewAI](https://www.crewai.com) - Multi-agent AI framework
- [AutoGen](https://github.com/microsoft/autogen) - Microsoft's conversational AI framework

## 🛠️ Technical Details

This presentation is built with:

- **reveal.js 5.0.3**: Modern HTML presentation framework
- **Gulp**: Build system for processing assets
- **Sass**: CSS preprocessing
- **Babel**: JavaScript compilation
- **Node.js**: Development environment

## 📝 Speaker Notes

The presentation includes speaker notes for each slide. To view them:

1. Start the presentation (`npm start`)
2. Press `S` to open the speaker view
3. The speaker view shows current slide, next slide, notes, and timer

## 🤝 Contributing

Contributions are welcome! Please feel free to:

- Submit bug reports or feature requests via [GitHub Issues](https://github.com/jjasghar/open-source-ai-slides/issues)
- Fork the repository and submit pull requests
- Suggest improvements to the presentation content
- Share your own use cases or examples

## 📄 License

This project is licensed under the Apache License 2.0 - see the [LICENSE](./LICENSE) file for details.

## 👤 Author

**JJ Asghar** - [@jjasghar](https://bsky.app/profile/jjasghar.bsky.social)
- Email: [awesome@ibm.com](mailto:awesome@ibm.com)
- GitHub: [@jjasghar](https://github.com/jjasghar)

## 🙏 Acknowledgments

- Built with [reveal.js](https://revealjs.com/) by [Hakim El Hattab](https://hakim.se)
- Granite models and InstructLab by IBM Research
- Images and content used with permission

---

*Copyright © 2025 IBM, Inc. Licensed under the Apache License, Version 2.0.*