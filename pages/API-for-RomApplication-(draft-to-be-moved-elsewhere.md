---
title: API for RomApplication (draft to be moved elsewhere
keywords: 
tags: [API-for-RomApplication-(draft-to-be-moved-elsewhere.md]
sidebar: kratos_sidebar
summary: 
---

The RomApplication expects a basis matrix <a href="https://www.codecogs.com/eqnedit.php?latex=\color{Black}\bold{{\Phi}}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\color{Black}\bold{{\Phi}}" title="\color{Black}\bold{{\Phi}}" /></a> (obtained for example from a POD procedure or using Modal Derivatives) with as many rows as degrees of freedom times the number of nodes, and as many columns as representative modes are being consired

![basis]

The RomApplication expects this basis in the form of a JSON file with saved as RomParameters.json which should be located in the same folder as the MainKratos.py and should be in the following format:

~~~json
{
  "rom_settings": {
    "nodal_unknowns": [
      "ROTATION_X",
      "ROTATION_Y",
      "ROTATION_Z",
      "DISPLACEMENT_X",
      "DISPLACEMENT_Y",
      "DISPLACEMENT_Z"
    ],
    "number_of_rom_dofs": 5
  },
  "nodal_modes": {
    "1": [
      [
        "Phi[0, :]"
      ],
      [
        "Phi[1, :]"
      ],
      [
        "Phi[2,:]"
      ],
      [
        "Phi[3,:]"
      ],
      [
        "Phi[4,:]"
      ],
      [
        "Phi[5,:]"
      ]
    ],
    "2": [
      .
      .
      .
    "dofs": [
      [
        "Phi[dofs*nodes -6 ,:]"
      ],
      [
        "Phi[dofs*nodes -5 ,:]"  
      ],
      [
        "Phi[dofs*nodes -4 ,:]"
      ],
      [
        "Phi[dofs*nodes -3 ,:]" 
      ],
      [
        "Phi[dofs*nodes -2 ,:]"
      ],
      [
        "Phi[dofs*nodes -1 ,:]"
      ]
    ]
  }
}

~~~ 


you can find examples of these files [here](https://github.com/KratosMultiphysics/Kratos/tree/master/applications/RomApplication/tests)



Exaplain also ElementsAndWeigths.json

Draw a chart with the files for a ROM and an HROM simulation






[basis]:https://github.com/KratosMultiphysics/Documentation/blob/master/Wiki_files/How_to_interact_with_a_simulation_to_visualize_results_in_real_time/Basis.jpg