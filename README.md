# Cursor

## Props
``` 
element: HTMLElement, 
box: HTMLElement,
tag: HTMLElement,
className: string,
elementsHover: {
   [key: string]: {
    enter: (e, cursor) => void,
    move: (e, cursor) => void,
    leave: (e, cursor) => void,
  } 
},
timout: number,
```

- tag курсор html tag
- box где работает курсор
- className класс для слздания событий ```className--hidden, className--down, className--hover```
- timout задержка событй
- elementsHover key передается CSS-селектору, события на блоке:
    - enter нажатия мыши
    - move движение блока
    - leave покидание блока
  
