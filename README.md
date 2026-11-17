# ДЗ: вибір моделі судді (L10) — PayPilot

Локальний суддя `qwen2.5:7b` проти хмарного `claude-sonnet-5-5` на тому самому наборі `l09_labels.jsonl` (32 кейси, `runs: 5`, `rubric.v1`).

Локальний суддя: перевірено на `qwen2.5:7b` станом на 2026-11-17 (дайджест `845dbda0ea48`; конфігурація: `judge.local.env`).

## Що в репозиторії

| Файл | Що це |
| --- | --- |
| `model-selection-recommendation.md` | рекомендація: вердикт, периметр, контракт, дві заяви поруч, ціна, обмін і умови, конфігурація |
| `judge-trust-statement.md` | перша заява про довіру (хмарний суддя, L09) |
| `judge-trust-statement.local.md` | друга заява про довіру (локальний суддя), за формою першої |
| `evals/reports/calibration-l09_labels-20261110T223210.json` | звіт калібрування хмарного судді (L09) |
| `evals/reports/calibration-l09_labels-20261117T193948.json` | звіт калібрування локального судді (L10) |
| `judge.local.env` | Local Judge Configuration (без ключів) |
| `model-selection-recommendation.template.md` | узагальнений шаблон для вибору моделі в іншій системі |

Файл `.env` і ключі в репозиторій не входять.
