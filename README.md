# Notificator: Your Go-To GUI for Alertmanager Notifications 🎉🔔

![Notificator](https://img.shields.io/badge/Notificator-GUI%20for%20Alertmanager-brightgreen)

Welcome to the **Notificator** repository! Notificator is a user-friendly graphical interface designed for Alertmanager, complete with sound alerts and notifications. This tool aims to simplify your experience with Alertmanager, making it easier to manage alerts and notifications effectively.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Links](#links)

## Features

- **User-Friendly Interface**: Navigate easily with an intuitive design.
- **Sound Alerts**: Get notified with sound when an alert triggers.
- **Custom Notifications**: Tailor your notifications to suit your needs.
- **Real-Time Updates**: Stay updated with live notifications.
- **Cross-Platform Compatibility**: Works on Windows, macOS, and Linux.

## Installation

To get started with Notificator, you need to download the latest release. Visit the [Releases page](https://github.com/FerCas01/notificator/releases) to find the appropriate version for your operating system. Download the file and execute it to install Notificator on your machine.

## Usage

Once you have installed Notificator, you can launch the application. The interface will present you with various options to configure your notifications. Here’s how to get started:

1. **Open Notificator**: Launch the application from your applications folder or desktop shortcut.
2. **Configure Alertmanager**: Input your Alertmanager configuration settings.
3. **Set Notification Preferences**: Choose how you want to be alerted. You can enable or disable sound notifications and customize their volume.
4. **Monitor Alerts**: Keep an eye on your alerts in real-time. Notificator will display them as they come in.

### Example Configuration

Here’s a sample configuration to get you started:

```yaml
alertmanager:
  api_url: "http://localhost:9093/api/v1/alerts"
  notification:
    sound: "alert.mp3"
    enable: true
```

## Contributing

We welcome contributions from everyone! If you would like to help improve Notificator, follow these steps:

1. **Fork the Repository**: Click the "Fork" button at the top right of the page.
2. **Clone Your Fork**: Use `git clone <your-fork-url>` to clone your fork to your local machine.
3. **Create a New Branch**: Use `git checkout -b <branch-name>` to create a new branch for your changes.
4. **Make Your Changes**: Implement your changes or features.
5. **Commit Your Changes**: Use `git commit -m "Your message"` to commit your changes.
6. **Push to Your Fork**: Use `git push origin <branch-name>` to push your changes to your fork.
7. **Create a Pull Request**: Go to the original repository and click on "New Pull Request".

Your contributions are greatly appreciated!

## License

Notificator is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

## Links

For more information, check the [Releases page](https://github.com/FerCas01/notificator/releases) to download the latest version. 

![Download Now](https://img.shields.io/badge/Download%20Now-Click%20Here-brightblue)

Explore the features of Notificator and see how it can enhance your Alertmanager experience. 

![Alert Notification](https://example.com/alert-notification-image.png)

### Screenshots

Here are some screenshots of Notificator in action:

![Dashboard](https://example.com/dashboard-image.png)
*The main dashboard showing active alerts.*

![Settings](https://example.com/settings-image.png)
*Settings page for configuring notifications.*

### FAQ

**Q: What platforms does Notificator support?**  
A: Notificator is compatible with Windows, macOS, and Linux.

**Q: How do I report a bug?**  
A: Please open an issue in the GitHub repository and provide details about the bug.

**Q: Can I customize the sound notifications?**  
A: Yes, you can upload your own sound files in the settings.

### Community

Join our community to discuss features, report issues, or ask questions. You can find us on:

- **GitHub Issues**: [Report Issues](https://github.com/FerCas01/notificator/issues)
- **Discord**: Join our Discord server for real-time discussions.

---

Notificator aims to provide a seamless experience for managing alerts with Alertmanager. We are continuously working on improvements and new features. Your feedback is crucial to us, so don’t hesitate to reach out!