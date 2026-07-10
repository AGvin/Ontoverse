<!--
l10n:
  locale: uk_UA
  source_locale: default
  source_path: ../../README.md
  source_hash: gitblob:3943e533635ca7f6621869c9f7316b72d9c0f3cd
  mode: translated
-->

# Регіони щільності history-space

Статус: draft

![Регіони щільності history-space](../../../../assets/uk_UA/diagrams/history-space-density-regions.svg)

Ця діаграма показує, як **temporal density** може відрізнятися між різними регіонами history-space.

## Переклади

- [English](../../)
- Українська — поточна

## Що показує діаграма

Діаграма розділяє history-space на три концептуальні регіони щільності:

- **low temporal density region** — розріджені траєкторії та менше event-nodes;
- **medium temporal density region** — помірна кількість event-nodes і можливостей розгалуження;
- **high temporal density region** — щільні популяції event-nodes і багато близько розташованих переходів.

Усі видимі траєкторії завершуються на рубіновій frontal time plane.

## Інтерпретація

Ontoverse розглядає temporal density як локальну властивість траєкторії або регіону, а не як рівномірне значення для всього history-space.

Одна й та сама frontal-time boundary може перетинати регіони з дуже різною кількістю значущих event-nodes.

Це візуалізує ідею, що local time може накопичуватися нерівномірно в різних історіях або регіонах моделі.

## Важливе обмеження

За frontal time plane не показано жодних event-nodes.

Площина представляє present boundary у цій візуалізації. Вміст за нею означав би future-side structure, яку поточна сторінка моделі ще не визначає.

## Роль у документації

Використовуйте цю візуалізацію для пояснення:

- нерівномірної temporal density;
- регіонів із різною event-node density;
- різниці між frontal time і локально накопиченим time;
- history-space як структурованого поля, а не однієї гілки.
