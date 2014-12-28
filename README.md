LookaheadTagger
===============

This is a C++ implementation of the part-of-speech (POS) tagging algorithm by Tsuruoka et.al.  This is trainable with your own POS-annotated corpus.

## Compiling

> cd lapos-X.X/ 
> make

## Tag sentences

Prepare the input in one-sentence-per-line format, then run the "lapos" command:

> echo "He opened the window." | ./lapos -t -m ./model_wsj02-21
He/PRP opened/VBD the/DT window/NN ./.
How to build a tagging model with your own annotated corpus

Please see the README file.

## References

[1] Yoshimasa Tsuruoka, Yusuke Miyao, and Jun'ichi Kazama. 2011. Learning with Lookahead: Can History-Based Models Rival Globally Optimized Models? In Proceedings of CoNLL, pp. 238-246. 

http://www.logos.ic.i.u-tokyo.ac.jp/~tsuruoka/lapos/

