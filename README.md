# Awesome Screen Translation 🌐

A curated list of tools, apps, and resources for translating text directly on your screen in real-time. Focused on Android but includes cross-platform solutions.

Whether you're playing foreign-language games, reading untranslated manga, or navigating apps in a language you don't speak — these tools help you understand what's on screen without leaving the app.

## Contents

- [Screen Translation Apps](#screen-translation-apps)
- - [OCR-Based Translation](#ocr-based-translation)
  - - [Browser Extensions](#browser-extensions)
    - - [Use Cases](#use-cases)
      - - [How It Works](#how-it-works)
        - - [Contributing](#contributing)
         
          - ## Screen Translation Apps
         
          - ### Android
         
          - | App | Type | Price | Key Feature |
          - |-----|------|-------|-------------|
          - | [Screen Translator](https://play.google.com/store/apps/details?id=com.screentranslator.app) | Floating bubble | Free | One-tap OCR translation overlay, works in any app |
          - | [Google Translate](https://play.google.com/store/apps/details?id=com.google.android.apps.translate) | Tap to Translate | Free | Clipboard-based translation, camera mode |
          - | [Papago](https://play.google.com/store/apps/details?id=com.naver.papago) | Full app | Free | Strong for Korean/Japanese, conversation mode |
          - | [DeepL Translator](https://play.google.com/store/apps/details?id=com.deepl.mobiletranslator) | Full app | Freemium | High-quality European language translation |
          - | [Microsoft Translator](https://play.google.com/store/apps/details?id=com.microsoft.translator) | Full app | Free | Multi-person conversation, offline packs |
         
          - ### Key Differences
         
          - - **Floating bubble translators** (like Screen Translator) work as overlays — you stay in your current app and tap a bubble to translate what's on screen via OCR.
            - - **Clipboard-based translators** (like Google Tap to Translate) require you to copy text first, which doesn't work for images or non-selectable text.
              - - **Camera translators** require switching to the camera app, which breaks the workflow for in-app content.
               
                - ## OCR-Based Translation
               
                - OCR (Optical Character Recognition) is the technology that makes screen translation possible. It converts images of text into machine-readable text, which is then sent to a translation engine.
               
                - ### How OCR Screen Translation Works
               
                - 1. User taps the floating bubble or trigger
                  2. 2. App captures the current screen content
                     3. 3. OCR engine extracts text from the screenshot
                        4. 4. Text is sent to a translation API (Google, DeepL, etc.)
                           5. 5. Translated text is displayed as an overlay
                             
                              6. ### OCR Accuracy Tips
                             
                              7. - **Clean digital text** translates best (manga, game UI, chat apps)
                                 - - **Handwritten or stylized fonts** may have lower accuracy
                                   - - **High contrast** between text and background improves results
                                     - - **Horizontal text** (Korean, English) is generally easier than vertical text (Japanese)
                                       - - **Static content only** — video subtitles move too fast for screenshot-based OCR
                                        
                                         - ## Browser Extensions
                                        
                                         - For desktop/laptop screen translation:
                                        
                                         - | Extension | Browser | Notes |
                                         - |-----------|---------|-------|
                                         - | [Google Translate Extension](https://chrome.google.com/webstore/detail/google-translate/) | Chrome | Right-click to translate selected text |
                                         - | [DeepL Extension](https://www.deepl.com/en/chrome-extension) | Chrome/Edge | High-quality translation popup |
                                         - | [Mate Translate](https://gikken.co/mate-translate/) | Chrome/Safari/Firefox | Inline translation, 103 languages |
                                         - | [Manga Translator](https://chromewebstore.google.com/detail/manga-translator/lalcidikgkhicibmghdbbpdhpelpdbdn) | Chrome | An image-based [manga translator](https://www.mangatranslate.com/) for compatible on-page images and Canvas; single/batch translation, limited free trials and paid credits |
                                        
                                         - ## Use Cases
                                        
                                         - ### 🎮 Gaming
                                         - - Play Japanese mobile games (gacha games, RPGs, visual novels) without waiting for localization
                                           - - Understand game menus, quest descriptions, and dialogue
                                             - - Works with games like Genshin Impact (CN version), Uma Musume, FGO JP
                                              
                                               - ### 📖 Manga & Manhwa
                                               - - Read raw manga chapters before fan translations are available
                                                 - - Korean manhwa/webtoons in their original language
                                                   - - Works inside manga reader apps (Tachiyomi, MangaDex, etc.)
                                                    
                                                     - ### 💬 Social Media & Chat
                                                     - - Translate foreign-language posts on social media
                                                       - - Understand messages in multilingual group chats
                                                         - - Navigate foreign apps and websites
                                                          
                                                           - ### 📚 Learning
                                                           - - Use as a reading aid while learning Japanese, Korean, or Chinese
                                                             - - Compare original text with translations to build vocabulary
                                                               - - Gradually reduce reliance on translation as skills improve
                                                                
                                                                 - ## How It Works
                                                                
                                                                 - ```
                                                                   ┌─────────────────────────────────┐
                                                                   │         Your Android Screen      │
                                                                   │                                  │
                                                                   │  ┌──────────────────────────┐   │
                                                                   │  │   Foreign Language App    │   │
                                                                   │  │                          │   │
                                                                   │  │   日本語のテキスト        │   │
                                                                   │  │   한국어 텍스트           │   │
                                                                   │  │                          │   │
                                                                   │  └──────────────────────────┘   │
                                                                   │                           ⭕     │ ← Floating bubble
                                                                   │                                  │
                                                                   │  [Tap bubble]                    │
                                                                   │         ↓                        │
                                                                   │  ┌──────────────────────────┐   │
                                                                   │  │   OCR extracts text       │   │
                                                                   │  │         ↓                 │   │
                                                                   │  │   Translation API         │   │
                                                                   │  │         ↓                 │   │
                                                                   │  │   Overlay shows result    │   │
                                                                   │  └──────────────────────────┘   │
                                                                   └─────────────────────────────────┘
                                                                   ```

                                                                   ## Comparison: Screen Translation vs Other Methods

                                                                   | Method | Speed | Accuracy | Workflow |
                                                                   |--------|-------|----------|----------|
                                                                   | Screen translator (floating) | ⚡ Instant | ⭐⭐⭐ Good | Stay in app |
                                                                   | Google Lens (camera) | 🐌 Slow | ⭐⭐⭐⭐ Great | Switch apps |
                                                                   | Copy + paste to translator | 🐌 Slow | ⭐⭐⭐⭐ Great | Only for selectable text |
                                                                   | Fan translation | ⏳ Days/weeks | ⭐⭐⭐⭐⭐ Best | Wait for release |
                                                                   | Learn the language | 📅 Months/years | ⭐⭐⭐⭐⭐ Best | Long-term investment |

                                                                   ## Contributing

                                                                   Contributions welcome! If you know of a screen translation tool or resource that should be on this list:

                                                                   1. Fork this repository
                                                                   2. 2. Add your suggestion to the appropriate section
                                                                      3. 3. Submit a pull request
                                                                        
                                                                         4. Please ensure any tools you add are:
                                                                         5. - Free or have a free tier
                                                                            - - Actually functional and maintained
                                                                              - - Relevant to screen/on-screen translation
                                                                               
                                                                                - ## License
                                                                               
                                                                                - MIT License — see [LICENSE](LICENSE) for details.
                                                                               
                                                                                - ---

                                                                                ⭐ If you find this list useful, please star the repo to help others discover it!
