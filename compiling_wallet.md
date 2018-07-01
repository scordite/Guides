# Guides wallet compiling


# Before starting make sure your machine is ready for compiling the files:

$ sudo apt-get update

$ sudo apt-get install build-essential git cmake libboost-all-dev python make automake g++ gcc


# Compiling and starting your wallet with the following steps:

# Step 1

$ git clone https://github.com/scordite/scordite.git  // This will download the scordite rep

$ ls                                                  // Will show the content of the folder you are in

$ cd scordite                                         // Enter scordite folder

$ ls                                                  // Will show the content of the folder you are in 

$ make                                                // start compiling


# Wait for the wallet to compile

# Step 2

$ cd build
$ cd release
$ cd src


$ ls
$ ./simplewallet
