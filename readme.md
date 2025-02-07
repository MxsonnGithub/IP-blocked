# 🚫 IP Blocked Website

This open-source project serves as a redirection page for users who have been IP-blocked from a website.  
When a user is blocked, they will be redirected here and see a message informing them of the restriction.  

## 📜 Features

- **Simple & Effective** – Displays a clear message to blocked users.
- **Minimalist Design** – Red text on a black background for high visibility.
- **Easy Deployment** – Host it on Vercel or any static hosting provider.

---

## 🔧 How to Set Up an IP Block on Vercel

To redirect blocked users to this page using Vercel, follow these steps:

1. Go to the **Firewall** tab in your Vercel project.
2. Click **Configure**.
3. In the **Configure** tab, click **New Rule**.
4. Name the rule **IP-Block Redirect**.
5. Set the conditions:
   - **If IP Address Equals** `[Blocked IP Address]`
   - **Then Redirect to** `[Your IP Block Page]`
6. Save the rule.

Now, users with the blocked IP will be redirected to this page.

---

## 🚀 Deployment

You can deploy this project easily using:

- **Vercel** – One-click deployment for free hosting.
- **Netlify** – Alternative hosting option.
- **Self-hosting** – Use any web server to serve the static page.

---

## 📂 Open-Source Contribution

This project is open source! Feel free to contribute by submitting pull requests or opening issues.

📌 **Repository:** [GitHub Link Here]  

📜 Licensed under MIT.
