git remote add origin https://github.com/kimsijin33/mybucket2023.git

#remote 상태 확인
git remote -v

#저장소 복제
git clone https://github.com/kimsijin33/mybucket2023.git

git status

git --version

git branch -r

git branch -a


#변경 사항 전부  커밋
git add .

#commit message
git commit -m "first commit"

#원격 저장소 명 확인(git clone 을 통해 저장소를 복제했다면 일반적으로 원격 저장소 명은 origin)
git remote

# git push
git push origin main