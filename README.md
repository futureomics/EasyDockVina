
        - #EasyDockVina is a free tool to perform multiple receptor-ligand
          docking with AutoDockVina.	
        - EasyDock supports popular docking programs, namely Autodock Vina, gnina, and smina.	
<br/>
/////////////////////////////////////////////////////////////////////////<br/>

![965d62_d33342f5e56c446684070f46a65339d6~mv2](https://github.com/user-attachments/assets/0b02b8f8-0990-4a21-a543-6f22fdae3b89)

[+] Parameters:

        --receptor file.pdbqt                   Receptor should be prepared and in pdbqt format.
        --ligands ./ligands/                    Ligands folder, all ligands should be in pdbqt format.
        --config config.txt                     Config file should only contain search box center and size.
        --output docking_result.txt             All docking results will be written on the file specified.

[+] Example:

        EasyDockVina dock --receptor 1mq4.pdbqt --ligands ./ligands/ --config config.txt --output results.txt
        
        
Config.txt file should contain only:<br/>
center_x = <br/>
center_y = <br/>
center_z = <br/>
size_x = <br/>
size_y = <br/>
size_z =  <br/>

