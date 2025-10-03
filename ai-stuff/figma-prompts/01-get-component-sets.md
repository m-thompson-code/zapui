For this prompt:
- DO NOT reference any files in the code base.
- DO NOT reference any existing files we are generating.


Using the Figma API
Go through the figma nodes for this Figma page, Find every Figma node that has property type = COMPONENT_SET 
https://www.figma.com/design/sYXUmoFZrdeOvfOTZofv18/Zap-UI-Kit--Bitovi-?node-id=1-3&m=dev

For each Figma node I want the following properties provided by the Figma API:

1. name
2. Id

Export a JSON array that lists this information in `ai-stuff/figma-outputs/01-figma.json`

I want the following json array with the following schema:

```
{
  name: <name>,
  id: <id>,
}
```
