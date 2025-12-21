# <img src="public/icon.svg" alt="NextBeats Icon" width="28" height="28" style="vertical-align: middle;"> NextBeats

A modern, customizable lofi music player built with Next.js and TypeScript. Perfect for coding, studying, or just chilling.
Try it out: [demo](https://nextbeats.vercel.app/).

<p align="center">
  <img src="demo.gif" alt="NextBeats Demo" width="800px" />
</p>

## ✨ Features

- 🎨 Beautiful retro TV-style interface
- 🎬 YouTube integration for endless lofi streams
- 🎛️ Multiple sound effects to enhance your experience
- 🌈 Theme customization
- 📻 Channel management (add, edit, delete custom channels)
- 🎚️ Independent volume controls for music and effects
- 💾 Persistent settings with localStorage
- 📱 Responsive design for all devices

## 🎵 Customization

### Adding Your Own Channels

Make NextBeats truly yours by adding your favorite lofi streams:

1. Click the '+' button in the channel list
2. Paste any YouTube lofi stream URL
3. Add a name, description, and creator
4. Save and enjoy your custom channel!

All your custom channels are saved locally and persist between sessions.

### Mixing Sound Effects

Create the perfect atmosphere by mixing different ambient sounds:

- ☕ Cafe ambience
- ⌨️ Keyboard typing
- 🔥 Fireplace crackling
- 🌧️ Rain sounds
- 🌫️ White noise
- 🌪️ Wind ambience

Add your own sound effects:

1. Click the '+' button in the sound effects panel
2. Enter a name for your effect
3. Provide any YouTube URL to add your sound file
4. Adjust the volume to your liking

Each effect has its own volume control, so you can mix them perfectly with your music. All custom effects are saved locally for your next session!

## 🚀 Getting Started

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn

### Known Limitations

- **Mobile Volume Control**: Due to security restrictions in mobile browsers (Safari, Chrome on iOS, etc.), programmatic volume control may not work. Users will need to use their device's physical volume buttons to adjust the audio level. This is a limitation imposed by mobile browsers to prevent unwanted audio experiences and cannot be circumvented via JavaScript.

### Installation

1. Clone the repository:

```bash
git clone https://github.com/btahir/next-beats.git
cd next-beats
```

2. Install dependencies:

```bash
npm install
# or
yarn install
# or
pnpm install
# or
bun install
```

3. Run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser to start vibing! 🎧

### 🐳 Using Docker

You can also run NextBeats using Docker:

```bash
# Clone the repository:
git clone https://github.com/btahir/next-beats.git
cd next-beats

# Build the Docker image
docker build -t next-beats .

# Run the container
docker run -p 3000:3000 next-beats
```

Or using docker compose:

```bash
# Clone the repository:
git clone https://github.com/btahir/next-beats.git
cd next-beats

# Run the Docker Compose file
docker compose up -d
```

Open [http://localhost:3000](http://localhost:3000) in your browser to start vibing! 🎧

### 🎮 Usage

- **Channel Navigation**: Use the channel buttons to switch between different lofi streams
- **Sound Effects**: Toggle various ambient sounds (rain, cafe, birds, etc.) to create your perfect atmosphere
- **Volume Control**: Adjust both music and effects volume independently
- **Custom Channels**: Add your own favorite lofi YouTube streams
- **Theme Customization**: Switch between different visual themes

## 🛠️ Built With

- [Next.js](https://nextjs.org/) - React framework
- [TypeScript](https://www.typescriptlang.org/) - For type safety
- [Tailwind CSS](https://tailwindcss.com/) - For styling
- [Shadcn UI](https://ui.shadcn.com/) - For UI components
- [React Player](https://github.com/cookpete/react-player) - For YouTube playback

## 🤝 Contributing

Contributions are what make the open source community amazing! Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- All the amazing lofi music creators
- The open source community
- Coffee ☕

## ⚡ From the Creators of

<p align="center">
  <a href="https://you-tldr.com">
    <img src="youtldr-banner.png" alt="You-TLDR Banner" width="600px" />
  </a>
</p>

Check out [You-TLDR](https://you-tldr.com) - AI-powered YouTube summaries that save you time!
