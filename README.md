# AI Reel Generated Video

An AI-powered application that generates video reels from images and text descriptions using advanced AI models and video processing techniques.

## Features

- **AI-Powered Video Generation**: Create engaging video reels from static images
- **Text-to-Speech Integration**: Convert text descriptions to audio narration
- **Web Interface**: User-friendly web application for easy interaction
- **Image Processing**: Support for various image formats
- **Video Gallery**: Browse and manage generated video reels
- **Customizable Templates**: Multiple video templates for different styles

## Technology Stack

- **Backend**: Python Flask
- **AI Models**: Text-to-speech and video generation models
- **Frontend**: HTML, CSS, JavaScript
- **Video Processing**: FFmpeg integration
- **Audio Processing**: Text-to-speech conversion

## Project Structure

```
├── main.py                 # Main Flask application
├── generate_process.py     # Video generation logic
├── text_to_audio.py       # Text-to-speech functionality
├── config.py              # Configuration settings
├── templates/             # HTML templates
│   ├── base.html
│   ├── index.html
│   ├── create.html
│   └── gallery.html
├── static/                # Static assets
│   ├── css/              # Stylesheets
│   ├── songs/            # Audio files
│   └── reels/            # Generated videos
└── user_uploads/          # User uploaded content
```

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ai-reel-generated-video.git
   cd ai-reel-generated-video
   ```

2. Install Python dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Install FFmpeg (required for video processing):
   - Windows: Download from https://ffmpeg.org/download.html
   - macOS: `brew install ffmpeg`
   - Linux: `sudo apt install ffmpeg`

4. Run the application:
   ```bash
   python main.py
   ```

## Usage

1. Open your web browser and navigate to `http://localhost:5000`
2. Upload images and provide text descriptions
3. Select video templates and customization options
4. Generate your AI-powered video reel
5. Browse and download your creations from the gallery

## Configuration

Edit `config.py` to customize:
- AI model parameters
- Video generation settings
- Audio processing options
- File storage paths

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- AI model providers and researchers
- FFmpeg community for video processing tools
- Flask framework contributors

## Support

For support and questions, please open an issue in the GitHub repository or contact the development team.
