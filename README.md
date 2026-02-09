[![Instructa AI Prompts Banner](/public/image.png)](https://www.instructa.ai/ai-prompts)

# AI Prompts & Rules

<p>
  <a href="https://github.com/instructa/ai-prompts"><img src="https://img.shields.io/github/repo-size/instructa/ai-prompts?style=flat&colorA=18181B&colorB=28CF8D" alt="Repo Size"></a>
  <a href="https://github.com/instructa/ai-prompts/actions"><img src="https://img.shields.io/github/actions/workflow/status/instructa/ai-prompts/ci.yml?branch=main&style=flat&colorA=18181B&colorB=28CF8D" alt="Build Status"></a>
  <a href="https://github.com/instructa/ai-prompts/blob/main/LICENSE"><img src="https://img.shields.io/github/license/instructa/ai-prompts.svg?style=flat&colorA=18181B&colorB=28CF8D" alt="License"></a>
  <a href="https://github.com/instructa/ai-prompts/stargazers"><img src="https://img.shields.io/github/stars/instructa/ai-prompts.svg?style=flat&colorA=18181B&colorB=28CF8D" alt="Stars"></a>
</p>

**Instructa AI Prompts** is an open-source repository dedicated to collecting and sharing AI prompts, best practices, and curated rules for developers.

## 🌍 שפות נתמכות / Supported Languages

נכון לעכשיו, התוכנה תומכת בשפות הבאות:
* 🇮🇱 **עברית**
* 🇺🇸 **אנגלית**

Currently, the software supports the following languages:
* **Hebrew**
* **English**

---

## Table of Contents

- [📖 Usage](#usage)
- [🤝 Contributing](#contributing)
- [🛟 Community & Support](#community--support)
- [🔗 Related Projects](#related-projects)
- [⚖️ License](#license)

---

## Usage

To dynamically include prompts in AI-assisted coding tools like Cursor, GitHub Copilot, Zed, Windsurf, and Cline, you can utilize their respective configuration features.

| AI Tool           | How to Include Prompts |
|-------------------|-------------------|
| **Cursor**        | Add prompts as project rules inside the `.cursor/rules/` directory. |
| **GitHub Copilot**| Create a `.github/copilot-instructions.md` file in your repository's root. |
| **Zed**           | Store prompts in the `.zed/` directory within your project. |
| **Windsurf**      | Add a .windsurfrules file into the project root. |
| **Cline**         | Add instructions in extension settings. |

## 🤝 Contributing Prompts

We welcome all contributions! 

1. Create a folder under `prompts/<prompt-name>`
2. Add metadata in `aiprompt.json`
3. Include `.mdc` files
4. Submit a Pull Request

## Community & Support

- **Discussions**: Share ideas on our [GitHub Discussions](https://github.com/instructa/ai-prompts/discussions).  
- **Issues**: Report bugs through [GitHub Issues](https://github.com/instructa/ai-prompts/issues).  

## License

[MIT License](https://github.com/instructa/ai-prompts/blob/main/LICENSE)
