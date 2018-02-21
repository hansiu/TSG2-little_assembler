# TSG2-little_assembler
This was a university project for a class focused on NGS data analysis.

The task was to create a simple assembler that returns contigs. We were allowed to make following simplifying assumptions about data:
- reads are from 1 strand of 1 chromosome
- reads length is 80
- average coverage of the reference sequence is 5
- reads have 1%, 2% or 5% of errors (3 sets)

We were allowed to use the code shown/used in classes, based on Ben Langmead codes.

Mine assembler is based on an idea to have fun with mixing a bit of OLC and DBG approach. The simplest explanation: here I use a greedy OLC approach with DBG-like error correction.


## Usage

To use the script simply run in the console:

`assembly input.fasta output.fasta`

with input and output filenames of your choosing.
