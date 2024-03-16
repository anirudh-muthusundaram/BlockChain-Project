________________________________________________________________________________________________________

                                 INSTRUCTIONS TO RUN DAPP ON GANACHE
________________________________________________________________________________________________________
                                 Go to the SneakTag-Contract Directory

MAKE SURE THAT GANACHE IS RUNNING ON YOUR SYSTEM

1) open commandline interface

2) RUN command truffle compile

3) RUN command truffle migrate -reset

4) RUN command truffle-export-abi and copy contents of the abi.json file from the builds directory

5) Note the contract address created and copy that too


                               Go to the SneakTag-DAPP directory

                               Navigate to SRC and in that naivgate to components folder


1) copy the contents of the abi.json from the build directory to the SneakTag.json file inside components file

2) Now in each js file inside the components directory pste the contract address you copied

3) Now from the root directory of SneakTag-DAPP run command npm start

4) The DAPP will open on localhost:3000 from here you can interact with the applicatio
