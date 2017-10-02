# clone_coin
This is a repo for allowing anyone to clone bitcoin and make their own bitcoin based crypto currency

Dependencies:
- Standard Bitcoin build environment deps
- GensisH0 - A python script for creating the parameters required for a unique genesis block
- modified chainparams.cpp for Bitcoin usage

Current Issues:
- only "sort of" works on regtest network
- only creates genesis block and 1 new block
- any subsequent blocks are not created; unsure why
