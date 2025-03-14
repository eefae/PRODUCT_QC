This is an empty template project to demonstrate directory structure for future project creation.

Overview of directory structure is shown below:

.
└── Project Top/
    ├── info.txt : project information
    ├── exdes : contains design source files/
    │   ├── src : sources files (bd, .v, etc..)
    │   ├── vivado : vivado project dir
    │   ├── vitis_wkspc : vitis workspace dir
    │   ├── scripts : scripts to rebuild project files
    │   └── Makefile : used to call scripts for automation
    ├── prebuilt : contains prebuilt bitstreams & ltx for quick deployment
    └── doc : contains documentation/
        ├── testflow : document detailing entire test procedure
        └── spec : schematic sheets & datasheets
