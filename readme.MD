Methods for compressing an image in a certain way to be represented on the gameboy. Only 192 unique 8x8 blocks can be shown at once at a time. The algorithm does not account for color values.

## genetic_algorithm.ipynb
Not working. The algorithm does not converge in a feasible amount of time.

## merge_nearest.ipybn 
Computes differences of blocks using given metric. Then combines the nearest until only 192 unique blocks are left. The representing block for each component can again be chosen using some metric or at random.

License: MIT