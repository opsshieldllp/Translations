# 🌍 Translation Repository

This repository contains internationalization (i18n) files for multiple languages used across our application. The translations are maintained in JSON format for easy integration.

## 📂 Structure

The repository is organized by language code:


Each file contains key-value pairs used by the application for localization.

## 🏷️ Supported Languages

| Language   | Code | Description  |
|------------|------|---------------|
| English    | `en` | Default language |
| Spanish    | `es` | Español |
| Portuguese | `pt` | Português |
| Russian    | `ru` | Русский |

## 📝 Format

Each file follows the same JSON structure. Example:

```json
{
  "welcome": "Welcome",
  "login": "Log In",
  "logout": "Log Out"
}
````


---

## 2️⃣ **CONTRIBUTING.md**

```markdown
# 🤝 Contribution Guidelines

We welcome contributions to the translation repository.

## Rules

1. **Keep keys consistent**  
   - Every language file must contain the same keys.
2. **Validate JSON syntax**  
   - Use a JSON linter or online validator before submitting.
3. **Add English as default**  
   - If you're unsure about a translation, keep the English version and flag it for review.
4. **Avoid breaking changes**  
   - Do not delete keys without prior discussion.
5. **Pull Requests**  
   - Always create a pull request with a clear description of your changes.

## Example Workflow

1. Create a new branch.
2. Make your changes to the JSON files.
3. Validate the JSON files.
4. Submit a pull request.

Thank you for your contribution!

