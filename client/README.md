## Create a vite project by
npm create vite@ latest
project name: client("Your_Wish")
Framework: React
Variant: JavaScript
linter to use : ESlint

## Comment which install necessaries..
cd client
npm install

## To Navigate to different pages 
# install react-router-dom
npm install react-router-dom

## run the project 
npm run dev

## Use rafce
To get the component structure of React
This is only work if you have extension: 
ES7 React/Redux/GraphQL/React-Native snippets
in VS code

## index.html file

used for Titel and logo settings

## Folder Structure
client
  |
  |----components

  |----pages

  |----context

  |----asserts
  |----
  |

## To use Tailwind css in vite

npm install tailwindcss @tailwindcss/vite

result - vite.config.js file
inside vite.config.js
import tailwindcss for vite by using comment

import tailwindcss from '@tailwindcss/vite'
inside plugins array add
tailwindcss()

## using google fonts 
go to google font website 
search outfit
grt embedded code
copy paste the code inside index.css
