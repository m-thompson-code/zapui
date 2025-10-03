For this prompt a component is a collection or one or more selectors.

Read information from `ai-stuff/01-selectors.json` and reference `projects/zap/core`, `projects/zap/forms`, and `projects/demo/src/app/components` to understand which selectors are expected to be used together to form a single component. For each component, come up with a name based on its folder structure and the common parts of all the selectors. Also include a summary of this component.

Export `ai-stuff/workspace-output/02-components.json` with the following schema:

```
{
  component: <COMPONENT_NAME>,
  selectors: [<COMPONENT_SELECTOR_1>, <COMPONENT_SELECTOR_2>, ...],
  summary: <short summary>
}
```
