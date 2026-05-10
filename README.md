cd /home/sultantalib/hms

rm -rf .git

git init

git branch -M main

git remote add origin https://github.com/smunaver/iit-hms-onproxmox.git

git add .

git commit -m "Initial HMS upload"

git push -u origin main --force
