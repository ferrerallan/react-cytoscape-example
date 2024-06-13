
# React Cytoscape Example

## Description

This repository contains an example of integrating Cytoscape, a graph theory library, with a React application. It demonstrates how to create and manipulate interactive network graphs within a React project.

## Requirements

- Node.js
- Yarn or npm

## Mode of Use

1. Clone the repository:
   ```bash
   git clone https://github.com/ferrerallan/react-cytoscape-example.git
   ```
2. Navigate to the project directory:
   ```bash
   cd react-cytoscape-example
   ```
3. Install dependencies:
   ```bash
   yarn install
   ```
4. Start the application:
   ```bash
   yarn start
   ```

## Use Case

This repository can be used as a reference for developing applications that require interactive graph visualizations. It is particularly useful for:

- Network analysis tools
- Data visualization dashboards
- Interactive educational tools

## Example of Use

### Adding a Node to the Graph

The code snippet below shows how to add a node to the graph:

```javascript
cy.add({
  group: 'nodes',
  data: { id: 'n1', label: 'Node 1' },
  position: { x: 100, y: 100 }
});
```

## License

This project is licensed under the MIT License.
