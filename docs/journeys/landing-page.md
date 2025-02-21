# Landing Page Journey

This journey walks you through the experience of accessing the landing page of New App.

1. Open the application in your browser by navigating to the app's URL.
2. The landing page displays a welcome message and a brief description, both of which are dynamically translated based on the current language setting.
3. By default, the application loads in Russian. To switch to English, you can modify the language setting in the source code or use the browser console to call `i18n.changeLanguage('en')`.
4. All text is managed via the internationalization system powered by react-i18next. The translation resources are located in the `public/locales` directory:
   - English translations: `public/locales/en/translation.json`
   - Russian translations: `public/locales/ru/translation.json`
5. Any errors encountered during runtime are logged using Sentry for effective debugging.

Follow these steps to ensure the landing page provides a seamless multilingual experience.