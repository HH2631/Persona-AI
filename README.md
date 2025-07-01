# 🤖 PersonaAI - Your AI Digital Twin

[![iOS](https://img.shields.io/badge/iOS-15.0+-blue.svg)](https://developer.apple.com/ios/)
[![Swift](https://img.shields.io/badge/Swift-5.7+-orange.svg)](https://swift.org/)
[![SwiftUI](https://img.shields.io/badge/SwiftUI-Native-green.svg)](https://developer.apple.com/swiftui/)
[![Privacy](https://img.shields.io/badge/Privacy-First-purple.svg)](#privacy--security)

PersonaAI is an advanced AI companion that learns your personality, mimics your voice, and can make decisions on your behalf. Think of it as your digital twin that understands you better than anyone else.

## ✨ Key Features

### 🧠 **Intelligent Personality Learning**
- **Adaptive AI**: Learns from every conversation to understand your unique personality
- **Behavioral Analysis**: Captures your communication style, preferences, and decision patterns  
- **Context Awareness**: Remembers past conversations and builds meaningful context
- **Smart Insights**: Provides detailed analytics about your personality traits and preferences

### 🎤 **Voice Cloning & Synthesis**
- **Voice Training**: Record samples to train PersonaAI to speak in your voice
- **Natural Speech**: Advanced TTS with your personal voice characteristics
- **Voice Analytics**: Captures pitch, tone, cadence, and articulation patterns
- **On-Device Processing**: Voice processing happens locally for maximum privacy

### 🤝 **Autonomous Call Handling**
- **Smart Call Management**: Takes calls when you're unavailable
- **Natural Conversations**: Responds to callers using your personality and voice
- **Context-Aware Responses**: Handles different types of calls appropriately
- **Call History**: Tracks and reports on call interactions

### 🎯 **Intelligent Decision Making**
- **Preference Learning**: Analyzes your past decisions to understand your preferences
- **Context Analysis**: Considers all available information before making decisions
- **Personality-Aligned Choices**: Makes decisions that reflect your unique style
- **Decision History**: Tracks outcomes to improve future decision-making

## 🚀 Getting Started

### Prerequisites
- iOS 15.0 or later
- iPhone with microphone access
- Internet connection for AI processing
- ~200MB storage space

### Installation
1. Clone the repository or download the source code
2. Open `persona ai vm.xcodeproj` in Xcode
3. Build and run the project on your iOS device
4. Complete the onboarding process

### First Launch Setup
1. **Profile Creation**: Enter your basic information
2. **Personality Survey**: Complete the comprehensive personality assessment
3. **Voice Training** (Optional): Record voice samples for voice cloning
4. **Privacy Settings**: Configure your privacy preferences

## 📱 App Structure

### Core Tabs
- **💬 Chat**: Main conversation interface with your AI twin
- **🤖 PersonaAI**: Specialized AI features and testing tools
- **📊 Insights**: Analytics about your personality and conversation patterns
- **⚙️ Settings**: Configuration, voice training, and privacy controls

### Core Components
- **AIManager**: Handles general AI conversations and emotional analysis
- **EnhancedAIManager**: Powers the PersonaAI twin functionality
- **ProfileManager**: Manages user profiles and personality data
- **VoiceModelManager**: Processes voice training and synthesis
- **CallHandler**: Manages autonomous call handling
- **UberduckManager**: Integrates external voice synthesis services

## 🛠️ Technical Architecture

### Backend Services
```
PersonaAI Core
├── AI Processing Layer
│   ├── EnhancedAIManager (PersonaAI Twin)
│   ├── AIManager (General AI)
│   └── Natural Language Processing
├── Voice Processing Layer
│   ├── VoiceModelManager
│   ├── UberduckManager
│   └── Speech Synthesis
├── Data Management Layer
│   ├── ProfileManager
│   ├── UserProfile Storage
│   └── Conversation History
└── Communication Layer
    ├── CallHandler
    └── Contact Integration
```

### Key Technologies
- **SwiftUI**: Modern native iOS interface
- **Natural Language Framework**: Text analysis and sentiment detection
- **AVFoundation**: Audio recording and playback
- **CallKit**: Call handling and management
- **Core Data**: Persistent storage for conversations
- **UserDefaults**: Settings and preferences storage

## 🔒 Privacy & Security

PersonaAI is built with privacy-first principles:

- **🏠 Local Processing**: Voice analysis and personality data stay on your device
- **🔐 Encrypted Storage**: All sensitive data is encrypted at rest
- **🚫 No Data Sharing**: Your personality profile never leaves your device
- **👤 Full Control**: You decide what data to collect and how it's used
- **🗑️ Easy Deletion**: Remove all data at any time

## 🧪 Development Mode Features

When running in debug mode, PersonaAI includes additional testing tools:

- **Feature Testing**: Test all PersonaAI capabilities with one button
- **Debug Logs**: Detailed logging for troubleshooting
- **Mock Data**: Simulate different scenarios for testing
- **Performance Metrics**: Monitor AI response times and accuracy

## 📋 Usage Examples

### Chat with PersonaAI
```
You: "I'm feeling stressed about work"
PersonaAI: "I understand that work stress can be overwhelming. Based on our previous conversations, I know you find it helpful to break tasks into smaller steps. Would you like to talk through what's causing the stress?"
```

### Decision Making
```
Context: "Choose a restaurant for dinner"
Options: ["Italian", "Japanese", "Mexican"]
PersonaAI Decision: "Italian - based on your preference for comfort food when you've had a long day, and you mentioned loving pasta last week."
```

### Call Handling
```
Caller: "Is [Your Name] available?"
PersonaAI: "[Your Name] is in a meeting right now. I can take a message or schedule a callback. What would work better for you?"
```

## 🗺️ Roadmap

- [ ] **Multi-language Support**: Support for additional languages
- [ ] **Smart Home Integration**: Control IoT devices with your voice
- [ ] **Calendar Integration**: Automated scheduling based on preferences
- [ ] **Advanced Analytics**: Deeper personality insights and recommendations
- [ ] **Group Conversations**: Handle multi-person calls and conversations
- [ ] **Federated Learning**: Improve AI models while preserving privacy

## 🤝 Contributing

We welcome contributions! Please see our contributing guidelines and code of conduct.
(contact at (hhijazi@appifylabs.pro))




## 🆘 Support & Feedback

- **Issues**: Report bugs via GitHub Issues
- **Questions**: Check the documentation or create a discussion
- **Feature Requests**: We'd love to hear your ideas!
- **Email**: support@appifylabs.pro

## 📜 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgments

- Built with love using Swift and SwiftUI
- Inspired by the vision of truly personal AI assistants
- Thanks to the open-source community for valuable tools and libraries

---

**⚠️ Disclaimer**: PersonaAI is designed for personal use and entertainment. It should not be used for medical, legal, or other professional advice. Always verify important decisions independently. 
