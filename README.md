# PROVERIF EXAMPLES

This directory contains some example ProVerif files.

## Verifying the Examples

You need to first download ProVerif from:
   https://prosecco.gforge.inria.fr/personal/bblanche/proverif/
You can either download the binary version or compiler it from source.
In either case you will have an executable file called "proverif" which
you can copy to this folder or add to your PATH.

To verify each file, execute:
   proverif <FILE.pv>
This will display the result of analysis.
To filter out all details except the main results, execute:
   proverif <FILE.pv> | grep ^RESULT


## FILES

Here are the files in this folder:
- NS-PK.pv: the original Needham-Schroeder Public-Key Protocol (with attack)
- NSL-PK.pv: the fixed Needham-Schroeder-Lowe Public-Key Protocol
- RPC.pv: EXERCISE - model and verify a Secure RPC Protocol


