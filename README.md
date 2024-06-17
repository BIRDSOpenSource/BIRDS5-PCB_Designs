
<div align="center">
  <a href="https://lean-sat.org/opensource/">
  <img alt="Join the monthly community webinars" src="https://img.shields.io/badge/join_our-monthly_webinars-orange" />
  </a>
</div>

<div align="center">
<img  width="25%" src="https://github.com/BIRDSOpenSource/BIRDS5-CAD/assets/100206676/fd3ff8ed-76a4-4b20-aec6-1a9d83f25005">
</div>


# BIRDS5-PCB_Designs
 Documentation for the PCB design files used in the boards in the BIRDS5 satellite


## About the BIRDS5 Program:

<img width="50%" src="https://github.com/BIRDSOpenSource/BIRDS5-CAD/assets/100206676/5cb7bd65-6989-4c46-8026-098282452dca">

The Mission Statement of the Project is:

> Build Uganda and Zimbabwe’s first satellite while improving the standardized bus system for future missions, giving continuity to the satellite development of Japan and previous missions from BIRDS-1,2,3 and 4.

The project is led by Kyushu Institute of Technology in Japan and involves students from Uganda, Zimbabwe, Trinidad and Tobago, and Japan.

Satellite Names: Taka (Japan), ZIMSAT-1 (Zimbabwe) and PearlAfricaSat-1 (Uganda)

Stakeholders: Uganda Science, Technology and Innovation Office of the President, Zimbabwe National Geospatial And Space Agency (ZINGSA), and Kyushu Institute of Technology (Kyutech) for Japan.

Project duration: 2018-2022

CubeSat: 1U (10x10x10) cm3, 2U (10x10x20) cm3

Weight: 1.13kg

Launch Date: 21st November 2022

BIRDS-5 has 5 main missions in total; attitude visualisation, Imaging classification Mission (IMG-CLS) and Store & Forward (SF- WARD), Particle Instrument for Nano-satellite(PINO), APRS-Digipeater mission (APRS-DP) 

