## Next to None

[NextToNone.lol](https://NextToNone.lol)

### Blocks

#### YouTube

```mdx
<YouTube videoId="PbkwqVZsUgs" startTime={230} />
```

#### Example Block

```mdx
<SideBySide ratio="3:5">
<ExampleCard>
Return a single root element, div or empty tag `<>`
</ExampleCard>
  \`\`\`some-component.jsx
    // focus(1:2) 
  return (
    <div>
      <h1 className="header">Hello</h1>
      <h2>World</h2>
      <img className="image" src="https://picsum.photos/200" alt="random"></img>
    </div>
  )
  \`\`\`
</SideBySide>
```

#### Instruction Block 

```mdx
<InstructionBlock>
  <InstructionBlock.Action step={1}>
    Add this code to your thing:
  </InstructionBlock.Action>
  <InstructionBlock.Implementation>

  ```App.js
  return (
      <div className="App">
        <h1 className="heading">Hello</h1>
        <h2>World</h2>
        <h3>{new Date().toString()}</h3>
      </div>
  )
  ```
  </InstructionBlock.Implementation>
</InstructionBlock>
```

#### Tabs 

```
<Tabs>
  <Tab name="npx">
    ```sh
    npx create-next-app@latest
    ```
  </Tab>
  <Tab name="yarn">
    ```sh
    yarn create next-app
    ```
  </Tab>
  <Tab name="pnpm">
    ```sh
    pnpm create next-app
    ```
  </Tab>
  <Tab name="bunx">
    ```sh
    bunx create-next-app
    ```
  </Tab>
</Tabs>
```

## Card 

```
<Card>
</Card>
```

## File Tree 

```
<Card>
<FileTree focus=[{
  depth: number
  item: number
}]>
  - src 
   - app
    - page.tsx
</FileTree>
</Card>
```