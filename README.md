# thinkmorse-rust
A Rust version of the Python thinkmorse script

## Prerequisites
To have the control over the lid LED you need `ec_sys` kernel module loaded with write support enabled. To do this, add `ec_sys.write_support=1` to your kernel parameters. 