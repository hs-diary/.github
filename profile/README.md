### 커밋 룰
| type | description |
| :---: | :---: |
| 연, 월, 일 | 처음 일기를 올렸을 때 |
| FIX 연 월 일| 일기를 수정하고 다시 올리고 싶을 때 |

### 커밋 방법
```bash
git init '처음 초기 세팅 후에는 할 필요 없음'
git remote add origin 레포지토리 주소 '이것도 마찬가지'
git add . '커밋할때 무조건 해야하는 부분 1'
git commit -m "연, 월, 일" '2'
git push origin master '3'
```
### 파일 구성 방식
├── 2023
│   ├── 23.08.22
└──