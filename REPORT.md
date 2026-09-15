# A1 리포트

- 이름: 오세은
- 학번: 2025205129
- GitHub ID: clickidev

## 어디를 둘러봤는지

awesome-nodejs 카테고리에서 Mad science 카테고리를 둘러보다 README에 나와있는 예시 검색어를 참고하여 emoji, ascii art 등을 검색함. 흥미로워 보이는 패키지를 몇 개 선별한 뒤 각각 npm 링크를 타고 들어가 키워드를 통해 다른 패키지를 구경함.

---

## 선정한 패키지

### 1. `cli-highlight`

**선정 이유:**
책이나 교재의 중요한 글에 형광펜으로 밑줄을 치듯, 코드를 작성할 때에도 중요하다고 생각하는 코드나 다시 돌아와서 봐야하는 부분을 강조하고 싶을 때가 있습니다. 이럴 때 해당 코드에 하이라이트를 할 수 있는 기능이 있으면 좋을 것 같다고 생각했습니다.

**이것으로 무엇을 할 수 있을지:**
이전에는 '//!!!!'같은 식으로 다시 돌아와 검토해야할 코드 옆에 표시를 해놓았습니다. 해당 기능을 사용하면 코드를 작성하는 과정에서도 훨씬 깔끔하게 정리할 수 있을 것 같습니다.

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
해당 패키지는 2023-04-12에 마지막으로 업데이트되었으며 이후 3년 가까이 방치되었다. ISC 라이선스를 사용하며, 이는 자유로운 오픈소스 라이선스로, 상업적 사용/수정/배포가 자유로운 편입니다.
하이라이트 키워드를 보고 코드를 강조하는 것으로 이해했는데, 더 자세히 보니 출력에서 하이라이트를 치는 것임을 알게 되었습니다.
---

### 2. `hangul-romanization`

**선정 이유:**
이 기능이 어디에 활용될 수 있을지 궁금해서 더 알아보고 싶었습니다.

**이것으로 무엇을 할 수 있을지:**
예를 들어 지하철 노선도 등을 앱으로 기획할 때, 역 이름을 영어로 romanize할 필요가 있습니다. 이때 해당 패키지를 사용하면 더 효율적이고 체계있게 진행할 수 있을 것입니다.

**확인 결과:**

```
$ npm view hangul-romanization version time.modified license dependencies
version = '1.0.1'
time.modified = '2022-09-02T11:58:22.973Z'
license = 'MIT'

$ npm view hangul-romanization deprecated

```

**출력을 보고 알게 된 것:**
버전이 '1.0.1'로 되어있는 것으로 보아 출시 후 한 번도 업데이트가 되지 않은 패키지임을 알 수 있습니다.
---

### 3. `boxen`

**선정 이유:**
설명에 'Create boxes in the terminal'이라고 나와있는 것을 보고 box가 무엇을 의미하는지 궁금해서 더 알아보게 되었습니다.

**이것으로 무엇을 할 수 있을지:**
결과 또는 안내 출력을 박스로 감싸서 시각적으로 눈에 띄게 만들 수 있습니다. 특히 경고, 중요 안내사항 등을 일반 텍스트와 구분되게 강조하여 터미널 출력에서 핵심 정보가 한 눈에 파악될 수 있게 도와줍니다. 이를 통해 CLI를 더욱 가독성 높게 정돈할 수 있습니다.

**확인 결과:**

```
$ npm view boxen version time.modified license dependencies
version = '8.0.1'
time.modified = '2024-08-05T11:05:04.881Z'
license = 'MIT'
dependencies = {
  'ansi-align': '^3.0.1',
  camelcase: '^8.0.0',
  chalk: '^5.3.0',
  'cli-boxes': '^3.0.0',
  'string-width': '^7.2.0',
  'type-fest': '^4.21.0',
  'widest-line': '^5.0.0',
  'wrap-ansi': '^9.0.0'
}

$ npm view boxen deprecated

```

**출력을 보고 알게 된 것:**
가장 최근 수정일이 24년도 8월로 현재도 활발히 유지보수되고 있는 패키지임을 알 수 있습니다. 라이선스는 MIT 라이선스를 사용 중이다.
---

## 설치해본 패키지

```
$ npm install boxen

added 19 packages, and audited 20 packages in 2s

12 packages are looking for funding
  run `npm fund` for details

found 0 vulnerabilities

SDSPRO@DESKTOP-PR3S9QF MINGW64 ~/Documents/clickidev/oss2026-a1 (main)
$ node try.js
┌─────────────┐
│             │
│   unicorn   │
│             │
└─────────────┘
```

---

## 막혔던 부분 (채점하지 않음)

에러 메시지든 헷갈렸던 부분이든 하나. 두 문장이면 됩니다. 없었으면 없었다고 적습니다.

```
npm view <패키지이름> version time.modified license dependencies
처음에 위 줄 같은 안내를 보고 패키지 이름을 꺽쇠 안에 적는 것으로 이해했습니다. 이 때문에 실행이 되지 않아 몇 번 버벅였습니다.
```

---

## AI 사용

사용했다면 프롬프트와, AI의 설명이 실제와 달랐던 부분을 적습니다.
사용하지 않았다면 "사용하지 않음"이라고만 적으면 됩니다.

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

이 출력을 통해 내가 알 수 있는 정보가 뭐야?
```
첫 패키지의 관리사항을 검색하였을 때 어떤 정보값을 읽어야하는지 헷갈려서 claude.ai에 다음과 같은 프롬포트를 입력하였습니다. AI의 설명에 틀린 부분은 없는 것으로 확인하였습니다.
---

## 제출 전 확인

- [ ] 저장소 이름이 `oss2026-a1`, 공개 범위가 Public
- [ ] `git status` 결과가 `nothing to commit, working tree clean`
- [ ] `node_modules` 폴더를 지우고 `npm install` → `node try.js` 를 다시 해도 실행됨
- [ ] 마지막 커밋을 push함
