# React Typing Animation
React Typing Animation is a React component that simulates real-time typing of text. It's perfect for adding a touch of dynamism to your pages, especially if you want to highlight titles or slogans.

How to Use
To get started, simply import the Presentation component and add it to your JSX code:

jsx

## import Typewriter from 'react-typing-animation';

```javascript
function App() {
  return (
    <div>
      <Typewriter />
      <h2>Your text here</h2>
      <p>More text</p>
    </div>
  );
}
```
You can customize the typed text as well as the speed and pause between animations using the data-rotate and data-period props. For example:

jsx

```javascript
<Typewriter
  data-rotate='["Lorem ipsum dolor1.", "Lorem ipsum dolor2.", "Lorem ipsum dolor3"]'
  data-period="3000"
/>
```

/>
This component is based on pure JavaScript and React Hooks, so you don't need to add any extra dependencies to your project.

# How to Install and Run the Application
This is a guide to help you install and run the application.

## Prerequisites
Before proceeding, make sure you have Node.js and Yarn installed on your machine. You can download them at https://nodejs.org/en/download/ and https://classic.yarnpkg.com/en/docs/install/, respectively.

## Installation
Open the terminal and navigate to the project folder.

Install the dependencies with the command:

bash
`yarn install`

Running the Application
Start the development server with the command:

bash
`yarn run dev`


Access the application in your browser through the link http://127.0.0.1:5174/

Now you have the application up and running and you can start using it. Remember that to stop the development server, simply press CTRL + C in the terminal.
