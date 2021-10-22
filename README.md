# Cognitive Cloud Open Development Documentation


To launch the docs, go to this url:<br/>
https://ibm-asset.github.io/ccode-docs/

## Install MkDocs

1. Install / Update `pip`
   - `python get-pip.py` to install or
   - `pip install --upgrade pip` to upgrade
2. Run `pip install mkdocs`
3. Run `pip install mkdocs-material`

## Generate Pages

1. Generate SSH keys and add public key to GitHub
   - `ssh-keygen  -b 4096 -f ./<key>`
2. Add SSH key to the SSH Agent (make sure it is running)
   - `eval "$(ssh-agent -s)"`
   - `ssh-add ./<key>`
3. Run `mkdocs` to generate pages under `site` <br/>
   and push to `gh-pages` branch
   - `mkdocs gh-deploy`

## Reference for Markdown

https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet



