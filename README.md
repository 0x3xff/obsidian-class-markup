# obsidian class markup
Add custom class to almost any markdown element for advanced styling

## Usage

Headers:

```markdown
# Header ::: class
# Header with multiple classes ::: class1 : class2 : class3
```

Lists:

```markdown
::: list-class
  - List Item
  - List Item ::: item-class
:::
```

Callouts:

```markdown
> [!callout] Callout ::: class
> ...
```

Codeblocks:

Inline
```markdown
`codeblock` ::: class
```

Multyline
~~~markdown
```python ::: class
  ...
```
~~~

Table:

```markdown
::: class

| key | value |
| ---- | ---- |
| ABC  | DEF  |

:::
```

```markdown
Lorem Impsum \::: This one is a plain text
```