## Organisation structure
In this repository you will find four main folders
```bash
├── .gitattributes
├── Antenna Panel
│   ├── BIRDS-5_1U_+X-panel_EM_PUPV_v3.2.brd
│   ├── BIRDS-5_1U_+X-panel_EM_PUPV_v3.2.sch
│   ├── BIRDS-5_2U_+X-panel_EM_PUPV_v3.2.brd
│   └── BIRDS-5_2U_+X-panel_EM_PUPV_v3.2.sch
├── Back Plane Board
│   ├── BPB_FM1.brd
│   └── BPB_FM1.sch
├── LICENSE
├── README.md
├── Rear Access Board
│   ├── 1U_Rear_Access_Board
│   │   ├── B5_1U_FM_RAB_Bottom.png
│   │   ├── B5_1U_FM_RAB_Top.png
│   │   ├── B5_1U_FM_RAB_Ver1.brd
│   │   └── B5_1U_FM_RAB_Ver1.sch
│   └── 2U_Rear_Access_Board
│       ├── B5_2U_EM_RAB_Bottom.png
│       ├── B5_2U_EM_RAB_Top.png
│       ├── B5_2U_EM_RAB_Ver3.brd
│       └── B5_2U_EM_RAB_Ver3.sch
└── Solar Panel
    ├── EM Solar Panels
    │   ├── 1U PCB Designs
    │   │   ├── B5_EM_+X_SOLAR_PANEL.b##
    │   │   ├── B5_EM_+X_SOLAR_PANEL.b#1
    │   │   ├── B5_EM_+X_SOLAR_PANEL.brd
    │   │   ├── B5_EM_+X_SOLAR_PANEL.sch
    │   │   ├── B5_EM_+Y_SOLAR_PANEL.b##
    │   │   ├── B5_EM_+Y_SOLAR_PANEL.b#1
    │   │   ├── B5_EM_+Y_SOLAR_PANEL.b#2
    │   │   ├── B5_EM_+Y_SOLAR_PANEL.brd
    │   │   ├── B5_EM_+Y_SOLAR_PANEL.s##
    │   │   ├── B5_EM_+Y_SOLAR_PANEL.s#1
    │   │   ├── B5_EM_+Y_SOLAR_PANEL.s#2
    │   │   ├── B5_EM_+Y_SOLAR_PANEL.s#3
    │   │   ├── B5_EM_+Y_SOLAR_PANEL.sch
    │   │   ├── B5_EM_+Z_SOLAR_PANEL.b#1
    │   │   ├── B5_EM_+Z_SOLAR_PANEL.b#2
    │   │   ├── B5_EM_+Z_SOLAR_PANEL.brd
    │   │   ├── B5_EM_+Z_SOLAR_PANEL.s#1
    │   │   ├── B5_EM_+Z_SOLAR_PANEL.sch
    │   │   ├── B5_EM_-X_SOLAR_PANEL.b#1
    │   │   ├── B5_EM_-X_SOLAR_PANEL.brd
    │   │   ├── B5_EM_-X_SOLAR_PANEL.sch
    │   │   ├── B5_EM_-Z_SOLAR_PANEL.b#1
    │   │   ├── B5_EM_-Z_SOLAR_PANEL.brd
    │   │   └── B5_EM_-Z_SOLAR_PANEL.sch
    │   ├── 2U PCB Designs
    │   │   ├── B5_EM_+Y_SOLAR_PANEL.b##
    │   │   ├── B5_EM_+Y_SOLAR_PANEL.b#1
    │   │   ├── B5_EM_+Y_SOLAR_PANEL.b#2
    │   │   ├── B5_EM_+Y_SOLAR_PANEL.brd
    │   │   ├── B5_EM_+Y_SOLAR_PANEL.sch
    │   │   ├── B5_EM_-X_SOLAR_PANEL.b#1
    │   │   ├── B5_EM_-X_SOLAR_PANEL.brd
    │   │   ├── B5_EM_-X_SOLAR_PANEL.s#1
    │   │   ├── B5_EM_-X_SOLAR_PANEL.sch
    │   │   ├── B5_EM_-Y_SOLAR_PANEL.brd
    │   │   ├── B5_EM_-Y_SOLAR_PANEL.sch
    │   │   ├── B5_EM_-Z_SOLAR_PANEL.b#1
    │   │   ├── B5_EM_-Z_SOLAR_PANEL.b#2
    │   │   ├── B5_EM_-Z_SOLAR_PANEL.brd
    │   │   ├── B5_EM_-Z_SOLAR_PANEL.s#1
    │   │   └── B5_EM_-Z_SOLAR_PANEL.sch
    │   └── Solar Attachment Training
    │       └── From Victor
    │           ├── IMG_7086.JPG
    │           ├── IMG_7171.JPG
    │           ├── IMG_7172.JPG
    │           ├── IMG_7173.JPG
    │           ├── IMG_7174.JPG
    │           ├── IMG_7175.JPG
    │           ├── IMG_7176.JPG
    │           ├── IMG_7177.JPG
    │           ├── IMG_7178.JPG
    │           ├── IMG_7179.JPG
    │           ├── IMG_7180.JPG
    │           ├── IMG_7181.JPG
    │           ├── IMG_7182.JPG
    │           ├── IMG_7183.JPG
    │           ├── IMG_7184.JPG
    │           ├── IMG_7185.JPG
    │           ├── IMG_7186.JPG
    │           ├── IMG_7189.JPG
    │           ├── IMG_7190.JPG
    │           ├── IMG_7207.MOV
    │           ├── IMG_7209.JPG
    │           └── IMG_7211.JPG
    └── FM Solar Panels
        ├── 1U Solar Panels Data-2022_05_19
        │   ├── 1U Solar Panel PCBs
        │   │   ├── BIRDS-5_FM_+Y Panel_Ver2.brd
        │   │   ├── BIRDS-5_FM_+Y Panel_Ver2.sch
        │   │   ├── BIRDS-5_FM_+Z Panel_Ver2.brd
        │   │   ├── BIRDS-5_FM_+Z Panel_Ver2.sch
        │   │   ├── BIRDS-5_FM_-X Panel_Ver2.brd
        │   │   ├── BIRDS-5_FM_-X Panel_Ver2.sch
        │   │   ├── BIRDS-5_FM_-Y Panel_Ver2.brd
        │   │   ├── BIRDS-5_FM_-Y Panel_Ver2.sch
        │   │   ├── BIRDS-5_FM_-Z_Panel_Ver3.b#1
        │   │   ├── BIRDS-5_FM_-Z_Panel_Ver4.brd
        │   │   ├── BIRDS-5_FM_-Z_Panel_Ver4.sch
        │   │   └── READ ME.txt
        │   ├── BOM
        │   │   ├── +Y_1U_FM_BOM.txt
        │   │   ├── +Z_1U_FM_BOM
        │   │   ├── -X_1U_FM_BOM
        │   │   ├── -Y_1U_FM_BOM
        │   │   ├── -Y_1U_FM_BOM.txt
        │   │   └── -Z_1U_FM_BOM
        │   ├── Drill Data
        │   │   ├── +Y
        │   │   │   ├── BIRDS-5_FM_+Y Panel_Ver2.drd
        │   │   │   └── CAMOutputs
        │   │   │       └── GerberFiles
        │   │   │           └── gerber_job.gbrjob
        │   │   ├── +Z
        │   │   │   ├── BIRDS-5_FM_+Z Panel_Ver2.drd
        │   │   │   └── CAMOutputs
        │   │   │       └── GerberFiles
        │   │   │           └── gerber_job.gbrjob
        │   │   ├── -X
        │   │   │   ├── BIRDS-5_FM_-X Panel_Ver2.drd
        │   │   │   └── CAMOutputs
        │   │   │       └── GerberFiles
        │   │   │           └── gerber_job.gbrjob
        │   │   └── -Y
        │   │       ├── BIRDS-5_FM_-Y Panel_Ver2.drd
        │   │       └── CAMOutputs
        │   │           └── GerberFiles
        │   │               └── gerber_job.gbrjob
        │   ├── Gerber Data
        │   │   ├── +Y
        │   │   │   ├── +Y_1U_BIRDS5_Panel.zip
        │   │   │   ├── .cmp
        │   │   │   ├── .out
        │   │   │   ├── .plc
        │   │   │   ├── .pls
        │   │   │   ├── .sol
        │   │   │   ├── .stc
        │   │   │   ├── .sts
        │   │   │   └── CAMOutputs
        │   │   │       └── GerberFiles
        │   │   │           └── gerber_job.gbrjob
        │   │   ├── +Z
        │   │   │   ├── .cmp
        │   │   │   ├── .out
        │   │   │   ├── .plc
        │   │   │   ├── .pls
        │   │   │   ├── .sol
        │   │   │   ├── .stc
        │   │   │   ├── .sts
        │   │   │   └── CAMOutputs
        │   │   │       └── GerberFiles
        │   │   │           └── gerber_job.gbrjob
        │   │   ├── -X
        │   │   │   ├── .cmp
        │   │   │   ├── .out
        │   │   │   ├── .plc
        │   │   │   ├── .pls
        │   │   │   ├── .sol
        │   │   │   ├── .stc
        │   │   │   ├── .sts
        │   │   │   └── CAMOutputs
        │   │   │       └── GerberFiles
        │   │   │           └── gerber_job.gbrjob
        │   │   ├── -Y
        │   │   │   ├── .cmp
        │   │   │   ├── .out
        │   │   │   ├── .plc
        │   │   │   ├── .pls
        │   │   │   ├── .sol
        │   │   │   ├── .stc
        │   │   │   ├── .sts
        │   │   │   └── CAMOutputs
        │   │   │       └── GerberFiles
        │   │   │           └── gerber_job.gbrjob
        │   │   ├── -Z
        │   │   │   ├── .cmp
        │   │   │   ├── .out
        │   │   │   ├── .plc
        │   │   │   ├── .pls
        │   │   │   ├── .sol
        │   │   │   ├── .stc
        │   │   │   ├── .sts
        │   │   │   └── CAMOutputs
        │   │   │       └── GerberFiles
        │   │   │           └── gerber_job.gbrjob
        │   │   └── READ ME.txt
        │   ├── Mounting Drawing
        │   │   ├── +Y
        │   │   │   ├── +Y_Mounting Drawing.pdf
        │   │   │   └── +Y_Mounting Drawing.pptx
        │   │   ├── +Z
        │   │   │   ├── +Z_Mounting Drawings.pdf
        │   │   │   └── +Z_Mounting Drawings.pptx
        │   │   ├── -X
        │   │   │   ├── -X_Mounting Drawings.pptx
        │   │   │   └── _X_Mounting Drawings.pdf
        │   │   ├── -Y
        │   │   │   ├── -Y_Mounting Drawings.pdf
        │   │   │   └── -Y_Mounting Drawings.pptx
        │   │   └── -Z
        │   │       ├── -Z_Mounting Drawings.pptx
        │   │       └── _Z_Mounting Drawings.pdf
        │   └── PBan_Parts_List
        │       ├── +Y_pban_parts_list_20210514.xls
        │       ├── +Z_pban_parts_list_20210517.xls
        │       ├── -X_pban_parts_list_20210514(Φªïµ£¼).xls
        │       ├── -Y_pban_parts_list_20210514.xls
        │       └── -Z_pban_parts_list_20210602.xlsx
        └── 2U Solar Panels Data-2022_05_19
            ├── 2U Solar Panels PCBs
            │   ├── +Y_panel_FM_2U_Ver1_v1.brd
            │   ├── +Y_panel_FM_2U_Ver1_v1.sch
            │   ├── -X_panel_FM_2U_Ver1_v1.brd
            │   ├── -X_panel_FM_2U_Ver1_v1.sch
            │   ├── -Y_panel_FM_2U_Ver1_v1.brd
            │   ├── -Y_panel_FM_2U_Ver1_v1.sch
            │   ├── -Z_Panel_FM_Ver3.brd
            │   ├── -Z_Panel_FM_Ver3.sch
            │   └── READ ME.txt
            ├── BOM
            │   ├── +Y_2U_Panel_FM_BOM
            │   ├── -X_2U_Panel_FM_BOM
            │   ├── -X_2U_Panel_FM_BOM.txt
            │   └── -Z_1U_Panel_FM_BOM
            ├── Drill Data
            │   ├── +Y
            │   │   ├── +Y_panel_EM_2U_Ver1_v1.drd
            │   │   └── CAMOutputs
            │   │       └── GerberFiles
            │   │           └── gerber_job.gbrjob
            │   ├── -Y
            │   │   ├── -Y_panel_EM_2U_Ver1_v1.drd
            │   │   └── CAMOutputs
            │   │       └── GerberFiles
            │   │           └── gerber_job.gbrjob
            │   └── -Z
            │       ├── BIRDS-5_FM_-Z_Panel_Ver3.drd
            │       └── CAMOutputs
            │           └── GerberFiles
            │               └── gerber_job.gbrjob
            ├── Gerber Data
            │   ├── +Y
            │   │   ├── .cmp
            │   │   ├── .out
            │   │   ├── .plc
            │   │   ├── .pls
            │   │   ├── .sol
            │   │   ├── .stc
            │   │   ├── .sts
            │   │   └── CAMOutputs
            │   │       └── GerberFiles
            │   │           └── gerber_job.gbrjob
            │   ├── -Y
            │   │   ├── .2l
            │   │   ├── .3l
            │   │   ├── .cmp
            │   │   ├── .drd
            │   │   ├── .out
            │   │   ├── .plc
            │   │   ├── .pls
            │   │   ├── .sol
            │   │   ├── .stc
            │   │   ├── .sts
            │   │   └── CAMOutputs
            │   │       └── GerberFiles
            │   │           └── gerber_job.gbrjob
            │   ├── -Z
            │   │   ├── .cmp
            │   │   ├── .out
            │   │   ├── .plc
            │   │   ├── .pls
            │   │   ├── .sol
            │   │   ├── .stc
            │   │   ├── .sts
            │   │   └── CAMOutputs
            │   │       └── GerberFiles
            │   │           └── gerber_job.gbrjob
            │   └── READ ME.txt
            ├── Mounting Drawing
            │   ├── +Y
            │   │   ├── 2U_+Y_Mounting Drawings.pdf
            │   │   └── 2U_+Y_Mounting Drawings.pptx
            │   ├── -X
            │   │   ├── 2U_-X_Mounting Drawings.pdf
            │   │   └── 2U_-X_Mounting Drawings.pptx
            │   ├── -Y
            │   │   ├── 2U_-Y_Mounting Drawings.pdf
            │   │   └── 2U_-Y_Mounting Drawings.pptx
            │   └── -Z
            │       ├── -Z_Mounting Drawings.pptx
            │       └── _Z_Mounting Drawings.pdf
            └── PBan Parts Lists
                ├── +Y_2U_pban_parts_list_20210514.xls
                ├── -X__2U_pban_parts_list_20210514.xls
                ├── -Y_2U_pban_parts_list_20210514.xls
                ├── -Z_pban_parts_list_20210602.xlsx
                └── READ ME.txt
```

