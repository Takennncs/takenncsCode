# takenncsStudio

A Windows code editor with an integrated terminal, SSH support and live web/FiveM NUI preview.

## Download

**[Download takenncsStudio for Windows](https://github.com/Takennncs/takenncsCode/releases/latest/download/takenncsStudio-Setup.exe)**

1. Download `takenncsStudio-Setup.exe`.
2. Run the installer.
3. Open Studio and select your project folder.

Visual Studio and a separate .NET installation are not required.
If Microsoft Edge WebView2 is missing, setup downloads and installs it.

## Features

- Monaco editor with syntax highlighting and file search
- HTML, CSS, JavaScript, TypeScript/TSX, Lua, C#, C++, Python and other text files
- Integrated PowerShell terminal and SSH connections
- Project tasks and local theme/snippet extensions
- Seven themes and configurable editor settings
- Optional Discord Rich Presence
- Live HTML and FiveM NUI preview
- Visual NUI designer with Lua callback generation
- Comment and console-log cleanup with a change preview

## Getting started

- **File → Open folder:** open a project
- **View → Terminal:** open PowerShell
- **Tools → SSH connection:** connect to a server
- **View → Settings:** configure the editor and Discord presence
- **Ctrl+S:** save changes
- **Ctrl+F:** search the current file
- **Ctrl+W:** close the current tab

TSX/JSX projects need their own development server.
Start it in Terminal or Tasks and enter its localhost URL in the preview.

SSH requires Windows OpenSSH Client. Compilers and project dependencies
must be installed separately when needed.

## Privacy

Studio does not require an account or upload your project automatically.
Settings and recent-project history are stored locally.

Discord presence is optional. Folder names, file names and cursor lines
can be shared when enabled. Full paths and source contents are not sent
by the presence service.

Project previews, terminal commands and optional integrations may access
the network.

## Limitations

NUI preview simulates the browser interface, not a running FiveM server.
“Protect UI” minifies JavaScript/CSS; it does not prevent dumping.
VS Code extensions are not supported.

The application is unsigned, so Windows may display a publisher or
reputation warning.

## Bug reports

Please [open an issue](https://github.com/Takennncs/takenncsCode/issues)
with reproduction steps, your Windows version and relevant screenshots.

Remove passwords, tokens, private code and personal paths before posting.

## License

Released under the [MIT License](LICENSE), including its warranty disclaimer
and limitation of liability.

Third-party components retain their own licenses.
See [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md).
