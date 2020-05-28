# \<timer-application>

This webcomponent follows the [open-wc](https://github.com/open-wc/open-wc) recommendation.

## Installation
```bash
npm i timer-application
```

## Usage
```html
<script type="module">
  import 'timer-application/textbox-component.js';
</script>

<textbox-component></textbox-component>

<script type="module">
  import 'timer-application/button-component.js';
</script>

<button-component></button-component>

<script type="module">
  import 'timer-application/clock-timer-component.js';
</script>

<clock-timer-component></clock-timer-component>

<script type="module">
  import 'timer-application/main-application.js';
</script>

<main-application></main-application>
```

## Linting with ESLint, Prettier, and Types
To scan the project for linting errors, run
```bash
npm run lint
```

You can lint with ESLint and Prettier individually as well
```bash
npm run lint:eslint
```
```bash
npm run lint:prettier
```

To automatically fix many linting errors, run
```bash
npm run format
```

You can format using ESLint and Prettier individually as well
```bash
npm run format:eslint
```
```bash
npm run format:prettier
```

## Testing with Karma
To run the suite of karma tests, run
```bash
npm run test
```

To run the tests in watch mode (for <abbr title="test driven development">TDD</abbr>, for example), run

```bash
npm run test:watch
```

## Demoing with Storybook
To run a local instance of Storybook for your component, run
```bash
npm run storybook
```

To build a production version of Storybook, run
```bash
npm run storybook:build
```