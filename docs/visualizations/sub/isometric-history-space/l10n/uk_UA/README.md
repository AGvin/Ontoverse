<!--
l10n:
  locale: uk_UA
  source_locale: default
  source_path: ../../README.md
  source_hash: gitblob:1305322d8ab80c42e0e44da260aa959ffc2b9a64
  mode: translated
-->

# Ізометричний history-space

Статус: draft

![Ізометрична діаграма history-space](../../../../assets/uk_UA/diagrams/isometric-history-space.svg)

Ця візуалізація представляє history-space як обʼємну структуру, а не як плоску timeline.

Діаграма використовує ізометричну проєкцію, щоб показати кілька деревоподібних realized strings, які рухаються через той самий обʼєм history-space до рубінової **frontal time plane**.

## Переклади

- [English](../../)
- Українська — поточна

## Концептуальне читання

- **History-space volume**: показаний box представляє локальний концептуальний зріз можливої або реалізованої історичної структури.
- **Tree-like strings**: кольорові strings представляють реалізовані історичні гілки, які можуть розщеплюватися на child branches.
- **Event-nodes**: кола позначають значущі event-nodes. У цьому SVG центр кожного вузла також є точкою його видимої string.
- **Frontal time plane**: рубінова площина праворуч представляє поточну межу показаного model slice.
- **No realized future-side continuation**: реалізовані гілки завершуються на frontal time plane або перед нею.

## Навіщо ізометрична проєкція

Попередні плоскі діаграми корисні для порівняння density patterns, але вони не показують достатньо ясно, що Ontoverse history-space задуманий як обʼємна концептуальна структура.

Ізометричний вигляд полегшує розуміння таких ідей:

- гілки можуть розходитися більш ніж в одному візуальному вимірі;
- різні регіони можуть мати різну event-node density;
- кілька tree-like structures можуть наближатися до однієї frontal time plane;
- сумісність із frontal boundary не вимагає, щоб усі історії були візуально сплющені в одну лінію.
