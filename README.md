# PlayerModel
**A drop-in API/CDN replacement for ReadyPlayerMe**
ReadyPlayerMe is discontinuing support on **January 31, 2026**. PlayerModel is an open-source project to create a compatible replacement so developers can migrate with minimal code changes.

## 🎯 Project Goals

The goal is simple: create a drop-in replacement where developers can swap out ReadyPlayerMe URLs and API calls with PlayerModel equivalents, and everything just works.

**What this means:**
- Same API endpoints and response formats
- Same CDN structure for GLB model delivery  
- Compatible with existing ReadyPlayerMe integrations
- Support for Unity, Unreal, Web, and other platforms
- Open source and community-driven

**Example migration:**
```javascript
// Before
const avatarUrl = `https://models.readyplayer.me/${avatarId}.glb`;

// After  
const avatarUrl = `https://models.playermodel.dev/${avatarId}.glb`;
```

## 🤝 How You Can Help

This project needs contributors! Here's where you can jump in:

### 💻 Developers
- **Backend**: Help build the API server and avatar processing pipeline
- **3D Graphics**: Work on GLB generation, rigging, and texture systems
- **SDK Development**: Create libraries for Unity, Unreal, JavaScript
- **DevOps**: Set up infrastructure, CDN, and deployment pipelines

### 🎨 Designers & Artists
- **3D Assets**: Create base avatar models and customization assets
- **UI/UX**: Design the avatar customization interface
- **Documentation**: Create visual guides and tutorials

### 📝 Documentation
- Help write API documentation
- Create migration guides
- Build example projects
- Write tutorials

### 🧪 Testing
- Test API compatibility with existing ReadyPlayerMe integrations
- Report bugs and edge cases
- Validate models across different platforms

## 🚀 Getting Started

```bash
# Clone the repository
git clone https://github.com/yourusername/playermodel.git
cd playermodel

# More setup instructions coming soon
```

**Want to contribute?** 
- Check the [Issues](https://github.com/kar-re/playermodel/issues) for tasks labeled "good first issue"
- Join discussions in [Discussions](https://github.com/kar-re/playermodel/discussions)
- Reach out if you want to help but aren't sure where to start

## 📜 License

MIT License - See [LICENSE](LICENSE) for details.

## 🙏 Acknowledgments

Built in response to ReadyPlayerMe's shutdown. We're grateful for the work they did in making avatars accessible and aim to continue that mission.

---

**⏰ Time is ticking. Let's build this together.**
