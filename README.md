# sublime snippets for react,redux and react-router

#### Documentation of available snippets (JSX):

```
    cdm→  componentDidMount: fn() { ... }

   cdup→  componentDidUpdate: fn(pp, ps) { ... }

     cs→  import cx from 'classnames';

    cwm→  componentWillMount: fn() { ... }

    cwr→  componentWillReceiveProps: fn(np) { ... }

    cwu→  componentWillUpdate: fn(np, ns) { ... }

   cwun→  componentWillUnmount: fn() { ... }

     cx→  cx({ ... })

    fdn→  React.findDOMNode(...)

    fup→  forceUpdate(...)

    gdp→  static defaultProps = { ... } 

    gis→  getInitialState: fn() { return {...} } 

    ism→  isMounted()

  props→  this.props.

     pt→  propTypes { ... }

    rcc→  component skeleton

    rcc→  Stateless Functional Component

   refs→  this.refs.

    ren→  render: fn() { return ... }

    rpc→  pure render component skeleton

    rrc→  redux component skeleton

    scu→  shouldComponentUpdate: fn(np, ns) { ... }

    sst→  this.setState({ ... })

  state→  this.state.

```

## Contributing

### Rebuilding the docs

After making changes to snippet files, run `npm install && npm run build-docs` to automatically generate this document from source. **Do not** make changes to README.md directly.

