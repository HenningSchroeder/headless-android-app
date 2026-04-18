pkg upgrade
pkg install git
pkg install g


git config --global user.name "Henning Schroeder"
git config --global user.email henning.schroeder@gmx.de

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



git clone https://github.com/HenningSchroeder/headless-android-app.git

