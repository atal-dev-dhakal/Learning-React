# Learning-React

## Day 1 - Basics of React, why use it and JSX.
- Refreshed the knowledge of js.
- Learnt new things possible in vanilla js like manipulating contents in html file without using inner HTML.
- Imperative (tell the computer exactly how to do) vs Declarative (tell the computer what to do) programming - This is one important reason why we use React.
- JSX, a syntax -perhaps more than just a syntax that allows us to get the directive script in the form of JS objects- that makes the job easier. JSX retuns normal js objects under the hood but looks like html.
- Learnt what difference does the DOM render make - compared to the other ways like trying to append js variable to the HTML element.

## Day 2 - Set up React App
- React components (Function that returns React elements) and React elements (Objects that get created when we return JSX).
- Set up Local React environment with Create React App and learnt how to use it.
- Basics of working with files, connecting to one another, some changes needed in switching from React 17 to React 18 and working with directories.

## Day 3 - Figma
- Created an account and played with the tools around a little. The basic layout of the current webpage was designed.

## Day 4,5,6,7,8,9,10,11,12,13,14,15 - Got busy with other stuff. React became low in priority, especially because of research and interviews.

## Day 16 - Restarting
- Took a while to gather everything up again. Did a task too. Now ready to continue learning.
- Got back to the same YouTube tutorial. Create a new project too. All the learning will happen there.

## Day 17 
- index.html -> Only for root. | index.js -> Contains App component (renders this) and imports index.css (importing only here works. No need to import on other files that might use CSS). | App.js -> Contains other components. | index.css -> import the google fonts here.

## Day 18
- Set up Github Deskotop. Created two repositories for react project 1 (react facts) and project 2 (business card).
- Worked on that project 2, completed it and published the repo.
  
## Day 19 
- Created project 3 (airbnb replica) and worked on it.
- Complete the project part. Used figma to see the design specifications and then coded.

## Day 20
- Started learning props. Worked on the tasks from the tutorial.

## Day 21
- Destructuring props.

## Day 22
- Conditional rendering the props.

## Day 23
- Map method and shorthand for a function.

## Day 24
- Started UX course on Domestika.

## Day 25
- Continued and completed the UX course on Domestika.
- Continued learning about map method and higher-order functions in JS.

## Day 26
- More about functions in js.

## Day 27
- Learnt basics of Figma.

## Day 28 
- Continued learning methods in JS: Map, Filter and Reduce.

## Day 29
- Made a duolingo replica on figma.

## Day 30
- Continued react course.

## Day 31
- Learnt speread and rest operator in js.
- Very helpful tool to simplify the code. Now, instead of doing:


| Instead of this                                                    | We can do this             |
|--------------------------------------------------------------------|----------------------------|
|  return (                                                          |  return (                  |
|  <div >                                                             |    <div >                   |
|    data.map((x)=>{                                                 |      data.map((x)=>{       |
|      <Card                                                         |      return <Card          |
|            key= {x.id}                                             |             {...x}         |
|            pic={x.pic}                                             |             />}            |
|            rating ={x.rating}                                      |    </div >)                 |
|            country = {x.country}                                   |                            |
|            descriptionText = {x.descriptionText}                   |                            |
|            price = {x.price}                                       |                            |
|            openSpots={x.openSpots}                                 |                            |
|      />}                                                           |                            |
|  </div >)                                                           |                            |
