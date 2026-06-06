# Screen Translator

Windows screen translation desktop app.

Screen Translator lets you select a region on screen, extract visible text with Windows OCR or UI Automation, translate it through an OpenAI-compatible API, and show the result in a lightweight overlay.

## Latest Release

Version: `0.1.0`

Download:

```text
releases/v0.1.0/screen-translator-0.1.0-win-x64.zip
```

Checksum:

```text
releases/v0.1.0/screen-translator-0.1.0-win-x64.zip.sha256
```

Release notes:

```text
releases/v0.1.0/RELEASE_NOTES.md
```

## Requirements

- Windows 10 or Windows 11 x64.
- An OpenAI-compatible API endpoint, API key, and model.
- No separate .NET installation is required for the release zip.

## Run

1. Extract the zip file.
2. Run `ScreenTranslator.App.exe` from the extracted folder.
3. Configure Base URL, API Key, and model in the app.
4. Click the model-fetch button to confirm the API connection and load models.
5. Start screen-region translation from the app, tray menu, or hotkey.

## Privacy And Settings

- API keys are stored locally by the application.
- Saved API keys are protected with Windows DPAPI for the current Windows user.
- Do not share `%APPDATA%\ScreenTranslator\settings.json`.

## Source

The source code and development notes are maintained separately in the private development repository while the app is being refined.
