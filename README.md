# neura-landing
📘 NEURA Token Launch Microsite

A lightweight, fast, fully static microsite for the NEURA token launch, deployed using GitHub Pages.
This site includes the landing page, token info, roadmap, tokenomics, and community links.

🚀 Live Website

Once GitHub Pages is enabled:

https://YOUR_USERNAME.github.io/neura-landing/


Replace the URL with your actual username and repo name.

📁 Project Structure
/ (root)
 ├── index.html            # Main microsite page
 ├── logo.png              # NEURA logo (replace with your own)
 ├── Neura_Litepaper.pdf   # Litepaper available for download
 └── README.md             # Documentation

🧩 How to Update the Website
1. Edit the Landing Page

All website content lives inside index.html.

To make changes:

Open index.html in GitHub.

Click the pencil icon (edit).

Update text, links, images, or styles.

Click Commit changes.

Refresh your website — updates appear within seconds.

🖼 Updating the Logo

Replace the existing logo file with your own:

Go to the repository.

Click Add file → Upload files.

Upload your new logo (e.g. logo.png).

Update the path inside index.html if the filename changed.

Example inside index.html:

<img src="./logo.png" alt="Neura Logo" />

📄 Updating the Litepaper

Replace Neura_Litepaper.pdf with your updated version:

Upload the new PDF through Add file → Upload files.

Keep the same filename to avoid editing links.

The site links to it like this:

<a href="Neura_Litepaper.pdf">Download Litepaper</a>

🔗 Where to Add Real Token Links

Inside index.html, search for these placeholders and replace them:

YOUR_DEX_LINK
YOUR_TELEGRAM_LINK
YOUR_TWITTER_LINK
YOUR_DISCORD_LINK
CONTRACT_ADDRESS_HERE
PATH_TO_LITEPAPER_PDF


Example:

YOUR_DEX_LINK → https://raydium.io/swap/?input=SOL&output=NEURA_MINT

🌐 GitHub Pages Deployment

Deployment is automatic once GitHub Pages is enabled.

To enable:

Go to Settings → Pages

Under Source, choose:

Branch: main

Folder: /root

Save

Your site deploys automatically and updates on every commit.

🎨 Custom Domain (Optional)

You can replace the GitHub URL with your own domain (e.g., neura.xyz).

Steps:

Buy a domain

Go to Settings → Pages → Custom domain

Enter your domain

Add a DNS CNAME record pointing to:

YOUR_USERNAME.github.io

👨‍💻 Local Development (Optional)

If you want to edit or preview the site locally:

git clone https://github.com/YOUR_USERNAME/neura-landing
cd neura-landing
# open index.html in any browser


No dependencies required — it’s just one HTML file.

📝 Maintainer Notes

All styling is contained inside index.html (no external frameworks).

Keep images optimized (PNG or WebP recommended).

Use proper CDN or file paths if adding new assets.

Check links after every update.

Make sure to commit your changes so GitHub Pages auto-deploys.
