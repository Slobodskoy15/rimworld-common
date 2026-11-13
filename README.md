# Work Manager & LordKuper.Common — RimWorld 1.7 build

**EN** · [RU ниже](#work-manager--lordkupercommon--сборка-под-rimworld-17)

Unofficial community rebuild of **Work Manager** for **RimWorld 1.7**.

Work Manager automates assigning work priorities to your pawns and, optionally, their daily work schedules — so you stop juggling the Work tab by hand every time the colony grows.

## Why this build exists

The original mod by [LordKuper](https://github.com/LordKuper) supports RimWorld 1.1–1.6, and its old DLLs fail to load on 1.7 (`ReflectionTypeLoadException`) — which also breaks the **Numbers** mod's "Colonists" tab.

This build was **rebuilt from the original sources** against the 1.7 assemblies. **No source code was changed** — only `About/About.xml` declares 1.7 support. Verified in game on 1.7.4990: both mods initialize and work, clean player log.

## Install

1. Requires [Harmony](https://steamcommunity.com/sharedfiles/filedetails/?id=2009463077).
2. Download **[Release v1.7.0](../../releases/tag/v1.7.0)** — it contains both mod folders:
   - `LordKuper.Common\`
   - `WorkManager\`
3. Extract both into your `Mods` directory.
4. In the mod list: **LordKuper.Common above Work Manager**, Harmony at the top.

## Notes

- Unofficial build — **not supported by the original author**. If an official 1.7 update appears on the [Workshop](https://steamcommunity.com/sharedfiles/filedetails/?id=2029596262), switch back to it and close this topic.
- Steam Workshop updates overwrite DLLs — use the versions from the release.
- Licensed under **CC-BY-NC-SA**. Original mod by **LordKuper**; this redistribution follows the license terms (attribution, non-commercial, share-alike).

### Support the modder

If this build saved you time — check out my other mods, or drop a coin:  
[![Boosty](https://i.imgur.com/rJsfGuJ.jpeg)](https://boosty.to/slobodskoy_modding)  
**🔥 [BOOSTY PAGE](https://boosty.to/slobodskoy_modding)**

---

# Work Manager & LordKuper.Common — сборка под RimWorld 1.7

Неофициальная пересборка мода **Work Manager** для **RimWorld 1.7**.

Work Manager автоматически расставляет приоритеты работ пешкам и, опционально, их ежедневное расписание работ — чтобы не двигать галочки во вкладке «Работа» руками каждый раз, когда колония растёт.

## Зачем эта сборка

Оригинальный мод от [LordKuper](https://github.com/LordKuper) поддерживает RimWorld 1.1–1.6, а его старые DLL не загружаются на 1.7 (`ReflectionTypeLoadException`) — из-за этого также ломается вкладка «Колонисты» мода **Numbers**.

Эта сборка **пересобрана из оригинальных исходников** против сборок игры 1.7. **Исходный код не изменён** — только `About/About.xml` объявляет поддержку 1.7. Проверено в игре на 1.7.4990: оба мода инициализируются и работают, лог чистый.

## Установка

1. Требуется [Harmony](https://steamcommunity.com/sharedfiles/filedetails/?id=2009463077).
2. Скачайте **[Release v1.7.0](../../releases/tag/v1.7.0)** — внутри обе папки модов:
   - `LordKuper.Common\`
   - `WorkManager\`
3. Распакуйте обе в каталог `Mods`.
4. В списке модов: **LordKuper.Common выше Work Manager**, Harmony в самом верху.

## Примечания

- Неофициальная сборка — **автором не поддерживается**. Если на [Workshop](https://steamcommunity.com/sharedfiles/filedetails/?id=2029596262) появится официальное обновление под 1.7 — вернитесь на него, а тему можно закрыть.
- Обновление Workshop-версии перезапишет DLL — используйте версии из релиза.
- Лицензия **CC-BY-NC-SA**. Оригинальный мод — **LordKuper**; распространение по условиям лицензии (указание авторства, некоммерческое использование, те же условия для производных).

### Поддержать мододела

Если сборка сэкономила вам время — гляньте мои другие моды или киньте копейку:  
[![Boosty](https://i.imgur.com/rJsfGuJ.jpeg)](https://boosty.to/slobodskoy_modding)  
**🔥 [BOOSTY PAGE](https://boosty.to/slobodskoy_modding)**