`/Antenna Panel` contains

`/Back Plane Board` contains

`/Rear Access Board` contains two folders 
    `/1U_Rear_Access_Board`
    `/2U_Rear_Access_Board`
    
`/Solar Panel` folders contains PCB and schematic file for the 1U and 2U solar panel configurations. Within this folder are also pictures from the Solar Panel Attachment Training to aid in understanding how to attaach the solar cells to the panels. 

## How to use
> [!CAUTION]
> The files `.sch` and `.brd` files in this repositiry were created using Eagle software.
 
For those that want to import these files into 
KiCAD7 [here's how you do it](https://community.element14.com/technologies/open-source-hardware/b/blog/posts/working-with-kicad-7-importing-eagle-files) 
KiCAD5.1 [here's how you do it](https://www.youtube.com/watch?v=RBc02MwpKxk&t=1s)

> [!NOTE]
> If you are wondering "What are the .s#1 and .b#1 files?"
> They are EAGLE backup files. Each time you save your work, the previous copy becomes one of them, in case you decide you were being a muppet, or just change your mind.

## I like this project, can I help you?
You are welcome 🙂

* Give us a star ⭐
* Watch repository to be notified about updates 👀
* If you will find some errors, report them in Issues 🐞
* Try Birds designs on some real computer and let us know how it worked in Discussions. 💬
* We would greatly appreciate if you would also tell others about this ecosystem, it helps us to improve BIRDS Open Source. Thank you!

[License for this project](docs/LICENSE.md)
