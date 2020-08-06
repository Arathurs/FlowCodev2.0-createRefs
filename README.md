## Flowcode/React.createRef Version 2.0

### Screenshot:
  ![Screenshot](/public/img/homepage.png/)

#### [Link to Repo](https://github.com/Arathurs/FlowCodev2.0.git/)  

### About the Project

A color flow code which can generate fifty random colors with the click of a button, as well as functionality to select a specific color and display it's rgb value. 

Unlike our previous version which was implemented by rendering dynamic information in the form of nested props or state, we manipulate child component instances from a parent container component using React.createRef().

## Functionalities

  - Display a list of 50 randomc colors which are passed down to presentational components from a container component which stores the all 50 colors and a selected color in it's state.
  - Users can pick a color from the list which will then become the active color. 
  - The element displaying the active color will highlight with a border upon being designated by the user. The active color also will be displayed at the top of the screen in it's rgb form. For example, navy blue would be `rbg(0,0,128)`.
  - Display a 'Reset' button. When this button is clicked, state and therefore the color list is updated, with 50 new colors and any select element will no longer be selected.


### Technologies Used
- React
- React.createRef()
- ReactDOM
- HTML5
- CSS5
