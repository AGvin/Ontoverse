# Візуалізації Ontoverse

<!--
l10n:
  locale: uk_UA
  source_locale: default
  source_path: ../../README.md
  source_hash: sha256:pending
  mode: translated
-->

Статус: draft

Цей розділ містить візуальні пояснення концептуального фреймворку Ontoverse.

## Переклади

- [English](../../)
- Українська — поточна

Діаграми є частиною документації, а не декоративними assets. Вони мають залишатися синхронізованими з terminology, що використовується у framework, models та glossary.

## Набір візуалізацій

- [`temporal-density-comparison/`](../../sub/temporal-density-comparison/l10n/uk_UA/) — порівнює low та high temporal density у межах одного frontal-time interval.
- [`convergent-channel/`](../../sub/convergent-channel/l10n/uk_UA/) — показує distinct historical origins, які звужуються в compatibility channel та convergent channel на frontal time plane.
- [`history-space-density-regions/`](../../sub/history-space-density-regions/l10n/uk_UA/) — показує sparse, medium та high temporal-density regions усередині history-space.
- [`uneven-temporal-density/`](../../sub/uneven-temporal-density/l10n/uk_UA/) — порівнює representative density patterns across history-space.
- [`isometric-history-space/`](../../sub/isometric-history-space/l10n/uk_UA/) — показує volumetric, tree-like history-space projection з branching strings, що наближаються до frontal time plane.

## Спільні візуальні правила

Ruby **frontal time plane** представляє present boundary поточного model slice.

Діаграми не мають показувати event-nodes, realized trajectories або channel continuations за frontal time plane, якщо документ явно не визначає future-side area як hypothetical або inaccessible.
