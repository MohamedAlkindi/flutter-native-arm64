# Flutter ARM64 Prebuilt SDKs

This repository provides **prebuilt Flutter SDKs for ARM64 architectures**:

- **Linux ARM64** – fully tested, includes Dart, Flutter CLI, engine binaries, Web & Android artifacts.
- **Windows ARM64** – prebuilt, includes the same components as Linux; not tested on hardware.

## How to use

1. Download the desired SDK from the [Releases](link-to-releases) page.
2. Extract it to your preferred location.
3. Add `bin/` to your PATH.
4. Run `flutter doctor` to verify setup.

## Contributing & Customization

This repository is designed to be **community-friendly and flexible**.  

- Feel free to **fork this project** and edit the GitHub Actions workflow for your own needs:
  - Add or remove pre-cache steps (Web, Android, Windows, Linux, etc.)  
  - Customize packaging or artifact verification  
  - Adjust SDK versions or channels  
  - Tweak any part of the workflow to fit your environment  

- Open issues or pull requests to share improvements or fixes.
- Share feedback on ARM64 Flutter experiences — together we can make Flutter smoother on ARM64 devices.

💡 Your contributions will help create a thriving **ARM64 Flutter community**!
