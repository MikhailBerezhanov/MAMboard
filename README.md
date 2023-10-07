# 
## Online audio system

![board image](/board_img.jpg)

This device 



### Dependencies
PCB development is performed using `Altium Designer 19` and higher.
Components library is linked as separate submodule:

```bash
git submodule init
git submodule update
cd pcb/libs
git checkout master
```

### Manufacturing and assembly
Current project provides all necessary files for _pcb order_:

* Bill of materials (BOM)
* Gerber files
* Assembly drawings

Files mentioned above are located in:
`./pcb/vX.X/Project Outputs for Autoinformer_vX.X/`

where `X.X` is version of the board. The lastest version for now is `1.1`.