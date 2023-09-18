# @bassyu/layout-component

## Example

### Container

```tsx
import { Container } from '@bassyu/layout-component';

const App = () => (
  <Container minWidth={600} maxWidth={960}>
    <div>Content</div>
  </Container>
);
```

### Grid

```tsx
import { Grid } from '@bassyu/layout-component';

const App = () => (
  <Grid rows={3} columns={3} gap={10} minWidth={600} maxWidth={960}>
    <div>Item 1</div>
    <div>Item 2</div>
    <div>Item 3</div>
  </Grid>
);
```

### Flex

```tsx
import { Flex } from '@bassyu/layout-component';

const App = () => (
  <Flex direction="row" justify="center" align="center" gap={5} minWidth={600} maxWidth={960}>
    <div>Item 1</div>
    <div>Item 2</div>
    <div>Item 3</div>
  </Flex>;
);
```
