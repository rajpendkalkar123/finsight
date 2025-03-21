# FinSight - AI-Powered Financial Analysis Tool

FinSight is a modern Flutter application that leverages AI to provide intelligent financial analysis and insights. The app uses Google's Gemini API for generating financial reports and critiques, offering users a powerful tool for financial decision-making.

## Features

- 🤖 AI-powered financial analysis
- 📊 Interactive financial charts
- 📱 Modern, responsive UI
- 🌓 Light/Dark mode support
- 🔒 Secure API key management
- 📝 Customizable report generation
- 💾 Report saving functionality

## Prerequisites

- Flutter SDK (latest version)
- Dart SDK (latest version)
- Google Gemini API key
- Firebase project (for data persistence)



## Project Structure

```
lib/
├── main.dart              # App entry point
├── screens/              # UI screens
│   ├── home_screen.dart
│   └── saved_reports_screen.dart
├── services/             # Business logic
│   └── openai_service.dart
├── models/              # Data models
│   └── financial_report.dart
└── widgets/             # Reusable widgets
    ├── loading_indicator.dart
    └── report_display.dart
```

## Dependencies

- `flutter`: UI framework
- `firebase_core`: Firebase integration
- `google_fonts`: Custom typography
- `http`: API communication
- `fl_chart`: Chart visualization

## Environment Variables

The following environment variables are required:

- `GEMINI_API_KEY`: Your Google Gemini API key

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Google Gemini API for AI capabilities
- Flutter team for the amazing framework
- Firebase for backend services
- All contributors who have helped shape this project


