# Publish ALIVE on GitHub

1. Create a new **public** GitHub repository named `alive`.
2. Extract this ZIP on your computer.
3. Open a terminal in the extracted `ALIVE` folder and run:

```bash
git init
git add .
git commit -m "Initial ALIVE public repository"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/alive.git
git push -u origin main
```

4. In GitHub, open **Settings → Pages** and set the source to **GitHub Actions**.
5. The Pages workflow will publish the website after the first push. Check the Actions tab for the deployment result.
6. Replace the placeholder links in `index.html` with your actual repository and Pump.fun token page links.
7. Before launch, publish the creator wallet in `docs/TRANSPARENCY.md`. After launch, fill in the mint address, transaction, token facts, and actual fee settings using verified evidence.

## Important
This ZIP prepares the public repository and website. It does **not** create a GitHub account/repository, deploy a Solana token, launch on Pump.fun, or verify wallet activity. Never add a seed phrase or private key to this repository.
