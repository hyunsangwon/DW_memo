### Rebase

    브랜치를 합치는 방법 중 하나.
    GIT에서 합치는 방법은 Merge와 Rebase가 있음.
    둘 실행결과는 같지만 커밋 히스토리가 달라짐.

### git pull 과 git pull --rebase

    차이점은 이력을 전부 관리할 것인가 or 불필요한 이력은 필요없으므로 깔끔하게 이력을 관리할 것인가의 차이.

### 명령어

```bash
git config --global pull.rebase true
```

로컬 저장소에 변경 내용이 있다면 커밋 부터 하고 pull받을 수 있게 설정
