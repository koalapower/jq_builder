# jq_builder

Веб-конструктор jq-выражений для использования в плейбуках **OSMP**.

**Онлайн:** https://koalapower.github.io/jq_builder/

---

## 🇷🇺 Русский

**jq Builder** позволяет собирать jq-выражения с помощью визуального конструктора вместо написания их вручную.

Поддерживаются:

* области действия **Алерт** и **Инцидент**;
* контексты **Триггер** и **Действие**;
* источники:

  * Инцидент;
  * Алерт;
  * Наблюдаемые объекты;
  * Активы;
  * Правила;
  * События (корреляционные и базовые);
* логические условия `AND` / `OR`;
* различные типы полей и соответствующие операторы;
* пользовательские jq-выражения;
* экспорт и загрузка реестра полей в JSON;
* светлая и тёмная темы;
* русский и английский интерфейс.

Встроенный список полей содержит наиболее востребованные поля модели данных и **не является полным**.

Если нужного поля нет, его можно временно добавить через загрузку собственного JSON-реестра. Если поле часто используется, можно предложить добавить его в стандартный набор — создав [Issue](https://github.com/koalapower/jq_builder/issues) в репозитории.

### Ссылки

* [Онлайн-версия](https://koalapower.github.io/jq_builder/)
* [Issues](https://github.com/koalapower/jq_builder/issues)

---

## 🇬🇧 English

A web-based **jq expression builder** for use with **OSMP playbooks**.

**Online:** https://koalapower.github.io/jq_builder/

### Features

Supports:

* **Alert** and **Incident** scopes;
* **Trigger** and **Action** contexts;
* data sources:

  * Incident;
  * Alert;
  * Observables;
  * Assets;
  * Rules;
  * Events (correlation and base events);
* `AND` / `OR` logical conditions;
* different field types and operators;
* custom jq expressions;
* JSON field registry import/export;
* light and dark themes;
* Russian and English UI.

The built-in field registry contains the most commonly used fields and **does not represent the complete data model**.

If a required field is missing, it can temporarily be added using a custom JSON registry. If you think a field should be included in the default registry, please open an [Issue](https://github.com/koalapower/jq_builder/issues).

### Links

* [Online version](https://koalapower.github.io/jq_builder/)
* [Issues](https://github.com/koalapower/jq_builder/issues)
