Issue Summary
The model failed to initialize because the data.obcs file, was either missing or improperly configured in the run directory.

MITgcm Message

The error message I got was ERROR: Missing or invalid OBCS configuration in data.obcs. which told me something was wrong with the data.obcs 


Issue Remedy

I saw that the it was missing in the run directory when I looked for it  and then I added it in which resolved the issue.