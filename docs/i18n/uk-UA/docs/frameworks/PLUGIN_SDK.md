# OmniRoute Plugin SDK (Українська)

🌐 **Languages:** 🇺🇸 [English](../../../../frameworks/PLUGIN_SDK.md) · 🇪🇹 [am](../../../am/docs/frameworks/PLUGIN_SDK.md) · 🇸🇦 [ar](../../../ar/docs/frameworks/PLUGIN_SDK.md) · 🇦🇿 [az](../../../az/docs/frameworks/PLUGIN_SDK.md) · 🇧🇬 [bg](../../../bg/docs/frameworks/PLUGIN_SDK.md) · 🇧🇩 [bn](../../../bn/docs/frameworks/PLUGIN_SDK.md) · 🇧🇦 [bs](../../../bs/docs/frameworks/PLUGIN_SDK.md) · 🇨🇿 [cs](../../../cs/docs/frameworks/PLUGIN_SDK.md) · 🇩🇰 [da](../../../da/docs/frameworks/PLUGIN_SDK.md) · 🇩🇪 [de](../../../de/docs/frameworks/PLUGIN_SDK.md) · 🇬🇷 [el](../../../el/docs/frameworks/PLUGIN_SDK.md) · 🇪🇸 [es](../../../es/docs/frameworks/PLUGIN_SDK.md) · 🇪🇪 [et](../../../et/docs/frameworks/PLUGIN_SDK.md) · 🇮🇷 [fa](../../../fa/docs/frameworks/PLUGIN_SDK.md) · 🇫🇮 [fi](../../../fi/docs/frameworks/PLUGIN_SDK.md) · 🇫🇷 [fr](../../../fr/docs/frameworks/PLUGIN_SDK.md) · 🇮🇪 [ga](../../../ga/docs/frameworks/PLUGIN_SDK.md) · 🇮🇳 [gu](../../../gu/docs/frameworks/PLUGIN_SDK.md) · 🇳🇬 [ha](../../../ha/docs/frameworks/PLUGIN_SDK.md) · 🇮🇱 [he](../../../he/docs/frameworks/PLUGIN_SDK.md) · 🇮🇳 [hi](../../../hi/docs/frameworks/PLUGIN_SDK.md) · 🇭🇷 [hr](../../../hr/docs/frameworks/PLUGIN_SDK.md) · 🇭🇺 [hu](../../../hu/docs/frameworks/PLUGIN_SDK.md) · 🇦🇲 [hy](../../../hy/docs/frameworks/PLUGIN_SDK.md) · 🇮🇩 [id](../../../id/docs/frameworks/PLUGIN_SDK.md) · 🇳🇬 [ig](../../../ig/docs/frameworks/PLUGIN_SDK.md) · 🇮🇹 [it](../../../it/docs/frameworks/PLUGIN_SDK.md) · 🇯🇵 [ja](../../../ja/docs/frameworks/PLUGIN_SDK.md) · 🇬🇪 [ka](../../../ka/docs/frameworks/PLUGIN_SDK.md) · 🇰🇭 [km](../../../km/docs/frameworks/PLUGIN_SDK.md) · 🇮🇳 [kn](../../../kn/docs/frameworks/PLUGIN_SDK.md) · 🇰🇷 [ko](../../../ko/docs/frameworks/PLUGIN_SDK.md) · 🇱🇹 [lt](../../../lt/docs/frameworks/PLUGIN_SDK.md) · 🇱🇻 [lv](../../../lv/docs/frameworks/PLUGIN_SDK.md) · 🇮🇳 [ml](../../../ml/docs/frameworks/PLUGIN_SDK.md) · 🇮🇳 [mr](../../../mr/docs/frameworks/PLUGIN_SDK.md) · 🇲🇾 [ms](../../../ms/docs/frameworks/PLUGIN_SDK.md) · 🇲🇹 [mt](../../../mt/docs/frameworks/PLUGIN_SDK.md) · 🇲🇲 [my](../../../my/docs/frameworks/PLUGIN_SDK.md) · 🇳🇵 [ne](../../../ne/docs/frameworks/PLUGIN_SDK.md) · 🇳🇱 [nl](../../../nl/docs/frameworks/PLUGIN_SDK.md) · 🇳🇴 [no](../../../no/docs/frameworks/PLUGIN_SDK.md) · 🇮🇳 [or](../../../or/docs/frameworks/PLUGIN_SDK.md) · 🇮🇳 [pa](../../../pa/docs/frameworks/PLUGIN_SDK.md) · 🇵🇭 [phi](../../../phi/docs/frameworks/PLUGIN_SDK.md) · 🇵🇱 [pl](../../../pl/docs/frameworks/PLUGIN_SDK.md) · 🇵🇹 [pt](../../../pt/docs/frameworks/PLUGIN_SDK.md) · 🇧🇷 [pt-BR](../../../pt-BR/docs/frameworks/PLUGIN_SDK.md) · 🇷🇴 [ro](../../../ro/docs/frameworks/PLUGIN_SDK.md) · 🇷🇺 [ru](../../../ru/docs/frameworks/PLUGIN_SDK.md) · 🇱🇰 [si](../../../si/docs/frameworks/PLUGIN_SDK.md) · 🇸🇰 [sk](../../../sk/docs/frameworks/PLUGIN_SDK.md) · 🇸🇮 [sl](../../../sl/docs/frameworks/PLUGIN_SDK.md) · 🇷🇸 [sr](../../../sr/docs/frameworks/PLUGIN_SDK.md) · 🇸🇪 [sv](../../../sv/docs/frameworks/PLUGIN_SDK.md) · 🇰🇪 [sw](../../../sw/docs/frameworks/PLUGIN_SDK.md) · 🇮🇳 [ta](../../../ta/docs/frameworks/PLUGIN_SDK.md) · 🇮🇳 [te](../../../te/docs/frameworks/PLUGIN_SDK.md) · 🇹🇭 [th](../../../th/docs/frameworks/PLUGIN_SDK.md) · 🇹🇷 [tr](../../../tr/docs/frameworks/PLUGIN_SDK.md) · 🇵🇰 [ur](../../../ur/docs/frameworks/PLUGIN_SDK.md) · 🇺🇿 [uz](../../../uz/docs/frameworks/PLUGIN_SDK.md) · 🇻🇳 [vi](../../../vi/docs/frameworks/PLUGIN_SDK.md) · 🇳🇬 [yo](../../../yo/docs/frameworks/PLUGIN_SDK.md) · 🇨🇳 [zh-CN](../../../zh-CN/docs/frameworks/PLUGIN_SDK.md) · 🇹🇼 [zh-TW](../../../zh-TW/docs/frameworks/PLUGIN_SDK.md)

