<!--
l10n:
  locale: uk_UA
  source_locale: default
  source_path: ../../README.md
  source_hash: gitblob:ab62afe103589dde6470c2abe9fe02f5f19d37d6
  mode: translated
-->

# Нерівномірна темпоральна щільність у history-space

Статус: draft

![Нерівномірна темпоральна щільність у history-space](../../../assets/uk_UA/diagrams/uneven-temporal-density.svg)

Ця діаграма порівнює кілька типових патернів temporal-density усередині Ontoverse history-space.

## Переклади

- [English](../../)
- Українська — поточна

## Що показує діаграма

Кожен рядок представляє інший патерн event-node density перед тією самою рубіновою frontal time plane.

Показані патерни:

- **Sparse** — лише кілька event-nodes у межах інтервалу.
- **Sparse to dense** — event-nodes частішають у міру наближення траєкторії до frontal time plane.
- **Dense to sparse** — event-nodes спочатку щільні, а потім стають розташованими ширше.
- **Burst cluster** — event-nodes зосереджені в локальному кластері.
- **Uniform medium** — event-nodes розподілені відносно рівномірно із середньою щільністю.

## Інтерпретація

Мета цієї діаграми — показати, що temporal density не обовʼязково має бути рівномірною в history-space.

Різні траєкторії можуть накопичувати різну кількість local time, навіть коли їх порівнюють із тією самою frontal-time boundary.

## Без future-side content

Кожна траєкторія завершується на frontal time plane.

Діаграма навмисно не показує реалізовані гілки або event-nodes за площиною, бо future side не є частиною поточного model slice.

## Роль у документації

Використовуйте цю візуалізацію для пояснення:

- нерівномірної temporal density;
- накопичення local time;
- sparse, dense і clustered event-node patterns;
- чому history-space слід розглядати як нерівномірний, а не як рівну сітку.
