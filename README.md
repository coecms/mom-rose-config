mom-rose-config
===============

Rose configuration &amp; metadata for MOM4

To use on NCI:

    module use ~access/rose/modules
    module load cylc/git
    module load rose
    
    git clone https://github.com/CoECSS-CompModellingSystems/mom-rose-config.git
    cd mom-rose-config
    
    rose config-edit 
    rose suite-run --gcylc
