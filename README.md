
Reproducible research
=====================

This works:
    
    tmdp pomdp-list --horizons --mdps intruderdec_2,intruderdec_4,intruderdec_4a,intruderdec_4b,intruderdec_6,intruderdec_6b,intruderdec_8 -o all3 --console

    tmdp pomdp-list --mdps pomdp_intruder_2,pomdp_intruder_4,pomdp_intruder_4a,pomdp_intruder_4b,pomdp_intruder_6,pomdp_intruder_8,pomdp_intruder_11 -o all3 -c  "parmake recurse=1"

Then copy using:

    rsync -avP all2/reports* ../../docs/14tmdp/14tmdpnotes/figures/all


tmdp pomdp-list --mdps intruderdec_2,intruderdec_4,intruderdec_4a,intruderdec_4b,intruderdec_6,intruderdec_8,intruderdec_11 -o all3 -c  "parmake recurse=1"


Other misc
===========
    tmdp pomdp-list --mdps pomdp_intruder_4 -o pomdp_intruder_4 -c  "parmake recurse=1"


#    tmdp pomdp-list --mdps intruder-imap2,intruder-imap4,intruder-imap6,intruder-imap8 -o bits -c  "parmake recurse=1"

2 rooms:
intruder-imap4:  requires 1 bit
intruder-imap2: 

3 rooms: (log 3 bits)
intruder-imap6:  
intruder-imap8:    6000 states

tmdp pomdp-list --mdps intruder-imap2 -o 16-imap2 --console
tmdp pomdp-list --mdps intruder-imap7 -o 17-imap7 -c "parmake recurse=1"



Quick, 1 bit:
    tmdp pomdp-list --mdps intruder-imap2 -o imap2 -c  "clean;parmake recurse=1"


tmdp pomdp-list --mdps pomdp_intruder_11 -o pomdp_intruder_11 -c "parmake recurse=1"



