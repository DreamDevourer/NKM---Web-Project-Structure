# NKM---Web-Project-Structure
🖥️ A simple and lazy Web Development project structure based on ITCSS Method and HubSpot Methodologies. 🚀

<pre>
           ,--.  ,--.,--. ,--.,--.   ,--.                          
,-----.    |  ,'.|  ||  .'   /|   `.'   |    ,-----.               
'-----'    |  |' '  ||  .   ' |  |'.'|  |    '-----'               
           |  | `   ||  |\   \|  |   |  |                          
           `--'  `--'`--' '--'`--'   `--'                          
,------.                ,--.               ,--.                    
|  .--. ',--.--. ,---.  `--' ,---.  ,---.,-'  '-.                  
|  '--' ||  .--'| .-. | ,--.| .-. :| .--''-.  .-'                  
|  | --' |  |   ' '-' ' |  |\   --.\ `--.  |  |                    
`--'     `--'    `---'.-'  / `----' `---'  `--'                    
 ,---.   ,--.         '---'           ,--.                         
'   .-',-'  '-.,--.--.,--.,--. ,---.,-'  '-.,--.,--.,--.--. ,---.  
`.  `-.'-.  .-'|  .--'|  ||  || .--''-.  .-'|  ||  ||  .--'| .-. : 
.-'    | |  |  |  |   '  ''  '\ `--.  |  |  '  ''  '|  |   \   --. 
`-----'  `--'  `--'    `----'  `---'  `--'   `----' `--'    `----' 
                                                                   

This is the default project structure made by Nicolas Mendes based on the ITCSS (Inverted Triangle CSS) 
follows this based on the idea of the inverted triangle and it is based on Boilerplate HubSpot Theme. 
The higher the triangle you are, the weaker the selector will be. The selectors present in a layer 
always overwrite the selects of the top layer.


x=============x Pyramid Base Inverted x=============x

_        1 - Settings
|        It is where we declare the settings of our project, such as variables of measurements, colors, etc.
|
|        2 - Tools
|        It is where you will store your mixins and functions needed to build your layouts.
|        It can be anything from font-face mixins to animation mixins, etc.
|        If you are not using pre-processors such as SASS or Less, this layer can be ignored.
|
|        3 - Generic
|        This is the first layer that will actually apply CSS final and it is intended for the 
|        most generic properties. In general, it is where we put resets, box-sizing, etc.
|
|        4 - Base or Elements
|        Base, also called Elements. This layer serves to stylize the most basic part of the elements. 
|        No ids or classes here, only selectors of elements such as H1-H6 headings, a, buttons, etc.
|        Usually used to make CSS reset.
|
|        5 - Objects
|        Following the principles of OOCSs (object-oriented CSS), here is where we will have our little "objects", 
|        which are nothing more than small pieces of the interface, in general, patterns that are repeated throughout 
|        the site and who may have or not a visual layer above.
|        We only use classes here. It is where we begin to declare the structure of our elements.
|        Here is where we make the patterns of buttons, lists, panels, etc. At that time, only the use of classes are also allowed.
|
|        6 - Components
|        Here we also only use classes. It is where we begin to stylize our elements more specifically.
|        While in the objects we try to abstract as much as possible, to have many reusable and generic objects, here we will 
|        be specific when creating the components.
|
|        7 - Trumps
|        It is the layer with greater specificity. Here we create small classes with "! Important;" to overwrite certain rules.
V

x=============x Pyramid Top Inverted x=============x
</pre>
