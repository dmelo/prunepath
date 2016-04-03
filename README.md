prunepath
=========

usage: prunepath DIR SIZELIMIT
Delete files until the size of DIR goes under SIZELIMIT, oldest modified files first.

    DIR - path to the directory to be pruned.
    SIZELIMIT - Threshold of size of the DIR. It must match [0-9]+[KMGT]?. Considering 1K = 1024 bytes.
