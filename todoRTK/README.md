# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.


## import configureStore method from reduxjs/toolkit
## export it by 
``
export const store = configureStore({})
``
## then createSlice and initialState 
## import method createSlice and then write down initialState it is an object 
## syntax is const initialState = { todo : [{id:1,msg:hello}]} means initially how your store will look like
## then write createSlice method with name , initialstate and reducers in it and then export them  

## dispatch reducer ko use krty hoay store mein value change krta hai 

systax is like this:

## dispatch comes from useDispatch()
## addTodo is reducer through which dispatch do changes in it with using hte useState hook

dispatch(addTodo(input))


