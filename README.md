# AI 거버넌스 아카데미: 한국어판

> **2026년 11월 26일 보존판.** 이 저장소는 보존 처리되어 읽기 전용이며, 법률 사항을 포함하여 더 이상 수정되지 않습니다. 기계 초벌 번역이며, 저자 검토는 완료되지 않았습니다. 한국어 작업은 책으로 한정합니다. 유지 관리하는 저장소는 [DISPOSITION.md](https://github.com/rolldabones/rolldabones/blob/main/DISPOSITION.md)에 있습니다.

> **Archived edition of 26 November 2026.** This repository is archived and read-only. It receives no corrections, legal ones included: verify every statement of law, regulation or standard against a current primary source before you rely on it. What I maintain, and why this repository is not part of it, is in [DISPOSITION.md](https://github.com/rolldabones/rolldabones/blob/main/DISPOSITION.md). Cite this edition as *AI Governance Academy, Korean edition*, v0.2.2 (26 November 2026). The license and [LICENSING.md](https://github.com/rolldabones/rolldabones/blob/main/LICENSING.md) still apply. Reach me at sonupaik@gmail.com. A machine draft. The author's line review was not completed.

*AI Governance Academy, Korean edition*

**고객사 대상 출판물의 한국어 번역**

**백선우**
GRC Solutions Korea 대표이사(CEO)

**v0.2.2 · 2026년 11월 26일 · 보존판(archived edition) · 라이선스: [CC BY-NC-SA 4.0](LICENSE.md) · 변경 기록: [CHANGELOG.md](CHANGELOG.md) · [English edition](https://github.com/rolldabones/AI-Governance-Academy)**

> **번역 및 검토 현황: 초벌 번역, 저자 검토 미완료 (machine draft; the author's review was not completed before the repository was archived on 26 November 2026).** 이 저장소의 한국어 텍스트는 영어판 출판물을 AI로 번역한 초벌 번역본으로, 저자의 검토는 2026년 11월 26일 보존 처리 시점까지 완료되지 않았습니다. 최종 번역본이 아니며, 영어 원문을 공식 기준으로 합니다. 한국어판과 영어 원문 사이에 차이가 있는 경우 영어 원문이 우선합니다.

[English below](#english)

---

## 이 저장소에 관하여

이 저장소는 [AI-Governance-Academy](https://github.com/rolldabones/AI-Governance-Academy)의 출판물을 한국어로 옮겨 제공합니다. 영어판에는 고객사 대상 프롬프트 템플릿과 출판물이 함께 실려 있으며, 이 저장소는 2026년 11월 15일자 영어판 v1.22.0을 기준으로 그중 출판물 한 편을 번역했습니다. 이후 영어판 v1.24.4의 *Boeing* 관련 정정 사항도 번역하여 반영했습니다. 템플릿은 번역하지 않았으며, 다른 출판물의 번역 여부와 순서는 저자가 정합니다.

출판물에 쓰이는 세 가지 핵심 원칙인 **Slow AI**(슬로우 AI), **Informed Intent**(정보에 기반한 의도), **Final Liability**(최종 책임)는 영문 명칭을 그대로 사용하되, 각 파일에서 처음 등장할 때 한국어 설명을 덧붙였습니다. 각 원칙의 규범적 내용은 계정 전체의 기준 문서인 [DOCTRINE.md](https://github.com/rolldabones/rolldabones/blob/main/DOCTRINE.md)에서 확인할 수 있습니다.

## 파일

| 파일 | 내용 | 영어 원문 |
|---|---|---|
| [`the-evidence-and-the-exit-ko.md`](the-evidence-and-the-exit-ko.md) | 『증거와 출구』: 2026년 힌턴 강연(Hinton Lectures 2026)에 관한 심화 워크숍(Advanced Workshop). 강연의 독해, 보강 증거, 본인-대리인 문제의 경제학과 법과 거버넌스, 세 원칙에 따른 독해, 약 3시간의 진행 순서, 분류할 10개의 진술, 45분 연습, 5개의 토론 질문 | [the-evidence-and-the-exit.md](https://github.com/rolldabones/AI-Governance-Academy/blob/main/the-evidence-and-the-exit.md) |

## 번역 방식

이 글은 AI를 활용하여 번역했으며, 저자가 번역 결과를 검토하는 방식으로 작업했습니다. 이 글이 AI 작업에 요구하는 방식 그대로, AI가 생성한 번역문은 초안이며 최종적인 판단과 책임은 저자에게 있습니다.

- 2026년 11월 15일, 영어 원문을 편집한 Claude 세션(Claude Fable 5.2, claude-fable-5-2)에서 영어 원문 전체를 한국어로 옮겼습니다. 일괄 처리(batch)가 아니라 한 세션에서 절 단위로 번역했으며, 다른 모델이나 사람에 의한 독립적 검토는 아직 거치지 않았습니다.
- 번역 기준은 [한국어판 책](https://github.com/rolldabones/final-liability-rests-with-the-human-ko-wip)의 기준을 따랐습니다. 문체(본문은 한다체), 세 가지 핵심 원칙의 명칭, 주요 용어(예: governance, risk management and compliance는 '거버넌스, 리스크 관리 및 컴플라이언스'), 조문 번호, 사건명 및 날짜의 표기 원칙이 여기에 해당합니다. 원칙의 약식 진술은 한국어판 책의 문장을 그대로 사용했습니다.
- 판례명, 법령 인용, 영어 문헌의 제목, 인용 부호 안의 발언, 연사의 이름은 원문 표기를 유지했습니다. 인용 부호 안의 발언에는 괄호로 한국어 설명을 덧붙였습니다.
- 자동화 스크립트를 이용해 제목 체계(30개), 표의 행(26개), 목록 항목, 링크(88개 모두 일치), 상표 표기, 경고 표시 및 맺음말이 영어 원문과 일치하는지 확인했습니다. 영어 원문의 189개 블록에 대해서는 각 블록의 숫자가 대응하는 한국어 블록에도 모두 있는지 검증했습니다. 이 대조는 구조와 숫자를 확인할 뿐, 의미의 정확성까지 확인하지는 않습니다.
- 이 글에서 처음 정한 번역 용어는 [CHANGELOG.md](CHANGELOG.md)에 목록으로 기록했으며, 2026년 11월 15일 저자가 승인했습니다.
- 2026년 11월 25일, 한국어 독자의 의견을 반영하여 이 안내문의 문체를 다듬고, 한국어판 책의 새 제목에 맞추어 원칙 이름의 한국어 설명을 고쳤습니다(v0.2.0).

저자의 문장별 검토는 완료되지 않았으며, 이 저장소는 2026년 11월 26일 보존 처리되었습니다.

## 인용

> 백선우(Son-U Michael Paik). 『증거와 출구』(*The Evidence and the Exit*, 한국어판), AI Governance Academy 한국어판 v0.2.2, 초벌 번역, 저자 검토 미완료. GRC Solutions Korea, 2026. https://github.com/rolldabones/AI-Governance-Academy-ko-wip

내용을 인용할 때는 기준 텍스트인 영어판을 인용해 주십시오. 기계가 읽을 수 있는 인용 정보는 [CITATION.cff](CITATION.cff)에 있습니다.

## 라이선스

[CC BY-NC-SA 4.0](LICENSE.md). 영어판과 같은 라이선스입니다. 상업적 이용은 [LICENSING.md](https://github.com/rolldabones/rolldabones/blob/main/LICENSING.md)를 따릅니다. 이 저장소의 내용은 법률 자문이 아니며, 이를 읽는 것만으로 변호사와 의뢰인 관계가 성립하지 않습니다.

---

## English

**Status: 초벌 번역, 저자 검토 미완료 (machine draft; the author's review was not completed before the repository was archived on 26 November 2026).** This repository is the parallel Korean repository of [AI-Governance-Academy](https://github.com/rolldabones/AI-Governance-Academy). It holds Korean translations of that repository's client-facing publications, made from English v1.22.0 (15 November 2026), with the correction of English v1.24.4 carried in translation. On 25 November 2026, after feedback from Korean readers, the Korean README moved to the polite register (합니다체) and the doctrine gloss follows the book's new Korean title, 최종 책임은 인간이 진다; the publication stays in 한다체. Each is a machine draft, not a finished translation: the author's line review was not completed before the repository was archived on 26 November 2026. The English edition is the text of record and governs wherever the two differ.

**What is here.** One publication: `the-evidence-and-the-exit-ko.md`, the Korean text of *The Evidence and the Exit: An Advanced Workshop on the Hinton Lectures 2026*. The eight program templates are not translated. Whether and in what order the other eleven publications are translated is the author's decision.

**How it was made.** The translation was made the way the piece says AI work should be governed: the model's output is a draft and a named human answers for the result. On 15 November 2026 the whole English text was translated in the same Claude session that edited it (Claude Fable 5.2, claude-fable-5-2), section by section and not as a batch; no second model and no person has reviewed it independently yet. The instructions follow the [Korean edition of the book](https://github.com/rolldabones/final-liability-rests-with-the-human-ko-wip): the register (한다체), the doctrine names (in English, with the Korean gloss at first use in each file), the fixed terms and the doctrines' short forms in that edition's wording. Case names, statutory citations, titles of English sources, quoted words and speakers' names stay as written, and quoted words carry a Korean gloss in parentheses. A script compared the file with its English source for headings (30), table rows (26), list items, links (all 88 present), trademark and warning marks and the closing line, and checked that every number in each of the 189 English blocks appears in the matching Korean block. That comparison tests structure and numbers. It does not test meaning.

**What remains.** The author's line review. The terms first rendered here, listed in the CHANGELOG, were accepted by the author on 15 November 2026. The status label changes when that review is complete.

**Cite** the English edition for its content. Nothing here is legal advice, and reading it creates no attorney-client relationship.

## Part of the ecosystem

This repository is the Korean edition of publications in the account's client-facing layer. The canonical map of all repositories is [ECOSYSTEM.md](https://github.com/rolldabones/rolldabones/blob/main/ECOSYSTEM.md) in the profile repository. The three doctrines are used as stated in [DOCTRINE.md](https://github.com/rolldabones/rolldabones/blob/main/DOCTRINE.md); this edition translates them and adds no doctrine (ECOSYSTEM.md protocol item 6).

Nearest neighbors:
- [AI-Governance-Academy](https://github.com/rolldabones/AI-Governance-Academy): the English edition and text of record, from which this edition is translated

---

**Final Liability rests with the Human.**
