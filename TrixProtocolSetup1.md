# How to install & build OpenTrix protocol?  
> **R : OpenTrix network team**  
>  *U : Knuth. N. torvali*  

> `1`  `wrun -rget open_trix_protocol   ` Install `OpenTrix` with `wrun` **( you may need `wrun` )**  
> `2`  `wrun -rget open_trix.lxc        ` Get `OpenTrix` setting packages  
> `3`  `cd OpenTrix & cd OConfigs       ` Go to config directory  
> `4`  `wrun -rget open_trix_bozi       ` Install `bandiz` in `OConfig` directory  
> `5`  `cd open_trix-bandiz & cd bashx  ` Go to setting directory  
> `6`  `wrun -build -o bozi.lpp:lpp     ` Build `bozi.lpp` with `wrun` **( you may need `lpp-script 1.0.3+` )**  
> `7`  `cd .. & cd ..                   ` Go to home directory  
> `8`  `wrun -build -o open_trix.lpp:lpp` Build `open_trix.lpp` with `wrun`, language : `lpp-script`  
> `9`  `chmod +x open_trix.lpp          ` Authorize file execution  

> `0`  `wrun open_trix.lpp` to run `OpenTrix protocol` & `bandiz shcner`
