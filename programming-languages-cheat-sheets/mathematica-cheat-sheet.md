This file collects syntax, semantics, and common usages of Mathematica (mma, for short).

# List Manipulation

## Constructing Lists

## Elements of Lists

## Rearranging & Restructuring Lists

- Partition

  `In := Partition[{1,2,3,4,5,6},2]` => `Out:= {{1,2}, {3,4}, {5,6}}`
  
## Applying Functions to Lists

## Predicates on Lists

## Math & Counting Operations

## Displaying & Visualizing Lists

# Files

## Importing Data from File

- numerical data file: one per line

  `dataList = Flatten[Import[filePath, "Data"]];`
  
  - `filePath`: The file will be searched under `$Path`. Note that in Linux, `/home/$USER/` is in `$Path`.
  - `Flatten`: `Import` returns a `n * 1` matrix. We use `Flatten` to obtain a list of data.