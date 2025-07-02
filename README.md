# 저장소 클론 (GitHub 웹에서 주소 복사)
git clone https://github.com/사용자명/my-first-repo.git

cd my-first-repo
echo "Hello GitHub!" > hello.txt

# 파일을 Git에 등록하고 커밋
git add hello.txt
git commit -m "처음 커밋"

# GitHub로 푸시
git push
