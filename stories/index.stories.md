```js script
import { html } from '@open-wc/demoing-storybook';
import '../src/TextboxComponent/textbox-component.js';
import '../src/ButtonComponent/button-component.js';
import '../src/ClockTimerComponent/clock-timer-component.js';
import '../src/MainApplication/main-application.js';

export default {
  title: 'TimerApplication',
  component: 'main-application',
  options: { selectedPanel: "storybookjs/knobs/panel" },
};
```

# TimerApplication

### Installation

```bash
yarn add timer-application
```

```js
import 'timer-application/textbox-component.js';
import 'timer-application/button-component.js';
import 'timer-application/clock-timer-component.js';
import 'timer-application/main-application.js';
```

```js preview-story

export const Textbox = () => html`
  <textbox-component></textbox-component>
`;

export const Button = () => html`
  <button-component></button-component>
`;

export const ClockTimer = () => html`
  <clock-timer-component></clock-timer-component>
`;

export const MainApp = () => html`
  <main-application></main-application>
`;
```
