# Grid Component
This project demonstrates a 2×4 grid structure built with React.js, where the grid is dynamically generated based on the number of rows (numRows) and columns (numCols) passed as props.

# DOM Structure
The grid is represented with the following HTML structure:

html

<div class="grid">
  <div class="row">
    <div class="cell"></div>
    <div class="cell"></div>
    <div class="cell"></div>
    <div class="cell"></div>
  </div>
  <div class="row">
    <div class="cell"></div>
    <div class="cell"></div>
    <div class="cell"></div>
    <div class="cell"></div>
  </div>
</div>

# Implementation Details
The grid is dynamically created using the range function from utils.js.
The rows and columns are mapped based on the props provided (numRows and numCols).
The component allows for variable grid sizes, not just a 2×4 structure.
Acceptance Criteria
The following criteria were met:

# The Grid component accepts:

A numRows prop for the number of rows.
A numCols prop for the number of columns.
The generated grid structure follows these rules:

It contains X <div> elements with a class of row, where X equals numRows.
Each row contains Y <div> elements with a class of cell, where Y equals numCols.
The implementation ensures:

The use of the provided range function for generating rows and columns.
There are no key-related warnings in the console during rendering.
