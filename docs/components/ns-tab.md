# ns-tab

## Introduction

> The singular tab that dictates what the area is about

The tab is the button that can be clicked to change the content in the `ns-tabs`. It shows the user what content there is with a heading and an optional icon.

## Usage

To see examples visit [Storybook](https://nucleus.bgdigital.xyz/demo/index.html?path=/story/ns-tab--tab)

```html
<ns-tab>Electricity</ns-tab>
```

## Component Relationship

- Does it live in a panel? (no)
- Does it live inside other components?
  - ns-tabs
- Atomic type: (atom)

## Specification
| **Name**| selected |
| ----------- | ------------------------------- |
| **Description** | The state of the tab |
| **Type**        | Boolean |
| **Default**     | false |
| **Options**     | true, false |

| **Name**| icon |
| ----------- | ------------------------------- |
| **Description** | Optional decoration for the text |
| **Type**        | String |
| **Default**     | '' |
| **Options**     | Please see the documentation for ns-icon |

| **Name**| Anonymous slot |
| ----------- | ------------------------------- |
| **Description** | The heading text |
| **Type**        | TextNode |
| **Default**     | '' |
| **Options**     | n/a |

## Best practises

| ✅ Do's | 💔 Don'ts |
| ------ | -------- |
| Always add heading text | Add an icon to one tab and not to the other tabs |
|        | Add more than 2 words to the heading |
|        | Add different types of icons (solid, outline, functional) |

### Considerations of best practises

- Only use inside `ns-tabs` as a slot of `tab`

## Feedback

- Do you have insights or concerns to share? You can raise an issue via [Github bugs](https://github.com/ConnectedHomes/nucleus/issues/new?assignees=&labels=Bug&template=a--bug-report.md&title=[bug]%20[ns-tab]).
- See all the issues already raised via [Github issues](https://github.com/connectedHomes/nucleus/issues?utf8=%E2%9C%93&q=is%3Aopen+is%3Aissue+label%3ABug+[ns-tab])

💩 🎉 🦄 You can also contact the team on Slack on the `#product-nucleus` channel!

## Related links
- Blog posts
- MDN articles
- Examples of where it is used