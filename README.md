# Flutter Native ARM64

This repository provides **prebuilt, fully native Flutter SDKs for ARM64 architectures**, for Linux.

- **Linux ARM64** – fully tested, includes Dart, Flutter CLI, engine binaries, Web & Android artifacts.
  
## Always Up-to-Date

These SDKs are **continuously updated with the latest stable Flutter releases**. Every workflow run ensures you get the newest version without building from source.

## How to use

1. Download the desired SDK version from the [Releases](https://github.com/MohamedAlkindi/flutter-native-arm64/releases) page.
2. Extract it to your preferred location.
3. Add `bin/` to your PATH.
4. Run `flutter doctor` to verify setup (this step might take some time before it shows the result, so please be patient).

## Screenshot
<img width="2560" height="1600" alt="Screenshot_20250904_222026_Termux" src="https://github.com/user-attachments/assets/8fb39080-7f28-48fe-9c5f-93dc70c3e2ee" />


## Contributing & Customization

This repository is designed to be **community-friendly and flexible**.  

- Feel free to **fork this project** and edit the GitHub Actions workflow for your own needs:
  - Add or remove pre-cache steps (Web, Android, Linux, etc.)  
  - Customize packaging or artifact verification  
  - Adjust SDK versions or channels  
  - Tweak any part of the workflow to fit your environment  

- Open issues or pull requests to share improvements or fixes.
- Share feedback on ARM64 Flutter experiences — together we can make Flutter smoother on ARM64 devices.

💡 Your contributions will help create a thriving **ARM64 Flutter community**!
