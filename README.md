```bash 
cd /d01/MyWork/1/K8s/ZENPHARMA/gitops
echo "# gitops" >> README.md
git init
git add .
git commit  -m "GITOPS Commit initiated at: $(date '+ %A, %B %d, %Y at %I:%M %p')"
git branch -M main
git remote add origin https://github.com/kkpaul2091/gitops.git
git push -u origin main
```
