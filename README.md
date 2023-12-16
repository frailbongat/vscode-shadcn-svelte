<p align="center">
 <img align="center" src="https://raw.githubusercontent.com/selemondev/vscode-shadcn-svelte/master/src/images/icon.png" height="96" />
 <h1 align="center">
  shadcn-svelte
 </h1>
</p>

This VSCode extension enables you to install [shadcn/svelte](https://shadcn-svelte.com) components directly from your IDE ✨.

## Initialize the Shadcn/Svelte CLI

![to initialize CLI open the command palette and search for shadcn/svelte: install cli command](https://raw.githubusercontent.com/selemondev/vscode-shadcn-svelte/master/src/assets/images/init-cli.png)

## Install components

![to initialize CLI open the command palette and search for shadcn/svelte: add new component](https://raw.githubusercontent.com/selemondev/vscode-shadcn-svelte/master/src/assets/images/add-new-component.png)

## Choose a component to install from the list

![choose a component to install from the list](https://raw.githubusercontent.com/selemondev/vscode-shadcn-svelte/master/src/assets/images/add-new-component-preview.png)

## Install multiple components

![install multiple components](https://raw.githubusercontent.com/selemondev/vscode-shadcn-svelte/master/src/assets/images/add-multiple-components.png)

## Choose components to install from the list
![choose components to install from the list](https://raw.githubusercontent.com/selemondev/vscode-shadcn-svelte/master/src/assets/images/add-multiple-components-preview.png)

## Open the Shadcn-Svelte documentation

![open the shadcn-svelte documentation](https://raw.githubusercontent.com/selemondev/vscode-shadcn-svelte/master/src/assets/images/shadcn-svelte-docs.png)

## Navigate to a particular component's documentation page

![navigate to a particular component's documentation page](https://raw.githubusercontent.com/selemondev/vscode-shadcn-svelte/master/src/assets/images/shadcn-svelte-component-docs.png)

## Shadcn/Svelte Snippets

Easily import and use shadcn-svelte components with ease using snippets within VSCode. Just type `cn` or `shadcn` in your svelte file and choose from an array of components to use.

![shadcn-svelte-snippets-example](https://raw.githubusercontent.com/selemondev/vscode-shadcn-svelte/master/src/assets/images/shadcn-svelte-import.png)

### How it works

| Snippet           | Description                            |
| ----------------- | -------------------------------------- |
| `cn-help`         | How to use shadcn/svelte snippets      |
| `cni-[component]` | Adds imports for the component         |
| `cnx-[component]` | Adds the markup for the svelte component|

### How to use?

1. Components

For `Alert` component, type `cni-alert` to add imports in your svelte file, and to use the component, use `cnx-alert`.

> Similarly, for any other component, use `cni-[component]` to add imports and `cnx-[component]` to use.

```tsx
// cni-alert
import * as Alert from "$lib/components/ui/alert"

// cnx-alert
<Alert.Root>
  <Alert.Title>Heads up!</Alert.Title>
  <Alert.Description>
    You can add components to your app using the cli.
  </Alert.Description>
</Alert.Root>
```

### How to contribute?

Use this link - [Snippet Generation](https://snippet-generator.app/?description=https%3A%2F%2Fwww.shadcn-svelte.com%2Fdocs%2Fcomponents&tabtrigger=shadcn-&snippet=&mode=vscode) to generate snippets and add/update them to the `snippets` folder that is located in the `src` accordingly.


### Credits 

All credits go to the creators of these amazing projects:

- [Shadcn UI](https://ui.shadcn.com) for creating this beautiful project.
- [Shadcn Svelte](https://shadcn-svelte.com) for creating the Svelte port of Shadcn UI.
- [Bits UI](https://www.bits-ui.com/docs/introduction) for doing all the hard work to make sure components are accessible.