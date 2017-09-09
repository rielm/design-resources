# Design Style Guide

This is my design style guide when I work on projects using Sketch or Figma

## Definition of terms

   **Compositions**
  
  biggest design chunk of an interface. These are usually the section in pages that are made up of modules/components.
  (i.e. navigation, landing, about section, contact section, footer etc)
  
   **Modules/Components**
  
  these are reusable components which are made out of elements.
  (i.e. search module, gallery module, card module, statistics module)
  
  **Elements**
  
  is what comprises a module. These are the building blocks that made up a design module.
  
  (i.e. search button + search bar = search, nav logo + nav menu = navigation)
  
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


## Layer name structure

* For Pages layer names:
  - composition / module / elements
  
  Example:
  ```
  nav (folder group)
    
    nav (composition) / search (module)
      
      search (module) / button (elements)
        
      search (module) / bar (elements)  
  ```  
  
 * For Symbols layer names (elements):
   - elements / class / modifier
    
   Example:
   
   ```
   button (element) / primary (class) / blue (modifier)
   
   icon (element) / phone (class) / big (modifier)
   ```
   
    
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
 
 * Use undercase "_" to join two words for names
 
   Example
   ```
   guest-name

   sign-up
   ```
  
  
  
  
  
