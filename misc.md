## Miscellaneous Vue notes 

#### Background: 
- Isolated to the view layer - no assuption of middleware or backend 
    - Easy integration 
- Lightweight library, fast page loading 
- Frameworks abstract the interaction between the browser and the DOM. 
    - Declaratively define and interact w/ DOM elements instead of referencing directly 
    - ex: using C instead of Assembly language to write system programs 
- Popularity linked to the rise of the Laravel PHP web app framework, but also prominent in other dev communities 
- Two core libraries: `vue-router` and `vuex` 
    - Relatively stable re: framework updates 

##### Differences from `React`
- `Vue` borrows the concept of the virtual DOM from `React`. 
- Out of the box, Vue doesn't re-render children of an affected component if they aren't affected by a given state change 
- `JSX` isn't a popular approach in `Vue` 
    - Any `HTML` file is a valid Vue template 
    - Easier learning curve for people coming from `HTML`-only (e.g. designers), `Angular`, or `Ember` backgrounds 
- `Vuex` - state management library for `Vue` 
    - Follows `Flux` architecture, similar to `Redux` 
    - `Redux` compatible with Vue, but `Vuex` is specially tailored 
- Indie project, not tied to large company 



```JavaScript
import Vue from 'vue'
```
- `Vue` is the main class of the framework 
```Javascript 
import App from './App'
```
- `App` is the root component of the application 

Key concepts: 
- Reactive interfaces 
- Declarative rendering 
- Data binding 
- Directives 
- Template logic 
- Components 
- Event handling 
- Computed properties 
- CSS transitions and animations 
- Filters 

#### Terminology 
- Progressive framework - framework that adapts to the needs of the developer 

#### Sources 
- [`Vue.js 2` Quickstart Tutorial 2017 - Sebastian Eschweiler](https:/https://www.youtube.com/watch?v=z6hQqgvGI4Y/medium.com/codingthesmartway-com-blog/vue-js-2-quickstart-tutorial-2017-246195cfbdd2)
- [`Vue.js 2.0` in 60 minutes - Traversy Media](https://www.youtube.com/watch?v=z6hQqgvGI4Y)
- Vue Handbook 