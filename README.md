# Build a Markdown Previewer

This JavaScript code is an implementation of a basic web application using the React library. The application consists of two main areas: an editing area (text editor) and a preview area. The main purpose is to allow users to input text formatted with Markdown-style in the editor, and then display a rendered preview of the formatted text in the preview area.

Below, I provide you with a detailed explanation of the code.

![Captura](https://github.com/AndresF-SanchezG/challenge2-react/assets/113924667/89030151-1f8f-44ae-ac18-c617c65bfb76)


In these lines, the necessary libraries are imported: React, ReactDOM (for rendering the application to the DOM), and marked (a library for converting Markdown text into renderable HTML).

Clase MyForm:
![Captura1](https://github.com/AndresF-SanchezG/challenge2-react/assets/113924667/6a1ff16b-c082-4d52-bd67-7db755eebbc1)


A class named MyForm is defined, which extends React.Component, indicating that this class represents a React component.

Constructor:
![Captura3](https://github.com/AndresF-SanchezG/challenge2-react/assets/113924667/501c75b0-371c-42be-863c-ae0798747493)


In the constructor, the component's state is initialized. The state contains a field called textarea which holds an example of Markdown text. The handleChange function is also bound to the current component.

handleChange:
![Captura4](https://github.com/AndresF-SanchezG/challenge2-react/assets/113924667/d191a124-819a-44cf-bf90-bb020d87991f)


handleChange is a function that updates the textarea state with the content of the editing textarea when it changes.


Rendering Method:
![Captura5](https://github.com/AndresF-SanchezG/challenge2-react/assets/113924667/12785af1-b89c-4d1d-9f9d-ea8b29cae05c)


In the render method, the user interface structure is returned. There are two main sections:

Editor: A textarea element that displays the current content of the textarea state and updates when changes occur.

Preview: A div element with the rendered content of the textarea state using the dangerouslySetInnerHTML function. The marked function converts Markdown text to HTML and is rendered within this element.

Initial Rendering:
Finally, the MyForm component is rendered into the DOM element with the ID 'root'. This is what makes the application appear on the web page.


![Captura5](https://github.com/AndresF-SanchezG/challenge2-react/assets/113924667/b33434fb-a9f4-46f1-b348-db29831d5281)

In summary, this code implements a basic web application that allows users to input and edit Markdown-formatted text and see a real-time rendered preview.


# Solution Challenge
In this challenge I tried to get as close as possible to your solution:
- Live Site URL: [Codepen](https://codepen.io/Andr-s-Fernando-Sanchez-Galarza/pen/XWxwKEg)
  
# Author

- Author - [@AndresF-SanchezG](https://github.com/AndresF-SanchezG)
- School - [Freecodecamp](https://www.freecodecamp.org/)
- Curse - [Build a Markdown Previewer](https://www.freecodecamp.org/learn/front-end-development-libraries/front-end-development-libraries-projects/build-a-markdown-previewer)


