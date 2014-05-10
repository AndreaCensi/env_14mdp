2014-04-29

This works:

    tmdp pomdp-list --mdps pomdp_intruder_2,pomdp_intruder_4,pomdp_intruder_4a,pomdp_intruder_4b,pomdp_intruder_6,pomdp_intruder_8,pomdp_intruder_11 -o all2 -c  "parmake recurse=1"

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



