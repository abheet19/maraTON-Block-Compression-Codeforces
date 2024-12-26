# TON Block Compression Solution

This repository contains the source code for a block compression solution designed for the TON Blockchain Compression Contest. The goal of this project is to efficiently compress and decompress TON blockchain blocks to reduce network load.

## Problem Description

The task is to implement a compression algorithm that operates on serialized TON blockchain blocks. These blocks are represented as byte strings obtained through the "bag of cells" serialization algorithm. The input and output for both compression and decompression are base64-encoded strings.

The solution utilizes the `ton_crypto_lib` C++ library provided by the contest organizers, which includes functionalities for base64 encoding/decoding and LZ4 compression/decompression.