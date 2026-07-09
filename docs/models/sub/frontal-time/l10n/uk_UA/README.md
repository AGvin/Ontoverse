# Модель frontal time

<!--
l10n:
  locale: uk_UA
  source_locale: default
  source_path: ../../README.md
  source_hash: sha256:pending
  mode: translated
-->

Статус: draft

Frontal Time Model вводить розрізнення між глобальним параметром упорядкування та локально досвідченим часом.

![Порівняння темпоральної щільності](../../../visualizations/assets/default/diagrams/temporal-density-comparison.svg)

## Переклади

- [English](../../)
- Українська — поточна

## Frontal Time

Frontal time (фронтальний час) є запропонованим глобальним параметром упорядкування для розгортання history-space.

Його можна візуалізувати як wavefront або plane, що рухається крізь простір можливих історій. Це метафоричний образ: frontal time ще не визначено як фізичне поле, metric або вимірювана величина.

У діаграмах Ontoverse frontal time plane представлена як рубінова boundary і зазвичай трактується як present boundary описаного model slice.

## Local Time

Local time (локальний час) — це час, досвідчений уздовж конкретної historical trajectory.

Робоча інтуїція полягає в тому, що experienced time відповідає не лише зовнішній координаті, а накопиченню значущих physical transitions уздовж trajectory.

```text
local time ~ accumulated significant event-nodes
```

## Temporal Density

Temporal density (темпоральна щільність) — запропонована кількість значущих event-nodes на одиницю frontal time.

```text
temporal density ~ event-nodes / frontal-time interval
```

Це концептуальний вираз, а не визначене фізичне рівняння.

Див. також:

- [`temporal-density-comparison`](../../../../visualizations/sub/temporal-density-comparison/l10n/uk_UA/);
- [`history-space-density-regions`](../../../../visualizations/sub/history-space-density-regions/l10n/uk_UA/);
- [`uneven-temporal-density`](../../../../visualizations/sub/uneven-temporal-density/l10n/uk_UA/).

## Відкриті проблеми

- Визначити, що саме кваліфікується як significant event-node.
- Уточнити, чи `event-nodes / frontal-time` може стати строгим measure.
- Уточнити, як ця модель повʼязана з proper time у relativity.
