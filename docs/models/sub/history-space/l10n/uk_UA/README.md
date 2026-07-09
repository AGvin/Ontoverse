# Модель history-space

<!--
l10n:
  locale: uk_UA
  source_locale: default
  source_path: ../../README.md
  source_hash: sha256:pending
  mode: translated
-->

Статус: draft

History-Space Model описує реальність як структурований простір можливих історій.

Історія не розглядається як єдина абсолютна timeline. Вона розглядається як trajectory крізь простір сумісних states, records та interactions.

![Регіони щільності history-space](../../../visualizations/assets/default/diagrams/history-space-density-regions.svg)

## Переклади

- [English](../../)
- Українська — поточна

## Базова інтуїція

Реальність можна уявити як простір, що містить багато historical trajectories.

Ці trajectories подібні до threads або strings. Вони можуть розгалужуватися, коли стають можливими несумісні продовження, і пізніше входити у спільні future channels, коли їхні локально доступні стани стають еквівалентними за обраним описом.

Ключова ідея: history-space не очікується рівномірно щільним. Деякі регіони можуть містити sparse event-node patterns, інші — dense або clustered event-node structures.

## Елементи

- **Historical trajectory** — шлях крізь history-space.
- **Event-node** — значуща точка переходу в historical trajectory.
- **Divergence node** — точка, де одна trajectory розділяється на кілька несумісних продовжень.
- **Compatibility channel** — спільна access structure, у якій можуть взаємодіяти лише mutually compatible states, records та observers.
- **Convergent channel** — compatibility channel, у який входить більше ніж одна historical trajectory.

Див. також [`convergent-channel`](../../../../visualizations/sub/convergent-channel/l10n/uk_UA/) для поточного візуального пояснення.

## Відкриті проблеми

- Математично визначити обʼєкт `history-space`.
- Уточнити, коли дві історії є locally equivalent.
- Повʼязати compatibility channels із decoherence та records.
- Уточнити, чи temporal density слід вимірювати через action, entropy, information change, decoherence rate або іншу величину.
