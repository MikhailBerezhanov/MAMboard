# Mobile audio module (MAM) 
## pcb

![board image](/board_img.jpg)

This project includes board scheme and manufacturing details. Current revision is `1.1`.
Board main features:
* Input power range 14V..28V
* Internet connection using onbard 4G LTE (SIM card needed)
* GPS connection (3V external antenna needed)
* AUDIO In (microphone input can be routed to amplified audio out)
* AUDIO Out Amplified (ready for external speaker use)
* External Memory storage (uSD card)
* Open-Linux programmable board

### Dependencies
PCB development is performed using `Altium Designer 19` or versions higher.
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