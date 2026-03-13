# Privacy Policy

**Last updated: March 10, 2026**

AntiElectricity ("we", "our", or "the app") is a macOS text editor with AI-assisted editing features. We are committed to protecting your privacy. This policy explains what data we collect, how we use it, and your rights.

## 1. Data We Collect

**We do not collect personal information.** AntiElectricity operates primarily as a local application on your Mac. Specifically:

- **Documents and files:** All files you open and edit remain on your device. We never upload, transmit, or access your documents except when you explicitly use an AI feature on selected text.
- **AI interactions:** When you use AI features (commands, chat), the selected text is sent to the AI provider you have configured. This is the only time your content leaves your device.
- **Subscription data:** If you subscribe to the AI service (맛보기), Apple handles all payment processing through the App Store. We receive only a confirmation of your subscription status, not your payment details.
- **Usage metrics:** For subscribers, our server tracks daily token usage counts to enforce fair-use limits. This data is anonymized and associated only with a session token, not with your identity.

## 2. AI Provider Data

AntiElectricity supports multiple AI providers. Depending on your configuration:

- **맛보기 (Managed):** Selected text is sent through our proxy server to Anthropic's Claude API. We do not store or log the content of your requests or responses. Only token usage counts are recorded.
- **Ollama (Local):** All AI processing happens entirely on your device. No data leaves your computer.
- **Bring Your Own Key (BYOK):** If you use your own API keys (Anthropic, OpenAI, GitHub Copilot), text is sent directly from your device to the respective provider. Please refer to their privacy policies:
  - [Anthropic Privacy Policy](https://www.anthropic.com/privacy)
  - [OpenAI Privacy Policy](https://openai.com/privacy/)
  - [GitHub Privacy Statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement)

## 3. Data Storage

- **API keys** you enter are stored locally in your macOS user preferences (UserDefaults) and the system Keychain. They are never transmitted to our servers.
- **Session tokens** for the managed service are stored locally and used to authenticate requests to our proxy server.
- **Application preferences** (editor settings, themes, etc.) are stored locally on your device.

## 4. Data We Do NOT Collect

- Personal identification information (name, email, address)
- Device identifiers or fingerprints
- Location data
- Browsing or usage analytics
- Contents of your documents (except when you explicitly use AI features)
- Crash reports (unless you opt in through macOS system preferences)

## 5. Third-Party Services

The app integrates with the following third-party services only when explicitly configured by you:

- **Apple App Store:** Handles subscription purchases and management.
- **Anthropic API:** Powers the managed AI service (맛보기).
- **Ollama:** Local AI inference (no data leaves your device).
- **OpenAI API, GitHub Copilot:** Optional BYOK providers.

## 6. Children's Privacy

AntiElectricity is not directed at children under 13. We do not knowingly collect information from children.

## 7. Changes to This Policy

We may update this privacy policy from time to time. Changes will be posted on this page with an updated revision date.

## 8. Contact

If you have questions about this privacy policy, please contact us at:

[antielectricity@proton.me](mailto:antielectricity@proton.me)

---

© 2026 AntiElectricity. All rights reserved.
