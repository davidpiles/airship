Table component explanation here.

```react
<Table>
  <Table.Header>
    <Table.Row>
      <Table.HeaderCell>Header</Table.HeaderCell>
      <Table.HeaderCell>Header</Table.HeaderCell>
      <Table.HeaderCell>Header</Table.HeaderCell>
    </Table.Row>
  </Table.Header>

  <Table.Body>
    <Table.Row>
      <Table.Cell>Cell</Table.Cell>
      <Table.Cell>Cell</Table.Cell>
      <Table.Cell>Cell</Table.Cell>
    </Table.Row>
    <Table.Row>
      <Table.Cell>Cell</Table.Cell>
      <Table.Cell>Cell</Table.Cell>
      <Table.Cell>Cell</Table.Cell>
    </Table.Row>
    <Table.Row>
      <Table.Cell>Cell</Table.Cell>
      <Table.Cell>Cell</Table.Cell>
      <Table.Cell>Cell</Table.Cell>
    </Table.Row>
  </Table.Body>
</Table>
```

Cells admit `colSpan` and `rowSpan` properties as well in order to allow cells to span width or height:

```react
<Table lined>
  <Table.Header>
    <Table.Row>
      <Table.HeaderCell colSpan={3}>Header</Table.HeaderCell>
    </Table.Row>
  </Table.Header>

  <Table.Body>
    <Table.Row>
      <Table.Cell rowSpan={2}>Cell</Table.Cell>
      <Table.Cell>Cell</Table.Cell>
      <Table.Cell>Cell</Table.Cell>
    </Table.Row>
    <Table.Row>
      <Table.Cell>Cell</Table.Cell>
      <Table.Cell>Cell</Table.Cell>
    </Table.Row>
    <Table.Row>
      <Table.Cell>Cell</Table.Cell>
      <Table.Cell>Cell</Table.Cell>
      <Table.Cell>Cell</Table.Cell>
    </Table.Row>
  </Table.Body>
</Table>
```

### Props

#### **lined** (boolean)

Using this property, you can tweak the theme adding border to the cells.

```react
<Table lined>
  <Table.Header>
    <Table.Row>
      <Table.HeaderCell>Header</Table.HeaderCell>
      <Table.HeaderCell>Header</Table.HeaderCell>
      <Table.HeaderCell>Header</Table.HeaderCell>
    </Table.Row>
  </Table.Header>

  <Table.Body>
    <Table.Row>
      <Table.Cell>Cell</Table.Cell>
      <Table.Cell>Cell</Table.Cell>
      <Table.Cell>Cell</Table.Cell>
    </Table.Row>
    <Table.Row>
      <Table.Cell>Cell</Table.Cell>
      <Table.Cell>Cell</Table.Cell>
      <Table.Cell>Cell</Table.Cell>
    </Table.Row>
    <Table.Row>
      <Table.Cell>Cell</Table.Cell>
      <Table.Cell>Cell</Table.Cell>
      <Table.Cell>Cell</Table.Cell>
    </Table.Row>
  </Table.Body>
</Table>
```
