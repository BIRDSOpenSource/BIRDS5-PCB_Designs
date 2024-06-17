
<div align="center">
  <a href="https://lean-sat.org/opensource/">
  <img alt="Join the monthly community webinars" src="https://img.shields.io/badge/join_our-monthly_webinars-orange" />
  </a>
</div>

:-------------------------:|:-------------------------:
<img width="25%" src="https://github.com/BIRDSOpenSource/BIRDS5-CAD/assets/100206676/5cb7bd65-6989-4c46-8026-098282452dca"> |  <img  width="25%" src="https://github.com/BIRDSOpenSource/BIRDS5-CAD/assets/100206676/fd3ff8ed-76a4-4b20-aec6-1a9d83f25005">

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
│   └── 2U_Rear_Access_Board
└── Solar Panel
    ├── EM Solar Panels
    │   ├── 1U PCB Designs
    │   ├── 2U PCB Designs
    │   └── Solar Attachment Training
    │       └── From Victor
    └── FM Solar Panels
        ├── 1U Solar Panels Data-2022_05_19
        │   ├── 1U Solar Panel PCBs
        │   ├── BOM
        │   ├── Drill Data
        │   │   ├── +Y
        │   │   │   └── CAMOutputs
        │   │   │       └── GerberFiles
        │   │   ├── +Z
        │   │   │   └── CAMOutputs
        │   │   │       └── GerberFiles
        │   │   ├── -X
        │   │   │   └── CAMOutputs
        │   │   │       └── GerberFiles
        │   │   └── -Y
        │   │       └── CAMOutputs
        │   │           └── GerberFiles
        │   ├── Gerber Data
        │   │   ├── +Y
        │   │   │   └── CAMOutputs
        │   │   │       └── GerberFiles
        │   │   ├── +Z
        │   │   │   └── CAMOutputs
        │   │   │       └── GerberFiles
        │   │   ├── -X
        │   │   │   └── CAMOutputs
        │   │   │       └── GerberFiles
        │   │   ├── -Y
        │   │   │   └── CAMOutputs
        │   │   │       └── GerberFiles
        │   │   ├── -Z
        │   │   │   └── CAMOutputs
        │   │   │       └── GerberFiles
        │   │   └── READ ME.txt
        │   ├── Mounting Drawing
        │   │   ├── +Y
        │   │   ├── +Z
        │   │   ├── -X
        │   │   ├── -Y
        │   │   └── -Z
        │   └── PBan_Parts_List
        └── 2U Solar Panels Data-2022_05_19
            ├── 2U Solar Panels PCBs
            ├── BOM
            ├── Drill Data
            │   ├── +Y
            │   │   └── CAMOutputs
            │   │       └── GerberFiles
            │   ├── -Y
            │   │   └── CAMOutputs
            │   │       └── GerberFiles
            │   └── -Z
            │       └── CAMOutputs
            │           └── GerberFiles
            ├── Gerber Data
            │   ├── +Y
            │   │   └── CAMOutputs
            │   │       └── GerberFiles
            │   ├── -Y
            │   │   └── CAMOutputs
            │   │       └── GerberFiles
            │   ├── -Z
            │   │   └── CAMOutputs
            │   │       └── GerberFiles
            ├── Mounting Drawing
            │   ├── +Y
            │   ├── -X
            │   ├── -Y
            │   └── -Z
            └── PBan Parts Lists
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
 or KiCAD5.1 [here's how you do it](https://www.youtube.com/watch?v=RBc02MwpKxk&t=1s).

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
