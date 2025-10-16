# Tags

## Creating Tags
```bash
git tag <태그이름>
```

## Removing Tags
```bash
git tag -d v1
git tag -d v2
git tag -d v3

## 또는 한번에 지우기..
git tag -d v1 v2 v3
```

## Tagging later
```bash
## Adding feature 2의 커밋메시지 확인...
git log
## 확인한 뒤 태그 달아주기
git tag v1 <Adding feature 2의 커밋메시지>
```

## Remote Tags
```bash
## git log로 첫 번째 커밋의 해시를 알아내고 실행
git tag v1 <첫 번째 커밋의 태그>

## HEAD에 v2 태그 달기
git tag v2

## remote 에 태그올리기
git push friend v2
```