---

## Швидкий старт

```ts
import { definePlugin } from "omniroute/plugins/sdk";

export default definePlugin({
  name: "my-plugin",
  priority: 50,
  onRequest: async (ctx) => {
    console.log(`Request ${ctx.requestId} for ${ctx.model}`);
  },
  onResponse: async (ctx, response) => {
    console.log(`Response for ${ctx.requestId}`);
    return response;
  },
  onError: async (ctx, error) => {
    console.error(`Error: ${error.message}`);
  },
});
```

## Довідник API

### `definePlugin(def: PluginDefinition): Plugin`

Фабрична функція, яка створює об’єкт Plugin зі значеннями за замовчуванням.

**Параметри:**

- `name` (string, обов’язковий) — Назва плагіна у форматі kebab-case
- `priority` (number, необов’язковий, за замовчуванням: 100) — Менше значення запускається першим
- `enabled` (boolean, необов’язковий, за замовчуванням: true) — Чи має бути ввімкнений під час запуску?
- `onRequest` (function, необов’язковий) — Виконується перед обробником чату
- `onResponse` (function, необов’язковий) — Виконується після обробника чату
- `onError` (function, необов’язковий) — Виконується в разі помилки обробника

### `blockRequest(response?): BlockingHookResult`

Блокує запит і, за потреби, повертає власну відповідь.

