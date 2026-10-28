## Юрий Туманов · Yuriy Tumanov

**AppSec / MLSecOps** · кандидат технических наук (НИЯУ МИФИ) · в информационной безопасности с 2001 года.
Application security and MLSecOps. PhD in engineering, NRNU MEPhI.

Исследовательская линия — **ZeroFalse**: доказательный (evidence-first) триаж срабатываний статического
анализа локальными языковыми моделями. Модель не получает права на вердикт, пока не сошлётся на проверяемые
улики в коде; при нехватке улик система отвечает `Unknown` и возвращает находку человеку.
Стек: Qwen2.5-Coder-14B-AWQ на vLLM, одна потребительская видеокарта с 16 ГБ VRAM.

*Research line — ZeroFalse: evidence-anchored triage of static-analysis findings with local LLMs. No verdict
without a verifiable citation in the code; when evidence is short the system answers `Unknown` and hands the
finding back to a human.*

### Где что

| | |
|---|---|
| 🌐 Сайт-портфолио | **https://eljees.github.io** |
| 🎓 Google Scholar | **https://scholar.google.com/citations?user=iH0LwcAAAAAJ** |
| 📚 Публикации и выступления | [tumanov-portfolio](https://github.com/Eljees/tumanov-portfolio) — YAML-реестр статей, докладов и заявок |
| 🧩 Исходник сайта | [eljees.github.io](https://github.com/Eljees/eljees.github.io) |
| 💼 LinkedIn | https://www.linkedin.com/in/yury-tumanov-bb55b531/ |

### Открытый код

Патчи в инструменты статического анализа, SBOM-утилиты и сканеры безопасности: pylint, astroid, rubocop,
PMD, SpotBugs, detekt, revive, NullAway, sqlfluff, syft, grype, scancode-toolkit, cve-bin-tool,
DependencyCheck, kubescape, MobSF, OpenSCAP, sbomqs и другие.

К 29 октября 2026 года — **125 публичных PR приняты в сторонние репозитории за последние 12 месяцев** (29.10.2025–29.10.2026; [выборка GitHub](https://github.com/search?q=is%3Apr+author%3AEljees+-user%3AEljees+is%3Apublic+is%3Amerged+merged%3A2025-10-29..2026-10-29&type=pullrequests)).

As of 29 October 2026: **125 public PRs merged into external repositories over the past 12 months** (29 October 2025–29 October 2026).

На эту дату: **130 открытых PR**, **34 закрытых без merge**. За всё время: принятые патчи в **61 проекте**, всего затронуто **133 репозитория**.
As of that date: **130 open PRs**, **34 closed without merge**. All time: accepted patches in **61 projects**, **133 repositories** contributed to.

Живые счётчики: [смерджённые PR](https://github.com/search?q=is%3Apr+author%3AEljees+-user%3AEljees+is%3Apublic+is%3Amerged&type=pullrequests) ·
[все PR](https://github.com/search?q=is%3Apr+author%3AEljees+-user%3AEljees+is%3Apublic&type=pullrequests)

### Доклады 2026

<p>
  <a href="https://eljees.github.io/#talk-photos">
    <img src="https://eljees.github.io/assets/photos/iscra-talks-stage.png" width="240" alt="Юрий Туманов на сцене ISCRA Talks / Yuriy Tumanov speaking at ISCRA Talks">
  </a>
  <br>
  <sub>ISCRA Talks · фото / photo: @romanpnn · <a href="https://eljees.github.io/#talk-photos">фотографии выступления / talk photos</a></sub>
</p>

- **ISCRA Talks 2026** — «Не все дефекты одинаковы: как структура SAST-находки ломает LLM-триаж» · [слайды](https://eljees.github.io/slides/Tumanov_ZeroFalse_ISCRA_2026.pdf)
- **OFFZONE 2026**, трек AppSec.Zone — «ZeroFalse для SAST: локальные LLM, evidence-gate и триаж без галлюцинаций» · [слайды](https://eljees.github.io/slides/Tumanov_ZeroFalse_OFFZONE_2026.pdf) · [видео](https://vkvideo.ru/video-172362100_456239390) · [разбор на Tproger](https://tproger.ru/articles/ai-piwet-ai-proveryaet-pochemu-uyazvimosti-poyavlyayutsya-pachkami-i-k)
- **ёPRSTCON 2026** — «От мешка false positive до нормального вердикта» · [видео, слайды, транскрипт](https://www.yoprstcon.ru/articles_manual_locB_html/11-zerofalse-llm-triage.html)
