# IBM-NZ-TRID
IBM Netezza Tri Dimensional Analysis


# This script is provided free of charge by IBM Corporation as a
# convenience to its customers.  This script is provided "AS-IS" with
# no warranty whatsoever.  The customer accepts all risk in connection
# with the use of this script, and IBM Corporation shall have no
# liability whatsoever.

1) Please create a new empty directory on your Netezza host called "trid".
2) Copy the attached file, tri-d.tar.gz, into the new "trid" directory.
3) Then, run the following two commands to extract and run the Tri-Dimensional 

Analysis collection scripts:
tar xvzf tri-d.tar.gz
./runtrid.sh

It may take a few minutes for the script to run.  When the script completes, it will 
create an output file, trid_output.zip. Please send us this output, and then you 
may delete the "trid" directory with the collection scripts and output
