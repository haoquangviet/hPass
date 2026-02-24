# hPass - Enterprise Password Manager

**hPass** is a secure, enterprise-grade password manager for Android, built as part of the [hOne/hCRM](https://hqv.biz) ecosystem.

## Features

- **AES-256 Encryption** - Military-grade encryption. Data encrypted locally before sync.
- **Biometric Unlock** - Fingerprint/Face unlock with hardware-backed Keystore.
- **Android Autofill** - One-tap login in any app or browser with inline suggestions.
- **TOTP Authenticator** - Built-in 2FA code generator.
- **Enterprise Sync** - End-to-end encrypted sync with hCRM server.
- **Tablet Optimized** - Adaptive master-detail layout for phones, foldables, and tablets.
- **Dark/Light Theme** - System-aware theme support.
- **Password Generator** - Customizable strong password generation.

## Download

Download the latest APK from the [Releases](releases/) folder or visit the [Landing Page](https://haoquangviet.github.io/hPass/).

| Version | Date | Download |
|---------|------|----------|
| v1.0.34 | Feb 2026 | [hpass-v1.0.34.apk](releases/hpass-v1.0.34.apk) |

### Installation

1. Download the APK file
2. Enable "Install from unknown sources" in Android Settings > Security
3. Open the APK file to install
4. Requires Android 8.0 (Oreo) or higher

## Feedback & Issues

We welcome your feedback! Please use the issue templates to:

- [Report a Bug](https://github.com/haoquangviet/hPass/issues/new?template=bug_report.md&labels=bug)
- [Request a Feature](https://github.com/haoquangviet/hPass/issues/new?template=feature_request.md&labels=enhancement)
- [Share UI/UX Feedback](https://github.com/haoquangviet/hPass/issues/new?template=ui_feedback.md&labels=ui)

## Security

hPass uses:
- AES-256-GCM for vault encryption
- PBKDF2 for PIN-based key derivation
- Android Keystore for biometric key storage
- EncryptedSharedPreferences for sensitive data
- Zero-knowledge architecture (server never sees plaintext)

## License

Proprietary software by Hao Quang Viet. All rights reserved.
