DO NOT REFERENCE ANY FILES IN THIS CODEBASE. DO NOT REFERENCE ANY GENERATED FILES FROM THIS PROMPT. DO NOT USE ANY CONTEXT FROM THE CODEBASE.

This is a link to figma page: https://www.figma.com/design/sYXUmoFZrdeOvfOTZofv18/Zap-UI-Kit--Bitovi-?node-id=1-3&m=dev

Using only the Figma MCP, find this page's Node. Iterate over the children of this node to find any nodes with property `type` and value `COMPONENT_SET`. Repeat this process for every node's children until there are no child nodes left.


Do not analyze the actual Figma Page for this task.
Generate a JSON array of all the nodes found with property `type` and value `COMPONENT_SET`.

I only want the following properties for each node:

1. id
2. name

The generated JSON array should have the following schema:

```
{
  id: string;
  name: string;
}
```

Export this JSON array into a file: `ai-stuff/figma-outputs/01-figma.json`
