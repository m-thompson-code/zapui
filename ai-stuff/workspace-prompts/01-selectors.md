Gather a information of all components that are listed in `projects/zap/core` and `projects/zap/forms`.

For each component I want:

1. Component name
2. Component selector(s)
3. relative path to component definition in `projects/zap/core` or `projects/zap/forms`
4. relative path to its demo component in `projects/demo/src/app/components` if it exists
5. Short summary of component

Export a markdown that lists this information in `ai-stuff/workspace-output/01-selectors.json`

I want the following json array with the following schema:

```
{
  selector: <COMPONENT_SELECTOR>,
  path: <projects/zap/core or projects/zap/forms based path to implementation>,
  demo: <projects/demo/src/app/components path if it exists, if not, null>,
  summary: <short summary>
}
```
