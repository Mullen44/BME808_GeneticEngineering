# BME808_GeneticEngineering

This repository hosts labs required of a fourth year Genetic Engineering class in the department of Biomedical Engineering at Ryerson University

1: CPG Islands - This Code loops through a DNA strand incrementing by the size of a specific window and searches for areas with high C and G content.  These locations are more stable due to 3 hydrogen bonds between base pairs (vs 2 between A and T) and therefore are often found at the start of a coding sequence.

2: Gene Pattern Finder - Coding strands of DNA have different features which are necessary for the strand to be transcribed. This program looks for start codons, stop codons and shine dalgarno sequences in a DNA strand and based off of this identifies locations where possible open reading frames are located.

3: Hidden Markov Model - This program employs both a brute force and viterbi method for implementing a hidden markov model to predict assign via probability labels to linear sequences.

4: Needleman Wunsch - This algorithm takes two input DNA strands and uses a custom scoring matrix scores the two based off of how similar they are and then traces back the correct path for optimal alignment.  This program accomplishes this and displays the scoring matrix as well as the most optimal alignment.
