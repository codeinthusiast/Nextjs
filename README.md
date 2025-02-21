## 📋 Table of Contents

- [Quick Setup](#-quick-setup-5-minutes)  
- [Features](#-features)  
- [Local Development](#-local-development)  
- [Customization](#-customization)  
- [Deployment](#-deployment)  
- [Contributions](#-contributions)  
- [Important Notes](#%EF%B8%8F-important-notes)  
- [License](#-license)  
- [Credits](#-credits)  


## 💻 Local Development

1. [Fork the repository](https://github.com/codeinthusiast/Nextjs)
2. Execute the following commands:
```bash
git clone https://github.com/<your_username>/portfolio.git
cd portfolio
npm install
npm run dev
```

## 🛠 Customization

Edit [CONFIG.json](CONFIG.json) to personalize:
- Site metadata
- Profile information
- Experience timeline
- Project cards
- Social links
- Contact form settings
- & More

### Fonts
Change global font in [CONFIG.json](CONFIG.json):
- `roboto`
- `delius`
- `audiowide`

## 🌐 Deployment

### Other Platforms
- Ensure Node.js is installed
- Install all dependencies `npm install`
- Build with `npm run build`
- Start with `npm start`

## ⚠️ Important Notes

### Contact Form
**YOU MUST** implement your own contact form logic in [route.js](/src/app/api/contact/route.js). The current implementation is a placeholder.

### Personal Information
Remove or replace **(Please replace these before deployment)**:
- **Email addresses** like `maxim@nextfight.net` (Very important)
- Social media links
- Profile image
- Experience details
- Projects

### Legal Disclaimer

This template is provided as-is, and you are responsible for:

- Implementing and securing contact form logic, ensuring compliance with GDPR and other privacy laws.
- Removing the original author’s personal information and ensuring no infringement on third-party intellectual property rights.
- Validating the functionality, ensuring security against unauthorized access or breaches, and updating for any legal changes.
- Providing users with the necessary privacy and cookie notices as required by law.
- Addressing any issues that may arise, including compatibility, security, and performance concerns.

By using or modifying this template, you agree to assume full responsibility for any legal or technical issues, including ensuring compliance with relevant legal requirements such as the "Impressum" (if applicable) and privacy laws in your jurisdiction.

## 📜 License

This project is licensed under the [GNU Affero General Public License v3.0](LICENSE)

## 🤝 Contributions

Contributions are welcome!  
Here's how you can help:
feature requests.  
- **Contribute Code:**  
  1. Fork the repository.  
  2. Create a branch: `git checkout -b feature/your-feature`.  
  3. Commit using the same message style (e.g., `feat: card hover effect`).  
  4. Push changes and submit a pull request.  
- **Improve Docs:** Update the README or add missing info.  

## 🏆 Credits

### Fonts
Font licenses available in [here](src/app/fonts/licenses/)

---

**Developed with ❤️ by codeinthusiast
