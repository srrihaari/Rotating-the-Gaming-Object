 # Rotating-the-Gaming-Object

## Aim:
To develop a 3D application for rotating the gaming objects in unity.
## Algorithm:

## Developed by: Sri hari R
## Register number: 212223040202

### Step1:
Start
### Step2:
Click File -> Scene -> Select the scene -> Save as-> New folder(Scenes)-> File name (Expno1)
### Step3:
Click Hierarchy -> 3DObject -> Cylinder
Hierarchy -> 3DObject -> Capsule
Hierarchy -> 3DObject -> Text
Hierarchy -> Effects -> Particle system
### Step4:
Create a folder in project and name as Materials
Material folder -> Create -> Material (Name: Cylinder)
Inspector ->Surface Inputs ->BaseMAp (Choose the color)
Drag the Cylinder to the plane and release the mouse

Create a folder in project and name as Materials
Material folder -> Create -> Material (Name: Capsule)
Inspector ->Surface Inputs ->BaseMAp (Choose the color)
Drag the Capsule to the plane and release the mouse

### Step5:
Click Hierarchy -> DirectionalLight
Inspector -> Change the color to white (255,255,255)

### Step6:
Create a folder name Coding and create a C# file to add the coding in it.

### Step7:
To add our C# Script file to our selected object, click on the C# Script file and drag it to our selected objects in the Hierarchy window nad run the application.

### Step8:
Stop

## Program:

```
using System.Collections;
using System.Collections.Generic;
using UnityEngine;

public class Rotate : MonoBehaviour
{
    // Start is called before the first frame update
    void Start()
    {
        
    }

    // Update is called once per frame
    void Update()
    {
        transform.RotateAround(Vector3.up,Vector3.left,40*Time.deltaTime);
    }
}
```

## Output:

<img width="1920" height="1080" alt="Screenshot 2025-08-20 083411" src="https://github.com/user-attachments/assets/6df47fda-aa7c-4f06-be28-7f18628e553e" />



## Result:

The 3D application for rotating the gaming objects in unity is executed sucessfully.
 
