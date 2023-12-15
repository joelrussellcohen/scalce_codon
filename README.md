# scalce_codon
A reimplementation of the SCALCE algorithm in Codon

# Usage

## Compression:
`codon run -plugin seq scalce_compress <input_file> <output_file>`

### Example
`codon run -plugin seq scalce_compress file.fastq compressed`

## Decompression:

### Example
`codon run -plugin seq scalce_decompress compressed file.fastq`
