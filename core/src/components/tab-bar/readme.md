# ion-tab-bar

Tab bar is the UI component that implements the array of button of `ion-tabs`. It's provided by default when `ion-tabs` is used, though, this "implicit" tab bar can not be customized.

In order to have a custom tab bar, it should be provided in user's markup as direct children of `ion-tabs`:

```html
<style>
  ion-tab-bar {
    font-size: 20px;
  }
</style>

<ion-tabs>
  <!-- User tabs  -->
  <ion-tab></ion-tab>
  <ion-tab></ion-tab>

  <!-- User provided ion-tab-bar that can be customized -->
  <ion-tab-bar slot="bottom" color="dark" layout="icon-only">
</ion-tabs>
```


<!-- Auto Generated Below -->


## Properties

| Property      | Attribute      | Description                                                                                                                                                                                                                                                            | Type                                                                                       | Default      |
| ------------- | -------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------ | ------------ |
| `color`       | `color`        | The color to use from your application's color palette. Default options are: `"primary"`, `"secondary"`, `"tertiary"`, `"success"`, `"warning"`, `"danger"`, `"light"`, `"medium"`, and `"dark"`. For more information on colors, see [theming](/docs/theming/basics). | `string \| undefined`                                                                      | `undefined`  |
| `layout`      | `layout`       | Set the layout of the text and icon in the tab bar.                                                                                                                                                                                                                    | `"icon-bottom" \| "icon-end" \| "icon-hide" \| "icon-start" \| "icon-top" \| "label-hide"` | `'icon-top'` |
| `mode`        | `mode`         | The mode determines which platform styles to use.                                                                                                                                                                                                                      | `"ios" \| "md"`                                                                            | `undefined`  |
| `selectedTab` | `selected-tab` | The selected tab component                                                                                                                                                                                                                                             | `string \| undefined`                                                                      | `undefined`  |
| `translucent` | `translucent`  | If `true`, the tab bar will be translucent.                                                                                                                                                                                                                            | `boolean`                                                                                  | `false`      |


## CSS Custom Properties

| Name           | Description               |
| -------------- | ------------------------- |
| `--background` | Background of the tab bar |
| `--border`     | Border of the tab bar     |
| `--color`      | Color of the tab bar      |


----------------------------------------------

*Built with [StencilJS](https://stenciljs.com/)*
