---
title: "The React useEffect Hook"
excerpt: "The useState hook in React is used in functional components to synchronize the component with an external system. useEffect fetches data after component mount in a React functional component. The empty dependency array ensures it runs once. Optional cleanup handles unmounting."
coverImage: "/assets/blog/laptop/laptop.jpg"
date: "2023-12-30T17:07:43.722Z"
author:
  name: Jai Gokhale
  picture: "/assets/blog/authors/jg.png"
ogImage:
  url: "/assets/blog/laptop/laptop.jpg"
---

The useEffect hook is a feature in React, a JavaScript library for building user interfaces. It is used to perform side effects in functional components.

Side effects may include data fetching, subscriptions, manual DOM manipulations, and more. useEffect accepts a function that contains the code for the side effect, and it runs after the component renders.

It's commonly used for tasks like fetching data from an API or setting up event listeners. Additionally, useEffect can return a cleanup function to handle any necessary cleanup when the component unmounts or when dependencies change.

If the useEffect hook is dependent on a parameter (variable or state), it can be configured to re-run every time the parameter changes. This can be achieved by using the dependency array, and listing the parameter. React will watch for changes in the parameter and trigger the useEffect function to run whenever there is a change.

Be careful, do not list the parameter in the dependecy array if you are setting the state of that parameter within the useEffect hook, or else you will create an endless loop. This is particularily important when interacting with APIs.

[Check out my new Instagram post for more details](https://www.instagram.com/p/C1m_m4_u04T/?img_index=1)
