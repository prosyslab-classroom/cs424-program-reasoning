---
name: translate-readme
description: Translate a course README.md into a matching README.en.md mirror while preserving Markdown structure, links, tables, and inline HTML.
---

# translate-readme

Use this skill when a repository has a syllabus-style `README.md` in Korean and needs a faithful English mirror.

## Workflow
1. Treat `README.md` as the source of truth unless the user says otherwise.
2. Translate prose naturally into English.
3. Preserve Markdown structure exactly: headings, lists, tables, blockquotes, links, image tags, inline HTML, and filenames.
4. Do not translate URLs, file paths, course codes, homework labels, or proper nouns unless they are clearly part of the prose.
5. Write the result to `README.en.md` in the repository root.
6. For future updates, run `scripts/translate-readme.py` from the repository root.

## Editing Rules
- Keep the English mirror aligned with `README.md`.
- Avoid unnecessary rewrites when only a small source change occurred.
- Keep terminology stable across updates unless the source changed.
- Do not include the sentence `본 강의에서는 쉬운 전문 용어를 사용하여 소박하게 지식을 전달한다.` in the English mirror.
- Do not make minor grammar or style edits beyond the minimum needed for a faithful translation.
- Use the following style for translations:
  - "프로그래밍 언어 이론" → "Theory of Programming Languages"
  - "수업정보" → "Logistics"
  - "허기홍" → "Kihong Heo"
  - "교수" → "Instructor"
  - "조교" → "TAs"
  - "강의 소개" → "Course Description"
  - "몰입을 위한 약속" → "Commitment to Engagement"
  - "강의실" → "Location"
- Use the English names of the TAs as listed on https://prosys.kaist.ac.kr/members/.
