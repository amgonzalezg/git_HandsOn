# git_HandsOn
This is a Python script that classifies a given sequence as DNA or RNA, and optionally searches for a given motif in the sequence. The script uses regular expressions to perform the classification and motif search.

The script takes two command line arguments: '-s' or '--seq', which specifies the input sequence, and '-m' or '--motif', which specifies the motif to search for (optional). The input sequence must be provided as a string, and the motif must be provided as a string if the '-m' option is used.

The script first converts the input sequence to uppercase letters, then checks if the sequence matches a pattern of DNA or RNA. If the sequence contains a 'T', it is classified as DNA. If the sequence contains a 'U', it is classified as RNA. If the sequence contains neither 'T' nor 'U', it is classified as either DNA or RNA.

If the '-m' option is used, the script also searches for the given motif in the input sequence using regular expressions. If the motif is found, the script outputs "FOUND". If the motif is not found, the script outputs "NOT FOUND".
