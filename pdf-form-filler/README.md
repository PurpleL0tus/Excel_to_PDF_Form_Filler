# PDF 양식 채우기 · PDF Form Filler

Excel 표의 행마다 PDF(또는 Word) 양식을 하나씩 자동으로 채워 줍니다. 파일은 컴퓨터 밖으로 나가지 않습니다.

Fills a PDF (or Word) form for every row of an Excel sheet. Your files never leave your computer.

---

## 한국어

### 사용 방법
1. **문서** — 데이터가 들어갈 자리마다 `T@RG3T`를 적어 둔 PDF 또는 Word(.docx) 파일을 넣습니다.
2. **데이터** — Excel 파일을 넣고, 열 제목 행과 만들 행, 파일 이름으로 쓸 열을 고릅니다.
3. **열과 칸 연결하기** — 각 칸(#1, #2 …)에 들어갈 열을 고릅니다. 계산기 버튼으로 계산한 값도 넣을 수 있습니다.
4. **PDF 만들기** — 모든 PDF가 ZIP 파일 하나로 저장됩니다.

자세한 내용은 페이지의 **설명서** 버튼에 있습니다.

### 보안
모든 작업은 브라우저 안에서 이루어집니다. 파일을 받는 서버가 없고, 파일 내용은 어디로도 전송되지 않습니다. 인터넷은 페이지와 도구를 처음 불러올 때만 씁니다.

### 웹사이트로 공개하기 (GitHub Pages)
1. 저장소의 **Settings → Pages**로 갑니다.
2. **Source**에서 *Deploy from a branch*, 브랜치 `main`, 폴더 `/ (root)`를 고르고 **Save**를 누릅니다.
3. 1~2분 뒤 `https://<사용자이름>.github.io/<저장소이름>/` 주소로 열 수 있습니다.

`index.html`을 더블클릭해서 바로 열면 브라우저 보안 때문에 글꼴을 불러오지 못합니다. GitHub Pages처럼 웹 주소로 여세요.

---

## English

### How to use
1. **Document** — add a PDF or Word (.docx) file with `T@RG3T` typed wherever data should go.
2. **Data** — add an Excel file, then choose the title row, the rows to make and the file name column.
3. **Match columns to boxes** — choose the column for each box (#1, #2 …). The calculator button puts a calculated value in a box.
4. **Make PDFs** — every PDF is saved in one ZIP file.

The **Manual** button on the page explains everything in detail.

### Security
Everything happens inside the browser. There is no server that receives files, and file contents are never sent anywhere. The internet is only used to load the page and its tools.

### Publish as a website (GitHub Pages)
1. Go to the repository's **Settings → Pages**.
2. Under **Source**, choose *Deploy from a branch*, branch `main`, folder `/ (root)`, and press **Save**.
3. After a minute or two it opens at `https://<username>.github.io/<repository>/`.

Double-clicking `index.html` to open it directly won't work, because browsers block loading the fonts from a local file. Open it from a web address such as GitHub Pages.

---

## Files

| File | |
|---|---|
| `index.html` | The whole app / 앱 전체 |
| `fonts/` | Noto Sans KR, 9 weights, with `OFL.txt` |
| `docx-preview.min.js`, `html-to-image.js` | Used for Word files / Word 파일 처리 |
| `THIRD_PARTY_NOTICES.md` | Licenses of the libraries and fonts used |

Made with Opus 5.5 (and with love) by John
