# Design Style Guide

This is my design style guide when I work on projects using Sketch or Figma

## Definition of terms

   **Compositions**
  
  biggest design chunk of an interface. These are usually the section in pages that are made up of modules/components
  (i.e. navigation, landing, about section, contact section, footer etc). Below is one composition, a section of the project's homepage.
  
  ![screen shot 2017-09-10 at 6 12 33 pm](https://user-images.githubusercontent.com/12945705/30248060-a7e4b202-9653-11e7-9d69-aa4f926630b3.png)

  
   **Modules/Components**
  
  these are reusable components which are made out of elements (i.e. search module, gallery module, card module, statistics module). Below is a card module / component.
  
  ![screen shot 2017-09-10 at 6 14 17 pm](https://user-images.githubusercontent.com/12945705/30248074-e36ede42-9653-11e7-8fba-29a8184a95e5.png)

  
  **Elements**
  
  is what comprises a module. These are the building blocks that made up a design module (i.e. search button + search bar = search, nav logo + nav menu = navigation). Below are the icon elements and text elements for the card module.
  
  ![screen shot 2017-09-10 at 6 16 17 pm](https://user-images.githubusercontent.com/12945705/30248099-2cdedb4a-9654-11e7-9d0d-28493df148d5.png)

  
  **Bases**
  
  the bits and pieces of a design. It is a mixture of text, shape, and colors.
  
  _**Article**: [Atomic Design](http://bradfrost.com/blog/post/atomic-web-design/)_
     
  _**Article**: [Component Design System](https://medium.com/@lewisplushumphreys/how-were-using-component-based-design-5f9e3176babb)_


## Design project foldering system and name structure

Folder names:

```
Project-name_monthdayyear (Coins_050317)
  
  00_assets
  
  01_files (coming from client)
  
  02_mockups (jpg files)
    version1 folder
    version2 folder
    version3 folder
    
  03_sketchfigma (sketch files / figma files)
  
  04_prototype (flinto folder)
    flinto file
    mov (folder, contains .mov files)

  05_documentation
  ```
![screen shot 2017-09-10 at 6 20 56 pm](https://user-images.githubusercontent.com/12945705/30248131-d29f1afe-9654-11e7-89ea-a484d9efd06a.png)


## Layer name structure

* For Pages layer names:
  - composition / module / elements
  
    Here is my layer structure for the header design on the right side:
    
![screen shot 2017-09-10 at 6 29 09 pm](https://user-images.githubusercontent.com/12945705/30248206-fcc4ea88-9655-11e7-9aca-5589811aa8e8.png)

  
 * For Symbols layer names (elements):
   - elements / class / modifier
    
   Example:
   
   ```
   button (element) / primary (class) / blue (modifier)
   
   icon (element) / phone (class) / big (modifier)
   ```
   Symbol layer structure for search module
   
   ![screen shot 2017-09-10 at 6 40 45 pm](https://user-images.githubusercontent.com/12945705/30248301-987dcc3c-9657-11e7-9564-4fe912746139.png)

    
## Layer Formatting

* Use lowecase letters for layer names
* Use "/" forward slash as separator for layer names with space in between 
  (i.e. button / primary / blue)
* Arrange layers starting from top to bottom and left to right, which corresponds to compositions' order found on the design. 
  
  Example:
  
  ```
  nav composition
  
  landing composition
  
  about composition
  
  contact composition
  
  footer composition
  ```
* All layers should be in group folder. 

  **Bad**
  ```
  nav (folder group)
  
  button / primary / blue
  
  about (folder group)
  ```
  
  **Good**
  ```
  nav (folder group)
  
  about (folder group)
  
  gallery (folder group)
  ```
  
 * Artboard / Frame names should be Camelcase notation
 
   **Bad**
   ```
   homepage

   cOntacT page
   ```

   **Good**
   ```
   Homepage

   Contact page
   ```
 
 * Use undercase "_" to join two words for names and "-" dash if it has modifier
 
   Example
   ```
   guest_name

   sign_up
   
   gallery - grid
   
   gallery - slider
   ```
   
 * Layer names must be descriptive and short.
 
   Bad
   ```
   button / primary / bigger
   
   border / slightly-gray
   ```
  
   Good
   ```
   button / primary / big
   
   border / gray / 25 (25 corresponds to opacity)
   ```
## Grid System
 
I'm using 8x8 grid system in my projects. 
 
Thus with 8x8 grid system, I'm using nudg.it plugin for Sketch app, to adjust the "arrow" and "shift + arrow" increments to 8px. So that whenever I move a particular element, it will move by 8px. And for Figma, you can change it in the settings panel, for the increments.
 
_**Plugin**: [Nudg it](http://nudg.it/)_
  
 
 ## Typography
 
* Font sizes
 
  I'm using a **base font of 16px** with **diminished fifth 1.414 ratio** in (www.modularscale.com) since it fits well with 8x8 grid system. 
 
  Usual font sizes:
  16px, 24px, 32px, 48px, 64px
 
  _**Tool**: [Modular Scale](http://www.modularscale.com/)_
   
* Line height
 
  _"Multiply your letter size by 1.618 and you will get perfect line height."_

  _**Tool**: [Line height ouput](http://jsbin.com/todidu/1/edit?output)_

  _**Article**: [How to use typography in UI Design](https://blog.prototypr.io/how-to-use-typography-in-ui-design-ce045fa4ff2e)_



 


 
  
