# svelte-component-import
Import a Svelte component and set component properties.

This is an extension of an excellent description provided by Ling Talfi outlining how to consume a bundled Svelte component in a non-Svelte web app.

https://github.com/lingtalfi/TheBar/blob/master/discussions/inject-svelte-in-existing-app.md

I've extended the example by adding a css file for the bundle, and adding the ability to update props of the Svelte component from Javascript.

Note the "<svelte:options accessors/>" Svelte compiler option in the component source file. This is required in order to access properties of the component via javascript in the consumer app.
