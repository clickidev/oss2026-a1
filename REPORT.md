# A1 리포트

- 이름: 오세은
- 학번: 2025205129
- GitHub ID: clickidev

## 어디를 둘러봤는지

awesome-nodejs 카테고리에서 Mad science 카테고리를 둘러보다 README에 나와있는 예시 검색어를 참고하여 emoji, ascii art 등을 검색함. 흥미로워 보이는 패키지를 몇 개 선별한 뒤 각각 npm 링크를 타고 들어가 키워드를 통해 다른 패키지를 구경함.

---

## 선정한 패키지

### 1. `<cli-highlight>`

선정 이유: 책이나 교재의 중요한 글에 형광펜으로 밑줄을 치듯, 코드를 작성할 때에도 중요하다고 생각하는 코드나 다시 돌아와서 봐야하는 부분을 강조하고 싶을 때가 있습니다. 이럴 때 해당 코드에 하이라이트를 할 수 있는 기능이 있으면 좋을 것 같다고 생각했습니다.

이것으로 무엇을 할 수 있을지: 이전에는 '//!!!!'같은 식으로 다시 돌아와 검토해야할 코드 옆에 표시를 해놓았습니다. 해당 기능을 사용하면 코드를 작성하는 과정에서도 훨씬 깔끔하게 정리할 수 있을 것 같습니다.

**확인 결과:**

```
$ npm view cli-highlight version time.modified license dependencies
version = '2.1.11'
time.modified = '2023-04-12T02:46:09.922Z'
license = 'ISC'
dependencies = {
  chalk: '^4.0.0',
  'highlight.js': '^10.7.1',
  mz: '^2.4.0',
  parse5: '^5.1.1',
  'parse5-htmlparser2-tree-adapter': '^6.0.0',
  yargs: '^16.0.0'
}
$ npm view cli-highlight deprecated

```

**출력을 보고 알게 된 것:**
해당 패키지는 2023-04-12에 마지막으로 업데이트되었으며 이후 3년 가까이 방치되었다. ISC 라이선스를 사용하며, 이는 자유로운 오픈소스 라이선스로, 상업적 사용/수정/배포가 자유로운 편이다.
---

### 2. `<패키지이름>`

**선정 이유:**

**이것으로 무엇을 할 수 있을지:**

**확인 결과:**

```
$ npm view <패키지이름> version time.modified license dependencies

$ npm view <패키지이름> deprecated

```

**출력을 보고 알게 된 것:**

---

### 3. `<패키지이름>`

**선정 이유:**

**이것으로 무엇을 할 수 있을지:**

**확인 결과:**

```
$ npm view <패키지이름> version time.modified license dependencies

$ npm view <패키지이름> deprecated

```

**출력을 보고 알게 된 것:**

---

## 설치해본 패키지

```
$ npm install <패키지이름>

$ node try.js

```

---

## 막혔던 부분 (채점하지 않음)

에러 메시지든 헷갈렸던 부분이든 하나. 두 문장이면 됩니다. 없었으면 없었다고 적습니다.

```

```

---

## AI 사용

사용했다면 프롬프트와, AI의 설명이 실제와 달랐던 부분을 적습니다.
사용하지 않았다면 "사용하지 않음"이라고만 적으면 됩니다.

---

## 제출 전 확인

- [ ] 저장소 이름이 `oss2026-a1`, 공개 범위가 Public
- [ ] `git status` 결과가 `nothing to commit, working tree clean`
- [ ] `node_modules` 폴더를 지우고 `npm install` → `node try.js` 를 다시 해도 실행됨
- [ ] 마지막 커밋을 push함
