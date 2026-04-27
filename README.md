# Policy Risk Memo Architect

[![ClawHub](https://img.shields.io/badge/ClawHub-global--think--tank--analyst-2bc6a4)](https://clawhub.ai/vassiliylakhonin/global-think-tank-analyst)
[![CI](https://github.com/vassiliylakhonin/global-think-tank-analyst/actions/workflows/ci.yml/badge.svg)](https://github.com/vassiliylakhonin/global-think-tank-analyst/actions/workflows/ci.yml)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

## Кратко о навыке

> **Decision‑ready geopolitical и policy memo** для OpenClaw и Codex. 
> Превращает вопросы о региональной политике, санкциях, торговле и регулировании в структурированные, факт‑подтверждённые мему‑выводы, где явно отделены факты, оценки, предположения и «unknown» — это ключ к принятию обоснованных решений.

## Что делает этот skill

- Быстрый короткий бриф (режим A)  
- Стандартный мемо (режим B)  
- Сценарное краткое изложение (режим C)  
- Red‑team‑анализ (режим D)  

Выбирайте режим в зависимости от времени и уровня детализации, которую требует клиент.

## Установка

```bash
openclaw skills install vassiliylakhonin/global-think-tank-analyst
```

## Codex‑вариант

Для Codex просто подключите файл `skills/codex/SKILL.md` в объявление ассистента.

## Примеры запросов

### Режим A – *Quick Brief*

```
Prepare a quick brief on the EU CBAM exposure for a Kazakh metals exporter over the next 12 months.
```

### Режим B – *Standard Memo*

```
Write a policy‑risk memo on sanctions exposure for a Russian energy company operating in Central Asia.
```

### Режим C – *Scenario Brief*

```
Provide a scenario brief on possible US‑China semiconductor control developments for 2026‑2028.
```

### Режим D – *Red‑Team Challenge*

```
Red‑team the claim that supply‑chain sanctions risk for a European tech firm is manageable.
```

## Качество вывода

| Критерий | Что обеспечивается |
|----------|-----------------------|
| **Решения‑ориентировано** | Структура: *Вопрос → Решение → Аудитория → Горизонт времени → Режим доказательств* |
| **Чёткая неопределённость** | Степени `Certain`, `Plausible`, `Judgment`, `Unknown` |
| **Разделение фактов/оценок** | Метки `Fact`, `Assessment`, `Assumption`, `Scenario`, `Unknown` |
| **Дисциплина доказательств** | Ограничение «source‑backed», «reasoning‑only», «mixed» |
| **Потенциальная недоступность данных** | Вывод `EVIDENCE ACCESS LIMITED` при отсутствии живой проверки |

## Структура репозитория

```
/SKILL.md            – основной мейн‑файл
/codex/SKILL.md      – меняется для Codex‑исполнения
/README.md           – этот файл
/LICENSE
```

## Лицензия

MIT – просто. Смотрите файл `LICENSE`.

---

**Если вам потребуется более детальная настройка «ролей» (A‑D) или примеры для конкретных контекстов, спросите.**