# Screen Translator 0.1.0

Date: 2026-06-06
Package: `screen-translator-0.1.0-win-x64.zip`
SHA256: `d9fae68eb946add23f409a9bcedd2aa9641af210519ef6aa3eed61dc60a27c00`

## What Is Included

Screen Translator 0.1.0 is the first public Windows x64 portable release.

It includes:

- Region-based screen translation.
- Windows OCR and UI Automation text extraction.
- OpenAI-compatible API configuration.
- Model list fetching from compatible providers.
- Floating translation overlay and result panel fallback.
- Continuous translation for a selected region.
- Tray icon controls and configurable global hotkeys.
- Local settings storage with Windows DPAPI protection for API keys.

## Download

Download and extract:

```text
releases/v0.1.0/screen-translator-0.1.0-win-x64.zip
```

Verify the download with:

```text
releases/v0.1.0/screen-translator-0.1.0-win-x64.zip.sha256
```

## Requirements

- Windows 10 or Windows 11 x64.
- No separate .NET installation is required; the package is self-contained.
- An OpenAI-compatible API endpoint, API key, and model.

## How To Run

1. Extract the zip file.
2. Run `ScreenTranslator.App.exe`.
3. Configure Base URL, API Key, and model in the app.
4. Click the model-fetch button to confirm the API connection and load models.
5. Start screen-region translation from the app, tray menu, or hotkey.

## Notes

- API keys are stored locally and protected for the current Windows user.
- Do not move only the `.exe`; keep the extracted folder contents together.
- This release is a portable zip package, not an installer.
