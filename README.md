# repo-95-reactjs-basics
here im explaining the basics of react in my own way

# reactjs basics
* react is an front-end library , if u open a website , the page u seeing is called frontend 
* it was used to build single page application
* it was maintained by facebook

## advantages:
* less traffic
* user internet consuming will be less

# Basics:
1. Components    
- **i.e  part of page or some specific conetent , we can divide the components in anyway posible , we can simply same , if u click on the component , total website doesnt rerender , only component will rerender**

2. Props
- **i.e take an component , if u want to send data from outside to component called props
- for reusablity we use props
- 
3. State 
- **i.e if u want to create a data inside the component , and manipulate , and want to show them called state
- we use this state for SPA (single page application things)

* prop and state both are data
- prop will come from outside
- state it will only inside the component

## Components are 2 types 
1. class based component (we will create javascript class and we wil render componenets)
* inside the classes , there will be state inbuilt

2. function based component (we will create functions and we will render them)
* inside the clases , there is no inbuilt state , so we use hooks concept , then we will achive state
* hooks are special type of functions
* note: basically react community found that , many developers are using the functions , so in functions we dont have state , so they created hooks , and hooks also a function

## steps to install react.js
* type "node js" in google
* https://nodejs.org/en/download/current
* download only LTS (long term support) while downloading for better
* donwload and install (click on addtopath while installing)
* in cmd type node it will show wheather it was installed ot not

## vscode
* create a folder and 
* npx create-react-app react-basics in your terminal


- while running above command in cmd ,  if u get this belowerror:
- C:\Users\poppo\Desktop\github ai\end to end by vivek\repo-95-reactjs-basics>npx create-react-app react-basics
npm ERR! code ENOENT
npm ERR! syscall lstat
npm ERR! path C:\Users\poppo\AppData\Roaming\npm
npm ERR! errno -4058
npm ERR! enoent ENOENT: no such file or directory, lstat 'C:\Users\poppo\AppData\Roaming\npm'
npm ERR! enoent This is related to npm not being able to fi
npm ERR! A complete log of this run can be found in:**

* if u facing above error : u can try 2 methods

1. ## first method: 
* npm install -g npm@latest
- This will reinstall npm globally on your system

2. ## second method:

- Check Environment Variables (if the above solution doesn't work):
        Search for "environment variables" in your system settings.
        Ensure that the PATH variable includes the directory where npm is installed. Typically, it's something like C:\Program Files\nodejs. You can add the path if it's missing.**


# now install extention in vscode
* ES7+ React/Redux/React-Native snippets

- whats the use of this extention?
* if we want to create CBC (class based component) , we dont need to workhard .
* just "rcc" is enough for class based
* if we want to add constructor just "rcont" (reactconstrucotr)

* just "rfc" is enough for function based

# basically we do , create components and load them that's it
## to start the react:
* cd react-basics 
* npm start

# we can also do our react.js experiments in:
* https://playcode.io/react

## ok now what is jsx?
- JSX is an eligible / compatible html format 
- JSX allows us to write HTML in React. JSX makes it easier to write and add HTML in React
- import React from 'react';

## some points:
- in html forms we have for, but in jsx forms wehave for loop 

export function App(props) {
  return (
    <div className='App'>
      <h1>Hello React.</h1>
      <h2>Start editing to see some magic happen!</h2>
    </div>
  );
}

// Log to console
console.log('Hello console')**

## we can use below website for html to JAX 
- https://transform.tools/html-to-jsx



## basics commands:
'''
  npm start
    Starts the development server.

  npm run build
    Bundles the app into static files for production.

  npm test
    Starts the test runner.

  npm run eject
    Removes this tool and copies build dependencies, configuration files
    and scripts into the app directory. If you do this, you can’t go back!

We suggest that you begin by typing:

  cd react-basics
  npm start

Happy hacking!

'''

## for documentation:
* https://react.dev/learn