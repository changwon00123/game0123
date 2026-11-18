# 판소리대학교 — 정리된 GitHub Pages 배포본

## 중요한 정리
이번 버전은 이미지 8개를 모두 `assets/` 한 폴더에만 저장합니다. 루트에 이미지 복제본을 올리지 마세요. 이전 버전에서 중복 이미지가 생성된 문제를 바로잡았습니다.

```text
index.html
styles.css
script.js
gallery.js
audio.js
assets/
  hero-campus.webp
  campus-life.webp
  culture.webp
  president-kang.webp
  president-kang.jpg
  master-placeholder.svg
  gallery-2020-1.jpg
  gallery-2020-2.jpg
audio/
  소리1.mp3  (직접 업로드)
  소리2.mp3  (직접 업로드)
  소리3.mp3  (직접 업로드)
```

## 기존 저장소 정리
1. 기존 저장소의 이미지 복제본(최상위에 있는 `.webp` `.jpg` `.svg` 이미지 파일), `assets/` 폴더의 구버전 이미지, 코드 5개 파일을 정리하고 새 ZIP의 내용으로 교체합니다. GitHub에서는 여러 파일을 한 번에 깔끔히 삭제하기 어렵기 때문에 저장소를 로컬로 복제한 뒤 삭제/복사/커밋하거나 GitHub 웹 UI에서 하나씩 삭제해야 합니다.
2. 기존 `audio/` 폴더의 MP3 파일은 **절대 삭제하지 말고 유지**합니다. 이 ZIP에 실제 MP3는 없습니다.
3. ZIP 내부의 `index.html`과 폴더를 **저장소 최상위**로 업로드합니다. 상위 디렉터리가 추가되지 않도록 합니다.
4. 배포 주소: https://changwon00123.github.io/namename/#home

## 사진 및 안내
- 공연 갤러리 2장: 사용자 제공 사진을 사용합니다.
- 강문경 총장 사진: `assets/president-kang.webp` 우선, JPG 대체. 원본 사진을 기계적으로 잘라낸 사진이 아닌 이전 AI 보정본이므로 얼굴 일치 여부 확인이 필요합니다.
- 김판순 단장님의 인증된 실제 독사진은 포함되지 않았습니다. `assets/gallery-2020-1.jpg` 공연 무대 자료 사진으로 소개하며 인물을 김판순 단장으로 특정하지 않습니다.
- 판소리대학교의 조선시대 연혁, 입학 원서 접수는 가상 시연용입니다. 실제 대학이나 학위/접수 제도가 아닙니다.
- `audio/소리1.mp3`, `소리2.mp3`, `소리3.mp3` 는 별도로 준비해야 재생됩니다.
