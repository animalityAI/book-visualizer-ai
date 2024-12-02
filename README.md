# 📚 Book Visualizer AI

> Turn any text into beautiful, AI-generated illustrations! ✨

![GitHub](https://img.shields.io/github/license/animalityAI/book-visualizer-ai)
![Python Version](https://img.shields.io/badge/python-3.8%2B-blue)

## 🌟 Features

- 🎯 Real-time text-to-image generation
- 🌍 Multiple language support
- 📖 Perfect for books and educational content
- 🎨 Various artistic styles
- 💾 Smart caching system
- 🚀 Easy to deploy
- 💰 100% Free and self-hosted

## 🚀 Quick Start

One-line installation:
```bash
curl -o setup.sh https://raw.githubusercontent.com/animalityAI/book-visualizer-ai/main/setup.sh && chmod +x setup.sh && ./setup.sh
```

## 💻 Requirements

- Python 3.8 or higher
- 8GB+ RAM
- GPU recommended (but not required)
- CUDA support for faster generation

## 📖 How It Works

1. 📝 Input your text
2. 🤖 AI processes and understands the content
3. 🎨 Generates matching illustrations
4. 📱 View in comic-style layout

## 🎨 Available Styles

- 📚 Children's Book
- 🎭 Fantasy Art
- 🖼️ Realistic
- 📝 Sketch
- 🌅 Watercolor
- And more!

## 🛠️ Technical Stack

- 🐍 Python/FastAPI backend
- ⚛️ React frontend
- 🖼️ Stable Diffusion for image generation
- 🔄 Real-time processing
- 📦 Efficient caching system

## 📋 API Documentation

Access the interactive API docs at:
```
http://localhost:8000/docs
```

## 📝 Example Usage

```python
import requests

# Generate an illustration
response = requests.post(
    "http://localhost:8000/generate",
    json={
        "text": "A friendly dragon reading a book in a library",
        "style": "children's book"
    }
)

print(response.json())
```

## 🎯 Use Cases

- 📚 Educational Materials
- 🎨 Story Visualization
- 🌍 Language Learning
- 📖 Interactive Reading
- 🎭 Creative Writing

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- 🎨 Stable Diffusion for the base model
- 🚀 FastAPI for the backend framework
- ⚛️ React for the frontend

## 💡 Support

Need help? Create an issue or reach out to us!

## 🔮 Future Plans

- [ ] More art styles
- [ ] Batch processing
- [ ] Animation support
- [ ] Custom model training
- [ ] Mobile app

## 🌟 Show your support

Give a ⭐️ if this project helped you!