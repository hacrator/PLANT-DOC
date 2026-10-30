# Plant Doctor with Google Gemini (no server, no login)

1. Go to https://aistudio.google.com and sign in with any Google account. Click "Get API key" > "Create API key". Copy it.
2. Lock the key to your website so others cannot use it: open https://console.cloud.google.com/apis/credentials, click your key,
   under "Application restrictions" choose "Websites", add `https://YOUR-GITHUB-USERNAME.github.io/*`, then Save.
3. On github.com open your repository, click `index.html`, click the pencil icon, replace PASTE_YOUR_GEMINI_KEY_HERE with your key (keep the quotes), click Commit changes.
4. Wait one minute and open https://YOUR-GITHUB-USERNAME.github.io/REPO-NAME/ on any phone. No login needed.

If you see an error: check the key is pasted correctly, and that the `MODEL` line in index.html is a model listed at https://aistudio.google.com (names change over time).
