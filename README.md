# Text File Compression with Huffman Encoding

This project implements a text file compression and decompression system using the Huffman Algorithm. The system is designed to achieve lossless data compression for text (.txt) files.
# Live Demo:
https://byte-squeeze.vercel.app/
## Overview

The Huffman Algorithm assigns variable-length codes to different characters based on their frequency of occurrence in the input text. This results in shorter codes for more frequently used characters and longer codes for less frequent ones, optimizing the compression ratio.

## How it Works

1. **Compression:** The algorithm builds a Huffman tree bottom-up, starting with the characters in the text and their frequencies. It then generates a code table based on the tree structure, where shorter codes represent common characters.
   
2. **Decompression:** Using the generated code table, the algorithm reverses the compression process to reconstruct the original text from the compressed data.

## Key Features

- Lossless compression and decompression of text (.txt) files.
- Variable-length code assignment for characters.
- Improved compression ratio with larger file sizes.
- Responsive web interface using HTML and CSS.
- Interactive elements powered by JavaScript.

## Usage

1. Upload a text file for compression.
2. Download the compressed file.
3. Use the decompression feature to restore the original text.

