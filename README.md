# .github
git clone https://github.com/your-username/your-repo.git
cd your-repo
mkdir my-codex-repo
cd my-codex-repo
git init
echo "# 테스트 저장소" > README.md
git add README.md
git commit -m "초기 커밋"
git branch -M main
git remote add origin https://github.com/start-miracle-project/.github
git push -u origin main
