# TileLang

TileLang is a powerful language designed for manipulating tiles (matrices) using a variety of operations, including matrix and, matrix or, matrix xor, rotation, flipping, and more. It provides a convenient and expressive way to work with tiles in programming.

## How to Use

To use TileLang, follow the steps below:

1. **Compile the Alex lexer**: Start by compiling the Alex lexer using the following command:
`alex Lexer.x`

2. **Compile the Happy parser**: Next, compile the Happy parser using the command:
`happy Parser.y`

3. **Compile the TileLang program**: Once you have the lexer and parser ready, compile the TileLang program using GHC:
`ghc Tsl.hs`

4. **Run the TileLang program**: After successful compilation, you can run the TileLang program with your own code by executing the following command:
`./Tsl <your_code.tsl>`
Replace `<your_code.tsl>` with the name of your TileLang code file.

5. **A tileviewer(tv) has been provided as a UNIX executable file, paste your generated matrix to a file in the same folder as tv and view your result using the following command:
`./tv <your_result.tl>`

## Requirements

To use TileLang, ensure that you have the following dependencies installed on your system:

- Haskell
- Other required dependencies (specified in the project documentation)

Make sure to have a compatible Haskell compiler and the necessary libraries installed to compile and run TileLang programs.

## Contributors

TileLang is the result of collaborative efforts by the following contributors:

- Shawn Yao (sy1g21@soton.ac.uk)
- Zhaoxu He (zh2u21@soton.ac.uk)
- Chengkang Gu (cg1y21@soton.uk)

Feel free to reach out to the contributors for any questions or contributions related to TileLang.
Sample usage(prN, 0<N<=10) has been provided.
