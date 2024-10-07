# Features

Hamming Code
- **Code Structure**: Codewords are designed with a total of n bits, where k bits represent the data and n-k bits are used for parity.
- **Error Detection and Correction**: The decoder is capable of detecting and correcting single-bit errors and detecting two-bit errors, ensuring robust error correction for reliable communication.
- **Efficiency**: Ideal for applications requiring lightweight error correction with minimal overhead.

Hadamard Code
- **Code Structure**: Codewords are composed of n bits, consisting of k message bits and n-k parity bits.
- **Error Correction Capacity**: The decoder can correct up to (n−1)/2 bits, offering a strong error correction capability that grows with the size of the codeword.
- **High Fault Tolerance**: Suitable for scenarios with high noise where multiple-bit errors are expected.

Reed-Solomon Code
- **Code Structure**: Encodes k data symbols into n-symbol codewords, with n-k symbols serving as parity for error correction.
- **Error Correction Capacity**: Capable of correcting up to (n−k)/2 symbol errors, making it highly effective in correcting burst errors across large blocks of data.
- **Versatility**: Widely used in applications like digital television, CDs, DVDs, and QR codes, where data integrity is critical.
