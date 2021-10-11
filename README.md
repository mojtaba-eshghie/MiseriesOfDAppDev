# MiseriesOfDAppDev

## Using solc-select
First get rid of any pre-installed standalone solc compiler. Add the solc-select to path, and do the following:

    SOLC_VERSION=0.4.26
    # use the following to list all installed solc compilers with solc-select
    solc-select install
    # use the following to install a 
    solc-select install SOLC_VERSION
    # use this to activate the desired/just installed version:
    solc-select use $SOLC_VERSION
    # now you can confirm that previous commands have been effective by issuing:
    solc --version
    
    