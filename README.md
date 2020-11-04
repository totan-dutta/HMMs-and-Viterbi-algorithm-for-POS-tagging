# HMMs-and-Viterbi-algorithm-for-POS-tagging
Modified the Viterbi algorithm to solve the problem of unknown words using various techniques

Solution 1: If the word count for a given tag is 0 then use alpha value to emission probabilities.

Solution 2: Here it is been considered that Unknown words belong to open class tags (NOUN, ADJ, ADV, VERB) So discard other tags. Words contain * are been tagged as X. If the word is absent for a given tag then this word is most probably belongs to open class words.

Solution 3: For Unknown Words, emission probability calculation is done using Laplace Smoothing.

Solution 4: Morphology rules used to assign unknown word tokens.

Solution 5: Tag is been assigned based on the next tag emission probability. For Unknown tags, alpha value is been assigned
