# Changelog

All notable changes to this repository are documented here. Versioning follows [Semantic Versioning](https://semver.org/). The README, CITATION.cff and this file version in lockstep; prior versions are superseded, never silently overwritten. Status until the author's line review is complete: 초벌 번역, 저자 검토 중 (machine draft under the author's review).

## v0.2.0 (2026-11-25)

Minor release, 25 November 2026 (KST): the register of the README and the doctrine gloss revised after feedback from a Korean reader on the Korean edition of the book, on Michael Paik's ruling of 25 November 2026 (book Korean edition v0.3.0). Prepared with Claude (claude-opus-5-5), approved by Michael Paik.

- **README.** The Korean section moves from 한다체 to 합니다체, in the wording adopted for the book's README; the status line keeps the statement that the text was translated with AI. It now also states that the correction of English v1.24.4 was carried (v0.1.2), where it named only v1.22.0, and the English section records the change.
- **The Evidence and the Exit.** The gloss on the doctrine name in the thesis section (명제) reads (최종 책임은 인간이 진다), following the book's new Korean title, as this repository's rule on the doctrines' short forms requires. No other line of the publication changes; it stays in 한다체.
- README and CITATION.cff to v0.2.0. Status unchanged: 초벌 번역, 저자 검토 중.

## v0.1.2 (2026-11-16)

Patch release, 16 November 2026 (KST): the mirror of English `AI-Governance-Academy` v1.24.4, which corrects *The Evidence and the Exit* for the 2026 *Boeing* decision (account-maintenance `OPEN-ITEMS.md` item 48(a)), corrected in translation on Michael Paik's ruling of 16 November 2026 for the book. Translated by Claude (claude-opus-5-5) in the remediation session, in the terms of the Korean edition of the book, with the Chapter 15 terms as the author ruled them in its v0.2.5 (item 48(b)). README and CITATION.cff to v0.1.2. Status unchanged: 초벌 번역, 저자 검토 중. Prepared with Claude, approved by Michael Paik.

- **`the-evidence-and-the-exit-ko.md`, mirroring the English:** a dated amendment note (개정 노트); the Rule's status note; the Oversight bullet; the Conclusion; the sources (the opinion added, the Forum post recorded as the earlier source, the opinion removed from what was not read). The supersession entry 2026년 결정 전에 쓰였고 is now quiet in class D.
- One term rendered here for the first time, for the author's ruling with the line review: demand futility = 제소 청구 무익(demand futility). Rule 23.1, demand, particularized facts, yellow flag and red flag follow the book's Chapter 15 as corrected in its v0.2.5 (형평법원 규칙(Court of Chancery Rule) 23.1, 제소 청구(demand), 구체적이고 특정된 사실(particularized facts), 주의 신호(yellow flag), 경고 신호(red flag)).

## v0.1.1 (2026-11-16)

Patch release, 16 November 2026 (KST). The terms first rendered in v0.1.0 are accepted: Michael Paik ruled on 15 November 2026 that they are no longer assumptions awaiting his ruling. The heading of their list in the v0.1.0 entry below says so; the list itself is unchanged. No translated text changes: `the-evidence-and-the-exit-ko.md` is byte for byte as released in v0.1.0. The README's two status sentences on what remains (Korean and English) now name the line review only; README and CITATION.cff to v0.1.1. The status label stays 초벌 번역, 저자 검토 중 until the line review is complete. Prepared with Claude, approved by Michael Paik.

## v0.1.0 (2026-11-15)

First release, 15 November 2026 (KST): the Korean machine draft of *The Evidence and the Exit: An Advanced Workshop on the Hinton Lectures 2026*, published for the author's line review. Decided by Michael Paik on 15 November 2026: a parallel repository in Korean, on the precedent of [final-liability-rests-with-the-human-ko-wip](https://github.com/rolldabones/final-liability-rests-with-the-human-ko-wip), under this name. Prepared with Claude, approved by Michael Paik.

### Source and run
- **Source.** `the-evidence-and-the-exit.md` as released in [AI-Governance-Academy](https://github.com/rolldabones/AI-Governance-Academy) v1.22.0 of 15 November 2026, less the one line that points to this edition.
- **Run.** Translated on 15 November 2026 (KST) in the Claude session that edited the English text (Claude Fable 5.2, claude-fable-5-2), section by section, in three parts assembled by script. Not a batch run. No second model and no person has reviewed the Korean independently.
- **Instructions.** Those of the Korean edition of the book (v0.2.2): register 한다체; doctrine names in English with the Korean gloss at first use; the closing line in English; that edition's fixed terms and its Korean wording of the three short forms. Case names, statutory citations, titles of English sources, quoted words and speakers' names stay as written; quoted words carry a Korean gloss in parentheses; bracketed status notes on the law are translated and their pinpoints left as cited.

### Checks
- **By script, against the English source:** 30 headings at the same levels; 26 table rows with the same cell counts; 90 list items and 10 numbered statements; all 88 links present, with two more in the status note that point to the English edition; three trademark marks, three ⚠ marks and nine "Unknown"; the closing line last; no em dash. Every number in each of the 189 English blocks appears in the matching Korean block. The Contents list is generated from the translated section headings.
- **Not checked:** meaning, by anyone other than the session that translated it. A check of structure and numbers does not show that a sentence says what its source says.

### Terms first rendered here, accepted by the author on 15 November 2026
- Advanced Workshop = 심화 워크숍(Advanced Workshop); the title = 증거와 출구.
- exit: 종료 where it is the fourth element of an Informed Intent authorization, 출구 where it is the title's word, a GRCnext™ Exit or a working way out.
- alignment = 정렬; reward hacking = 보상 해킹; grader and scorer = 채점기; evaluator = 평가자; shortcut = 지름길; swarm = 스웜.
- agency costs = 대리인 비용; monitoring = 감시; bonding = 보증; residual loss = 잔여 손실; multitask problem = 다중 과업 문제.
- agent: 대리인 in the economist's and the lawyer's sense, 에이전트 for an AI agent; electronic agent = 전자적 대리인; instrumentality = 도구; apparent authority = 표현대리, as in the book.
- good faith = 선의; bad faith = 악의; duty of oversight = 감독 의무; reliance (8 Del. C. § 141(e)) = 의존; liability rule = 책임 규칙; floor = 하한선; dismissed = 각하하였다.
- governed, explained, audited as test names = 거버넌스할 수 있음, 설명할 수 있음, 감사할 수 있음; short form = 약식 진술; nominee = 명목상의 소유자; intervention path = 개입 경로.
- the lifecycle = 명세 시 지명되고, 확인 시 귀속되며, 의존이 이어지는 동안 유지된다, with the English beside it at first use.
- materiality = 중요성; three lines of defense = 3선 방어 체계; tabletop exercise = 도상 훈련, as in the book; fact sheet = 사실 자료; key = 해답; closure rate = 종결률; reconciliation = 대사.
- benevolence = 자애, to keep it apart from 선의 (good faith).
- Speakers' and authors' names are left in Latin script.
- One addition for sense: where the English says that the doctrine and Christiano's proposal share a word, the Korean adds (slow) after 한 단어, because the Korean verb for slowing does not show the shared word.

**Final Liability rests with the Human.**
