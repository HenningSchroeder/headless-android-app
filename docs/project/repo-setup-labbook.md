# Repository Setup Labbook (Original Bootstrap Notes)

The original `README.md` content with repository bootstrap commands is preserved here for historical traceability.

```bash
pkg upgrade
pkg install git
pkg install gh

git config --global user.name "Your Name"
git config --global user.email your.email@example.com

gh auth login

mkdir github
cd github/
mkdir HenningSchroeder
cd HenningSchroeder/

gh repo create HenningSchroeder/headless-android-app --public --description "Headless Android App" --clone

cd headless-android-app
vi README.md

git add .
git commit -m "Setup of Repo"
git push

# Alternative path for a fresh environment (instead of using --clone above):
git clone https://github.com/HenningSchroeder/headless-android-app.git
```
