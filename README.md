# 

## Option B: GitHub account wide SSH key installed on every codespace you own

1. Create a repo called dotfiles (if you do not already have one). Your dotfiles repo can be private, and it will still work.
2. Follow the steps outlined above (in option A) to add your .pem file as a secret to your dotfiles repo. Keep the same naming conventions.
3. Copy install.sh into your dotfiles repo.
4. Follow the documentation here to enable your dotfiles repo. https://docs.github.com/en/codespaces/setting-your-user-preferences/personalizing-github-codespaces-for-your-account#dotfiles
5. You may need to rebuild the container for any existing Codespaces you own.
6. Note: Keys added via your dotfiles repo will be installed over top of per-repo keys with this configuration. I'm sure there's a way to change it up.

This works with GitHub Classroom. The only drawback is you need to give students admin privileges on their assignment repo.
