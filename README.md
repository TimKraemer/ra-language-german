# German Translations for react-admin

German translations for [react-admin](https://github.com/marmelab/react-admin), the frontend framework for building admin applications on top of REST/GraphQL services.

[![react-admin-demo](https://marmelab.com/react-admin/img/react-admin-demo-still.png)](https://vimeo.com/268958716)

## Installation

```sh
npm install --save ra-language-german
```

## Usage

```jsx
import { Admin } from 'react-admin';
import englishMessages from 'ra-language-english';
import polyglotI18nProvider from 'ra-i18n-polyglot';

const messages = {
    'en': englishMessages,
};
const i18nProvider = polyglotI18nProvider(locale => messages[locale]);

<Admin locale="en" i18nProvider={i18nProvider}>
    ...
</Admin>
```

## License

This translation is licensed under the [MIT Licence](LICENSE).
