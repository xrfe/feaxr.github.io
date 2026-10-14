# Privacy Policy for Esum

**Last updated:** October 14, 2026

This Privacy Policy describes how **Esum** ("the Application", "We", "Us", or "Our") handles your information when you use our mobile application. 

Esum is built with a **100% Privacy-First, On-Device Architecture**. We do not operate user account servers, track analytics, or collect your personal data.

---

## 1. Data Collection & Local On-Device Storage

Esum operates locally on your Android device. All personal data processed by Esum is stored exclusively in a local, encrypted SQLite/Room database on your device and never transmitted to servers owned or operated by Us:

- **Voice & Text Queries:** Processed locally to generate assistant responses.
- **Personal Memory & Preferences:** Stored in your device's local database.
- **Conversation History:** Retained locally until you delete it or uninstall the app.
- **Device State Data:** Battery level, Wi-Fi status, and system settings are checked locally for assistant context.
- **Encrypted Credentials:** API keys and sensitive user profile settings are encrypted using Android's hardware-backed Keystore (AES-256-GCM).

---

## 2. AccessibilityService API Declaration

Esum utilizes the Android **AccessibilityService API** strictly as an assistive tool to help users navigate and interact with applications hands-free via explicit voice or text commands (such as "Open Settings" or "Send a message").

- **User-Initiated Only:** The AccessibilityService API activates solely when you explicitly issue a command or run an automation you configured.
- **Zero Data Harvesting:** Esum does **NOT** collect, harvest, log, or transmit any personal or sensitive user data observed through the AccessibilityService API.
- **No Background Surveillance:** Esum does **NOT** read passwords, financial information, or personal messages in the background.
- **User Control:** You can disable Accessibility Service access at any time in Android Settings > Accessibility > Esum.

---

## 3. Third-Party LLM AI Providers

When you use connected AI providers (e.g., Google Gemini, OpenAI, Anthropic Claude, OpenRouter), Esum transmits your query text directly to the provider you selected to generate responses:

- **Direct Communication:** Queries travel directly from your phone to the selected AI provider's API.
- **API Key Security:** Your API keys are stored encrypted on your device and are never sent to Us.
- **Provider Policies:** Data processed by third-party LLMs is governed by the respective provider's privacy policy.
- **Offline Local AI Option:** You can choose to run 100% on-device local models (Android AI Core / LiteRT / Local PC Server) for complete offline data isolation.

---

## 4. Location Services

When you ask Esum for location-aware queries (e.g., "What's the weather today?" or "Find nearest coffee shop"), Esum uses coarse/fine location in the foreground to fetch results. Location data is processed on-demand and is never saved to external servers or tracked in the background.

---

## 5. Children's Privacy

Esum is not directed to anyone under the age of 13. We do not knowingly collect or solicit personal information from children.

---

## 6. Data Control & Deletion

Since all your data resides on your physical Android device, you have full sovereignty over your information:
- You can edit or clear any memory category from the **Memory** screen in the app.
- You can clear chat history at any time from the **Assistant** screen.
- Uninstalling Esum permanently deletes all local databases, settings, and stored data from your device.

---

## 7. Changes to This Privacy Policy

We may update this Privacy Policy periodically. Any updates will be posted on this page with an updated "Last updated" date.

---

## 8. Contact Us

If you have any questions regarding this Privacy Policy or Esum's data practices, please contact us:

- **Email:** feaxr@outlook.com
- **Website:** https://feaxr.com