```ts
onRequest: (ctx) => {
  if (!ctx.headers["authorization"]) {
    return blockRequest({ error: "Unauthorized", status: 401 });
  }
};
```

### `modifyBody(body): PluginResult`

Змінює тіло запиту до того, як воно надійде до провайдера.

```ts
onRequest: (ctx) => {
  return modifyBody({ ...ctx.body, temperature: 0.7 });
};
```

### `addMetadata(metadata): PluginResult`

Додає метадані до контексту запиту.

```ts
onRequest: (ctx) => {
  return addMetadata({ source: "my-plugin", version: "1.0.0" });
};
```

## Контекст плагіна (`PluginContext`)

| Поле         | Тип                       | опис                                 |
| ------------ | ------------------------- | ------------------------------------ |
| `requestId`  | `string`                  | Унікальний ідентифікатор запиту      |
| `model`      | `string`                  | Запитана назва моделі                |
| `provider`   | `string`                  | Цільовий провайдер ID                |
| `body`       | `Record<string, unknown>` | Тіло запиту                          |
| `headers`    | `Record<string, string>`  | Заголовки запитів (див. примітку)    |
| `metadata`   | `Record<string, unknown>` | Змінні метадані                      |
| `timestamp`  | `number`                  | Мітка часу запиту                    |
| `apiKeyInfo` | `object` (необов'язково)  | ключові метадані API (див. примітку) |

Контекст ніколи не містить облікові дані клієнта: заголовки `authorization`, `x-api-key`, `proxy-authorization` і `cookie` видаляються (будь-який регістр), а `apiKeyInfo` зберігає метадані ключа (такі як `id`, `name` і `scopes`), але не значення ключа чи його відбиток (`redactPluginContext()` в `src/lib/plugins/hooks.ts`). Це стосується `onRequest`, `onResponse` і `onError`.

## Маніфест (`plugin.json`)

```json
{
  "name": "my-plugin",
  "version": "1.0.0",
  "description": "A sample plugin",
  "author": "your-name",
  "main": "index.js",
  "hooks": {
    "onRequest": { "enabled": true, "priority": 50 },
    "onResponse": true,
    "onError": false
  },
  "requires": {
    "permissions": ["network", "file-read"]
  },
  "enabledByDefault": false,
  "configSchema": {
    "apiKey": {
      "type": "string",
      "description": "API key for external service"
    },
    "maxRetries": { "type": "number", "min": 1, "max": 10, "default": 3 },
    "debug": { "type": "boolean", "default": false },
    "mode": { "type": "string", "enum": ["fast", "slow"], "default": "fast" }
  }
}
```

### Пріоритет хуків

Хуки можна налаштувати з пріоритетом (менше значення = запускається першим):

```json
{
  "hooks": {
    "onRequest": { "enabled": true, "priority": 10 },
    "onResponse": { "enabled": true, "priority": 100 }
  }
}
```

Або як прості логічні значення (пріоритет за замовчуванням — 100):

```json
{
  "hooks": {
    "onRequest": true,
    "onResponse": true
  }
}
```

## Система дозволів

Плагіни є** не пісочниця** . Кожен активний плагін працює як окремий, звичайний дочірній процес Node.js (`loadPlugin()` у `src/lib/plugins/loader.ts`) під тим самим користувачем операційної системи, що й OmniRoute, без контексту VM та прапорів дозволу Node.js. Код плагіна може використовувати `node:fs`, `node:child_process`, `fetch` та будь-який інший Node.js API: він може читати та писати будь-який файл, доступний користувачу OmniRoute (включно з каталогом даних), запускати програми та підключатися до мережі.

`requires.permissions` маніфесту приймає `network`, `file-read`, `file-write`, `env` та `exec`, але сьогодні лише `env` має ефект під час виконання:

| Дозвіл                                       | Ефект сьогодні                                                                                                                                                                                                               |
| -------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `env`                                        | Процес плагіна також отримує `PORT`, `HOSTNAME`, `TZ` і `TMPDIR`. Без нього він отримує лише `PATH`, `HOME`, `USER`, `LANG`, `LC_ALL`, `NODE_ENV`, `PLUGIN_ENTRY` і `PLUGIN_NAME` (плюс `SystemRoot` і `windir` на Windows). |
| `network`, `file-read`, `file-write`, `exec` | Жодного. Це лише оголошення: нічого не блокується, якщо вони відсутні.                                                                                                                                                       |

Встановлення плагіна схоже на встановлення будь-якої іншої програми на хості. Встановлюйте лише плагіни, джерелу яких ви довіряєте.

## Схема конфігурації

Визначте параметри, доступні для налаштування, у `configSchema`:

```json
{
  "configSchema": {
    "apiKey": { "type": "string", "description": "Ключ зовнішнього API" },
    "maxRetries": { "type": "number", "min": 1, "max": 10, "default": 3 },
    "debug": { "type": "boolean", "default": false },
    "mode": { "type": "string", "enum": ["fast", "slow"], "default": "fast" }
  }
}
```

Типи полів: `string`, `number`, `boolean`, `select`

Параметри полів: `default`, `min`, `max`, `enum`, `description`

Значення конфігурації зберігаються в базі даних і доступні на сторінці конфігурації панелі керування.

## Вбудовані події

| Подія             | Коли                                  | Корисне навантаження          |
| ----------------- | ------------------------------------- | ----------------------------- |
| `onRequest`       | Перед обробником чату                 | Контекст запиту               |
| `onResponse`      | Після обробника чату                  | Дані відповіді                |
| `onError`         | У разі помилки обробника              | Об’єкт помилки                |
| `onModelSelect`   | Модель вибрано для маршрутизації      | Інформація про модель         |
| `onComboResolve`  | Комбіновану маршрутизацію визначено   | Цілі комбінації               |
| `onRateLimit`     | Досягнуто обмеження частоти запитів   | Інформація про обмеження      |
| `onQuotaExhaust`  | Квоту вичерпано                       | Інформація про квоту          |
| `onProviderError` | Постачальник повернув помилку         | Відомості про помилку         |
| `onStreamStart`   | Потік SSE розпочато                   | Інформація про потік          |
| `onStreamEnd`     | Потік SSE завершено                   | Статистика потоку             |
| `onInstall`       | Плагін установлено                    | `{ name, version, manifest }` |
| `onActivate`      | Плагін активовано                     | `{ name, version, manifest }` |
| `onDeactivate`    | Плагін деактивовано                   | `{ name, version, manifest }` |
| `onUninstall`     | Плагін видалено (до видалення файлів) | `{ name, version, manifest }` |

## Приклади

### Реєстратор запитів

```ts
import { definePlugin } from "omniroute/plugins/sdk";

export default definePlugin({
  name: "request-logger",
  onRequest: async (ctx) => {
    console.log(`[${new Date().toISOString()}] ${ctx.method} ${ctx.model} -> ${ctx.provider}`);
  },
});
```

### Обмежувач частоти запитів

```ts
import { definePlugin, blockRequest } from "omniroute/plugins/sdk";

const requests = new Map<string, number[]>();

export default definePlugin({
  name: "rate-limiter",
  priority: 10,
  onRequest: async (ctx) => {
    const key = ctx.headers["x-api-key"] || "anonymous";
    const now = Date.now();
    const window = 60000; // 1 хвилина
    const maxRequests = 100;

    const timestamps = (requests.get(key) || []).filter((t) => t > now - window);
    timestamps.push(now);
    requests.set(key, timestamps);

    if (timestamps.length > maxRequests) {
      return blockRequest({
        error: "Перевищено обмеження частоти запитів",
        status: 429,
      });
    }
  },
});
```

### Перетворювач відповідей

```ts
import { definePlugin } from "omniroute/plugins/sdk";

export default definePlugin({
  name: "response-transformer",
  onResponse: async (ctx, response) => {
    if (response.choices) {
      response.choices = response.choices.map((c: any) => ({
        ...c,
        message: { ...c.message, content: c.message.content.trim() },
      }));
    }
    return response;
  },
});
```
