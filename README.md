# MultiLoginBrowser

Public distribution repository for MultiLoginBrowser, a .NET MAUI Windows application for opening the same web application in multiple isolated browser sessions.

![Platform](https://img.shields.io/badge/platform-Windows%2010%2F11-brightgreen)
![.NET](https://img.shields.io/badge/.NET-10.0-purple)
![Type](https://img.shields.io/badge/type-MAUI%20desktop-blue)

## Downloads

Download the latest Windows build from the [Releases](../../releases) page.

- `MultiLoginBrowser-win-x64.zip` - unpackaged Windows x64 application
- `MultiLoginBrowser-win-x64.zip.sha256` - SHA256 checksum

## System requirements

| Requirement | Minimum |
|-------------|---------|
| Operating system | Windows 10 or Windows 11, x64 |
| WebView2 Runtime | Microsoft Edge WebView2 Runtime |

## Installation

1. Download `MultiLoginBrowser-win-x64.zip` from the Releases page.
2. Extract the archive to a local folder.
3. Run `MultiLoginBrowser.exe`.

## Notes

MultiLoginBrowser uses separate WebView2 profile folders for isolated sessions. Application runtime data and browser session data should stay local to each workstation and are not part of this repository.
