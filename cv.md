# Alexandr Kirichenko

___

## Contacts

- Phone : +380633333333
- Telegram: [@AlexandrKirichenko](https://t.me/AlexandrKirichenko)

___

## About Me

Prolific, full stack web developer with a passion for coding!Passionate about building  web applications.

## Skills:

+ HTML, CSS, SASS
+ JS, OOP
+ React.js,Redux,Typescript,Jest,GraphQL,Apollo
+ Git, bash, webpack

## Experience
**NewTone** (August 2021 - October 2021)  - Frontend developer

## Projects
1.**React mini-shop**
*July 2021*
Lil fruit shop on react
[netlify.app](https://stoic-feynman-e0be24.netlify.app/)

2.**Chat-TS**
*September 2021*
Practice try create chat (React,TS,GQL,Apollo)
[Github](https://github.com/AlexandrKirichenko/Chat-TS)


## Code examples

```React
import { useEffect } from "react";

const useOutsideClick = (ref: any, callback: any) => {
   
   useEffect(() => {
      const handleClick = (e: any) => {
         if (!ref.current || ref.current.contains(e.target)) {
            return;
         }
         callback();
      };
      
      document.addEventListener("mousedown", handleClick);
      
      return () => {
         document.removeEventListener("mousedown", handleClick);
      };
   }, [ref, callback])
};

export default useOutsideClick;
```
## Education
1. [ZarMarathon, React](https://www.zarmarathon.com/) (May 2021)
2. [ZarMarathon, JavaScript](https://www.zarmarathon.com/) (Apr 2021)
3. [React с нуля](https://www.udemy.com/course/react-from-scratch/) (Nov 2020)
5. [React + Redux - Профессиональная Разработка](https://www.udemy.com/course/pro-react-redux/) (March 2020)

## Languages

+ **Russian** - Native
+ **English** - Pre-intermediate
+ **Ukrainian** - Native