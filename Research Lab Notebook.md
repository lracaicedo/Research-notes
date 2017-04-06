## Research Lab Notebook

1. DNA Extraction and PCR amplification: by Lab protocols

2. Sending PCR to sequencing facility: 

3. Assembly of sequences received:

4. - Make: names!.txt file on a text editor, including names (with locality and barcode) to match with sequences (ab1files).
   - Ingi: uses Phred & Phrap for assembly

5. Proofreading of sequences: on Mesquite

   Guide here: http://mesquiteproject.org/packages/chromaseq/manual/quality.html

   - Organize sequences by quality: top= good quality (light green, light yellow), bottom= low quality (blue or purple). Using Matrix-> Move selected taxa to: specify position you want to move it to (eg. 1)
   - Start with high quality paired reads first (light green)
   - Highest peaks (about 50% higher than the rest) are used to call the base
   - If the section being analyzed has a paired read, use pair to call the base as well as the peaks. 
   - Low quality ends (grey and blue) can be eliminated by selecting and going to Edit->Clear
   - Very low quality reads that are not essential (i.e.. only sequence of the species for a locality) can be eliminated from the matrix.
   - ​

