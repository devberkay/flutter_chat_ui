# [Flyer Chat](https://flyer.chat) 💬

[![Ship faster with a go-to chat SDK for Flutter](banner.png)](https://flyer.chat/docs/flutter/introduction/)

[![Pub Version](https://img.shields.io/pub/v/flutter_chat_ui?logo=flutter&color=orange)](https://pub.dev/packages/flutter_chat_ui) [![Pub Likes](https://img.shields.io/pub/likes/flutter_chat_ui?logo=flutter&color=orange&label=pub%20likes)](https://pub.dev/packages/flutter_chat_ui) [![Stars](https://img.shields.io/github/stars/flyerhq/flutter_chat_ui?style=flat&color=orange&logo=github)](https://github.com/flyerhq/flutter_chat_ui/stargazers) [![melos](https://img.shields.io/badge/maintained%20with-melos-ffffff.svg?color=orange)](https://github.com/invertase/melos)

Flyer Chat is an open-source chat UI package for Flutter applications, designed for performance, customization, and ease of integration.

## ✨ Features

- 🔄 **Backend-agnostic**: Connect to any backend service.
- 🧬 **Adaptable**: Perfect for real-time messengers, generative AI agents and LLM-based assistants, support platforms, and beyond.
- 🎨 **Highly Customizable**: Tailor the UI with extensive theme options and builder functions.
- 🧩 **Modular**: Pick and choose the features you want. You can change any part of the UI or swap it with your own custom implementation.
- ⚡ **Performance Optimized**: Built for speed and smooth animations.
- 🌐 **Cross-Platform**: Supports iOS, Android, Web, macOS, Windows, and Linux.
- 📜 **Open Source**: Free to use under the Apache 2.0 License.

## 🚀 Installation

Add the package to your `pubspec.yaml`:

```yaml
dependencies:
  flutter_chat_core: ^2.0.0
  flutter_chat_ui: ^2.0.0
```

Then, import and use the `Chat` widget.

## 📚 Documentation & Examples

For detailed usage, customization options, different message types, controllers, and more complex scenarios, please refer to the **full documentation**:

➡️ **[flyer.chat/docs/flutter/introduction](https://flyer.chat/docs/flutter/introduction)** ⬅️

Explore the comprehensive [example application](https://github.com/flyerhq/flutter_chat_ui/tree/main/examples/flyer_chat) to see various features and customizations in action.

## 📦 Packages

The project is structured as a monorepo managed by [Melos](https://melos.invertase.dev/) 💙.

### Core Packages

These are the foundational packages included when you install `flutter_chat_ui`:

- [`flutter_chat_ui`](https://github.com/flyerhq/flutter_chat_ui/tree/main/packages/flutter_chat_ui): The main UI package.
- [`flutter_chat_core`](https://github.com/flyerhq/flutter_chat_ui/tree/main/packages/flutter_chat_core): Contains core models, controllers, theming, and utilities used across the ecosystem.
- [`cross_cache`](https://github.com/flyerhq/flutter_chat_ui/tree/main/packages/cross_cache): Provides a cross-platform (IO & Web) image caching solution.

### Optional Message Widget Packages

Opinionated packages for rendering different message types. You can also build your own!

- [`flyer_chat_text_message`](https://github.com/flyerhq/flutter_chat_ui/tree/main/packages/flyer_chat_text_message): Renders text messages with markdown support.
- [`flyer_chat_text_stream_message`](https://github.com/flyerhq/flutter_chat_ui/tree/main/packages/flyer_chat_text_stream_message): Renders streamed text messages with markdown and fade-in animation support.
- [`flyer_chat_image_message`](https://github.com/flyerhq/flutter_chat_ui/tree/main/packages/flyer_chat_image_message): Renders image messages.
- [`flyer_chat_file_message`](https://github.com/flyerhq/flutter_chat_ui/tree/main/packages/flyer_chat_file_message): Renders file messages.
- [`flyer_chat_system_message`](https://github.com/flyerhq/flutter_chat_ui/tree/main/packages/flyer_chat_system_message): Renders system messages (e.g., user joined).

## 🤝 Contributing

Contributions are welcome! Please see [CONTRIBUTING.md](https://github.com/flyerhq/flutter_chat_ui/blob/main/CONTRIBUTING.md) for guidelines on how to contribute.

## 📜 License

Licensed under the Apache License, Version 2.0. See the [LICENSE](https://github.com/flyerhq/flutter_chat_ui/blob/main/LICENSE) file for details.
