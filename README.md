# pyramidal-hash
The core component is a pyramidal reduction: a 64- byte vector is iteratively compressed level by level.At each level adjacent bytes are combined using: SBOX,XOR anchor and rotate-left.This continues until a single byte remains(the tip of the pyramid).Seven independent statistical test were performed on the correct, fully validated implementation.
