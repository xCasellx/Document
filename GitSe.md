#### Generate ssh-key:

*   ssh-keygen -t ed25519 -C "_your\_email@example.com_"
*   eval "$(ssh-agent -s)"
*   ssh-add ~/.ssh/id\_ed25519

#### Add public key on git:

*   [GitHub](https://docs.github.com/en/free-pro-team@latest/github/authenticating-to-github/adding-a-new-ssh-key-to-your-github-account)

#### Copy .ssh in nginx: 

*   sudo cp -r ~/.ssh /var/cache/nginx/.ssh

#### Git config :

*   git config --global user.name "Your Name"
*   git config --global user.email "you@example.com"1