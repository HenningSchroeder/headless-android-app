pkg upgrade
pkg install git
pkg install g

gh auth login

mkdir github
cd github/
mkdir HenningSchroeder
cd HenningSchroeder/
gh repo create HenningSchroeder/headless-android-app --public --description "Headless Android App" --clone
git clone https://github.com/HenningSchroeder/headless-android-app.git

