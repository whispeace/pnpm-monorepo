# pnpm-monorepo

Пример monorepo с использованием pnpm.

## Примеры

- `apps/web` - Web-приложение на vite + typescript
- `apps/web-vue` - Web-приложение на vite + vue + typescript
- `packages/tsconfig` - Общие конфигурации typescript (tsconfig) для использования в приложениях и пакетах
- `packages/utils` - Общие utils для использования в других пакетах и приложениях

## TODO

- [x] Добавить приложение используя __Vue 3__ + __Vite__ + __TypeScript__
- [x] Добавить поддержку __TailwindCSS__ с конфигурацией в `packages/tailwind`
- [ ] Добавить библиотеку компонентов для Vue приложений
- [ ] Добавить в `packages` библиотеку с __переиспользуемыми блоками__ и __composables__ для __Vue__ приложений. 
- [ ] Настроить CI