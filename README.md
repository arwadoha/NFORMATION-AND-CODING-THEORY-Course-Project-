# ENEE5304: Information and Coding Theory - Source Coding Project

## Project Overview

This project demonstrates the implementation of Huffman coding for lossless data compression. The primary goal is to simulate the Huffman algorithm, calculate compression ratios, and compare the performance with standard ASCII encoding. The project uses text data to evaluate how Huffman coding optimizes space by assigning shorter binary codes to more frequent symbols and longer codes to less frequent symbols.


## Introduction

Huffman coding is a well-known algorithm used for lossless data compression. It assigns variable-length binary codes to symbols based on their frequency of occurrence in the input data. This project applies Huffman coding to a sample dataset (literature text) to demonstrate the compression efficiency and compare it with standard ASCII encoding.


## Project Objectives

- Implement the Huffman coding algorithm in Java.
- Calculate the compression rate when compared to ASCII encoding.
- Compute and analyze the entropy of the source data.
- Evaluate the efficiency of Huffman coding in terms of compression and time complexity.

## Methodology

1. **Data Collection**: The input data consists of a sample text (e.g., a story or a dataset with character frequencies).
2. **Huffman Algorithm Implementation**: Implement the algorithm using Java. The program will:
   - Read the input text.
   - Build a frequency table.
   - Generate Huffman codes for each symbol.
   - Calculate the total bits required for both Huffman and ASCII encoding.
3. **Compression Calculation**: Calculate and compare the compression ratio.
4. **Entropy Calculation**: Compute the entropy of the source.

## Results

- **Compression Rate**: Achieved a compression rate of **52.68%** compared to the standard ASCII encoding.
- **Efficiency**: The Huffman coding algorithm showed efficient use of binary codes with shorter codes assigned to more frequent symbols.
- **Entropy vs Code Length**: The average code length achieved was close to the theoretical entropy of the source.

## Conclusion

Huffman coding provides a significant improvement in data compression, especially for datasets with skewed symbol distributions. This project demonstrates its practical application and efficiency in reducing data size without any loss of information.

## References

1. **Huffman, D. A.** (1952). "A Method for the Construction of Minimum Redundancy Codes." *Proceedings of the IRE*.
2. **Cover, T. M., & Thomas, J. A.** (2006). *Elements of Information Theory* (2nd ed.). Wiley-Interscience.

