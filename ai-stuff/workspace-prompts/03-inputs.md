Read the list of selectors from `ai-stuff/01-selectors.json` and list of components from `ai-stuff/02-components.json`

Based on this list, look through `projects/zap/core` or `projects/zap/forms` to consider what input binds are available for each component's selector(s) and what possible values for each. Then summarize how these input binds change the appearance of the overall component and also look through `projects/demo/src/app/components` for more information.

Create separate lists for each component by their selector. For each component, list the following:

1. List each selector and its input
2. List possible values for that input. Flag if a value has a finite possible values or is not bound like a string union type vs string
3. Summarize how that input changes the appearance of that component

Export a json array that lists this information for all component selector and input bind pairing in `ai-stuff/workspace-output/03-inputs.json`

```
{
  component: <COMPONENT_NAME>
  selectors: {
    <COMPONENT_SELECTOR>: {
      <INPUT_BIND_NAME>: {
        value: [<VALUE_1>, <VALUE-2>, ...] or [true, false] for boolean or string or number or unknown or any
        summary: <short summary>
      }
    }
  },
}
```
