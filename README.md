
        - #EasyDockVina is a free tool to perform multiple receptor-ligand
          docking with AutoDockVina.	
        - EasyDock supports popular docking programs, namely Autodock Vina, gnina, and smina.	
<br/>
/////////////////////////////////////////////////////////////////////////<br/>

![965d62_d33342f5e56c446684070f46a65339d6~mv2](https://github.com/user-attachments/assets/0b02b8f8-0990-4a21-a543-6f22fdae3b89)



![docker_aim](https://github.com/user-attachments/assets/97162be8-b073-41ce-9eae-6fb8255debfc)




![blinddock-gif-small](https://github.com/user-attachments/assets/72b1115b-521c-4753-a268-6c038cfdb55c)







[+] Parameters:

        --receptor file.pdbqt                   Receptor should be prepared and in pdbqt format.
        --ligands ./ligands/                    Ligands folder, all ligands should be in pdbqt format.
        --config config.txt                     Config file should only contain search box center and size.
        --output docking_result.txt             All docking results will be written on the file specified.

[+] Example:

        EasyDockVina dock --receptor 1mq4.pdbqt --ligands ./ligands/ --config config.txt --output results.txt
        
        
Config.txt file should contain only:<br/>
center_x , center_y , center_z = <br/>
size_x , size_y , size_z =  <br/>

