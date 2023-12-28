---
title: "React Building Blocks"
excerpt: "React functional components have become the preferred approach for buidling react components. Functional components utilize JSX to combine javascript logic, html and css."
coverImage: "/assets/blog/dynamic-routing/cover.jpg"
date: "2023-07-20T05:35:07.322Z"
author:
  name: Jai Gokhale
  picture: "/assets/blog/authors/jj.jpeg"
ogImage:
  url: "/assets/blog/dynamic-routing/cover.jpg"
---

React utilizes funtional components as the building block of React single page applications (SPAs). Functional components have replaced class based components and become the go to approach for building out SPAs.

Functional components were initially introduced as "stateless" components and lacked the ability to manage their own state. At the time of it's introduction, a class based component was preffered for managing state. With the introduction of React hooks, functional components were able to manage state and perform all of the lifecycle actions (when component is renered or tore down) that could previously only be achieved by class based components. These changes in react's ecosystem soon led to functional components being the "go to' component when building react apps.

My personal experience with functional components have been that they are easier to work with and easier to test thatn class based components. Abstracting the logic out of the component into seperate functions allows you to test DOM elements and logic separately and in isolation. From a testing standpoint, this drastically reduces the number of mocks and spies that you would use and provides greater confidence on testing the responsiblilty of components versus functions.

My research on functional components and react in general continues with greater emphasis on react's custom hooks, testing and code reusability. I hope you enjoyed reading a little bit about functional components!
