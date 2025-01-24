# LZW-Huffman Compressor with 2D Parity Check

This Python script implements two compression algorithms (LZW and Huffman) with support for error detection using 2D parity checks. It supports compression and decompression of text or binary files (e.g., .jpg, .png) and includes a unit test suite for verifying functionality.
#

Features:
- LZW Compression/Decompression: Efficient encoding of repetitive sequences.
- Huffman Compression/Decompression: Optimal coding based on symbol frequency.
- 2D Parity Check: Adds error detection by calculating parity bits for compressed data.
- Support for Text and Binary Files: Handles any type of input file (e.g., .txt, .jpg, .png, etc.).
- Code Table for Huffman Decompression: Saves and reuses the Huffman code table for decoding.
- Unit Tests: Includes a suite of tests to validate the implementation.
