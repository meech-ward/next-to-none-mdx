## Next to None

[NextToNone.lol](https://NextToNone.lol)

### Blocks

#### YouTube

```mdx
<YouTube videoId="PbkwqVZsUgs" startTime={230} />
```

#### Example Block

```mdx
<ExampleBlock>
  <ExampleBlock.Action>
    **Rendered as JS:**
  </ExampleBlock.Action>
  <ExampleBlock.Implementation>
    ```js
    <p>{6 + 9}</p>
    ```
  </ExampleBlock.Implementation>
</ExampleBlock>
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