To add a new assignment go to the proj.json file and input the following code

    "proj3": { <--- The proj name increases by one each time thus proj0, proj1, porj2, porj3, proj4 ... etc
      "proj_name": "(Asssignment name goes here)", <--- A "," comma goes here because there is another object were going to add
      "img_name": "images/(image name goes here, include file type)" <--- Notice there is no "," comma here because it is the last object   
    }

Make sure the proj before the proj you add has a "," comma after the "}" bracket ex ...

    {
    
      "proj0": { 
        "proj_name": "Blue Twilight",   
        "img_name": "images/Background.png"   
      },
    
      "proj1": {       
        "proj_name": "Sky Whale",    
        "img_name": "images/sky_for_dreamers_by_rhads-d6gbpqu.jpg"    
      }, 
    
      "proj2": {
        "proj_name": "Eater of Worlds",   
        "img_name": "images/dX2maU0.jpg"  
      }, <--- COMMA GOES HERE BECAUSE WE ARE ADDING ANOTHER ASSIGNMENT   
    
      "proj3": {
        "proj_name": "Stuff 3",
        "img_name": "images/imgname"
      } <--- NO COMMA HERE BECAUSE WE DONT WANT ANYMORE ASSIGNMENTS IN THE JSON FILE 
      
    }
