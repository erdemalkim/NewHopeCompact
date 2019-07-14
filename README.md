# NewHopeCompact
Compact and simple RLWE based key encapsulation mechanism

This software package includes implementation of the "NewHope-Compact"
RLWE-based key exchange:

- ref (non-optimized reference implementation)


In the ref directory, build the software by running 'make'. This
will produce 6 binaries in the same directory: 

- test_kem512:     test multiple properties of the key exchange for parameter set n=512, in
                         particular that both parties indeed agree on a shared
                         key
- test_kem768:     test multiple properties of the key exchange for parameter set n=768, in
                         particular that both parties indeed agree on a shared
                         key
- test_kem1024:    test multiple properties of the key exchange for parameter set n=1024, in
                         particular that both parties indeed agree on a shared
                         key
- speed_kem512:    run benchmarks and print results for parameter set n=512
- speed_kem768:    run benchmarks and print results for parameter set n=768
- speed_kem1024:   run benchmarks and print results for parameter set n=1024


# Licence

All codes in this repository is in public domain. Main part of code is taken
from [NewHope](https://newhopecrypto.org/data/NewHope_2019_04_10.zip)
submission to the NIST post-quantum standardization project. fips202.c and
fips202.h is also in public domain from authors listed in the top of these
files.
