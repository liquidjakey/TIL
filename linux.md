#Linux 

##명령어 구조 
- 셋사이는 띄어쓰기로 구분합니다 

```
명령어 옵션 대상 
ls -l notes
brew install --cask iterm2 
ls - a : 숨김파일 (.으로 시작하는 파일/폴더) 까지 
ls -la
```

## 경로 
- '~': 내 홈 폴더
- '.': 지금 있는 폴더 
- '..': 한칸위 폴더 
- '/'로 시작: 절대 경로 
- 나머지: 상대 경로

- touch 

echo 'hello' > test.txt #새로 쓴다 (있으면 덮어쓰기)
echo 'world' >> test.txt #끝에 덧붙이기 

- 파일 내용 보기 
    - cat : 전부 출력
    - head -3 : 앞부분 출력 (옵션을 입력하는 경우 그줄만큼)
    - tail: 뒷부분 출력
    - less: 새로운 레이어에 출력

rm - 삭제하고 싶음 파일


