<div align="center">

# 📬 WazobiaMail

### Send email from your app. Fast. Easy. It lands in the inbox.

**Your app needs to send email. We send it for you.**

[🌍 Website](https://wazobiamail.com) · [📖 Docs](https://docs.wazobiamail.com) · [🚀 Start free](https://app.wazobiamail.com)

</div>

---

## 🤔 What is WazobiaMail?

Your app sends email all the time:

- 🔑 "Here is your password reset link"
- 🧾 "Thank you for your order"
- 👋 "Welcome to our app"

Sending email yourself is **hard**. Email can go to spam. Servers break. Setup takes days.

**WazobiaMail does the hard part for you.** You write a few lines of code. We deliver the email.

## ✅ Why people use it

| | |
| --- | --- |
| ⚡ **Quick to start** | Send your first email in about 5 minutes. |
| 📥 **Gets to the inbox** | We help your email avoid the spam folder. |
| 🧩 **Works with your tools** | 14 free packages for the languages people use most. |
| 🔒 **Safe** | Your secret key stays on your server. Webhooks are signed so fakes get blocked. |
| 👀 **You can see everything** | Check if each email was sent, delivered, or bounced. |
| 🌐 **Use your own name** | Send from `hello@yourcompany.com`, not from us. |

## 🚀 How it works (3 steps)

1. **Make an account** at [wazobiamail.com](https://wazobiamail.com) and get your API key.
2. **Add our package** for your language (pick one below 👇).
3. **Send an email** with a few lines of code. Done! 🎉

```python
from wazobiamail import WazobiaMail

client = WazobiaMail(api_key="wzbm_live_...")

client.messages.send(
    to="friend@example.com",
    sender="My App <hello@myapp.com>",
    subject="Hello! 👋",
    text="Your email works.",
)
```

That is all. Every package works the same simple way.

## 🧰 Pick your tool

Click a name to open the code. Every link goes to the real project.

### 🟨 JavaScript & web apps

| Package | Use it for | Get it |
| --- | --- | --- |
| [**wazobiamail-node**](https://github.com/WazobiaMail/wazobiamail-node) | Node.js, TypeScript, Bun, Deno | `npm install wazobiamail` ⏳ |
| [**wazobiamail-react**](https://github.com/WazobiaMail/wazobiamail-react) | React apps and React Email templates | `npm install wazobiamail-react` ⏳ |
| [**wazobiamail-nextjs**](https://github.com/WazobiaMail/wazobiamail-nextjs) | Next.js (server code, forms, webhooks) | `npm install wazobiamail-nextjs` ⏳ |
| [**wazobiamail-vue**](https://github.com/WazobiaMail/wazobiamail-vue) | Vue 3 apps | `npm install wazobiamail-vue` ⏳ |
| [**wazobiamail-nuxt**](https://github.com/WazobiaMail/wazobiamail-nuxt) | Nuxt 3 and Nuxt 4 apps | `npm install wazobiamail-nuxt` ⏳ |

### 🐘 PHP & WordPress

| Package | Use it for | Get it |
| --- | --- | --- |
| [**wazobiamail-php**](https://github.com/WazobiaMail/wazobiamail-php) | Any PHP app | `composer require wazobiamail/wazobiamail-php` ✅ |
| [**wazobiamail-laravel**](https://github.com/WazobiaMail/wazobiamail-laravel) | Laravel (your old `Mail` code keeps working) | `composer require wazobiamail/wazobiamail-laravel` ✅ |
| [**wazobiamail-wordpress**](https://github.com/WazobiaMail/wazobiamail-wordpress) | WordPress sites (no code needed) | [Download the plugin](https://github.com/WazobiaMail/wazobiamail-wordpress/releases) ✅ |

### 🐍 Python, Ruby & more

| Package | Use it for | Get it |
| --- | --- | --- |
| [**wazobiamail-python**](https://github.com/WazobiaMail/wazobiamail-python) | Python, Django, Flask, FastAPI | `pip install wazobiamail` ✅ |
| [**wazobiamail-ruby**](https://github.com/WazobiaMail/wazobiamail-ruby) | Ruby and Ruby on Rails | `gem install wazobiamail` ⏳ |
| [**wazobiamail-go**](https://github.com/WazobiaMail/wazobiamail-go) | Go | `go get github.com/WazobiaMail/wazobiamail-go` ✅ |
| [**wazobiamail-rust**](https://github.com/WazobiaMail/wazobiamail-rust) | Rust | `cargo add wazobiamail` ✅ |
| [**wazobiamail-java**](https://github.com/WazobiaMail/wazobiamail-java) | Java 17+ apps | Maven / Gradle ⏳ |
| [**wazobiamail-csharp**](https://github.com/WazobiaMail/wazobiamail-csharp) | C# and .NET 8+ | `dotnet add package WazobiaMail` ⏳ |

> ✅ = ready to install now.
> ⏳ = coming to the package store very soon. You can already use the code from GitHub today.

## 🤝 Want to help? Join us!

We love help from everyone. New people are welcome. 💛

1. Pick a project above.
2. Make a copy (fork) of it.
3. Make your change on the **`dev`** branch.
4. Send us a pull request **to `dev`** (not `main`).

`main` = the safe, released code.
`dev` = where new work happens first.

Found a bug? Have an idea? Open an **Issue** in that project. Small fixes like typos help too!

## 💬 Need help?

- 📖 Read the guides: [docs.wazobiamail.com](https://docs.wazobiamail.com)
- 🐛 Something broken? Open an Issue in the project you use.
- 🌍 Learn more: [wazobiamail.com](https://wazobiamail.com)

---

<div align="center">

**Made with ❤️ by [Bonifade Technologies](https://github.com/WazobiaMail)**

All packages are free and open source (MIT License).

⭐ If WazobiaMail helps you, give us a star!

</div>
