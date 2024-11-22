# EasyDockVina

![Static Badge](https://img.shields.io/badge/molecular_docking-computational)
![Static Badge](https://img.shields.io/badge/bioinformatics-computational)
![Static Badge](https://img.shields.io/badge/drugs-computational)
![Static Badge](https://img.shields.io/badge/receptor-computational)
![Static Badge](https://img.shields.io/badge/autodock_vina-computational)

Future Omics Bioinformatics made easy
https://youtu.be/pmXxPVcud54?si=XY9It5HSql8XS7h6 


        EasyDockVina dock [parameters]

        --receptor file.pdbqt                   Receptor should be prepared and in pdbqt format.
        --ligands ./ligands/                    Ligands folder, all ligands should be in pdbqt format.
        --config config.txt                     Config file should only contain search box center and size.
        --output docking_result.txt             All docking results will be written on the file specified.

[+] Example:

        EasyDockVina dock --receptor 1mq4.pdbqt --ligands ./ligands/ --config config.txt --output results.txt
        
this tool will only work on windows machines, linux version is on the way.<br/>

![modelling-fu-7](https://github.com/user-attachments/assets/04e4cb3e-3a4f-40eb-a154-27faee7c95ac)
