# DoubleMetaphone

This is an implementation in modern Swift of Lawrence Philips's Double Metaphone algorithm.
See:  
[The Double Metaphone Search Algorithm](https://drdobbs.com/the-double-metaphone-search-algorithm/184401251?pgno=2).

## Usage

    let encoder = DoubleMetaphone()
    (primary, secondary) = encoder.encode("nameToBeEncoded")



