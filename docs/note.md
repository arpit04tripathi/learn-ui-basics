# Note

Read section 3 - How CSS works

## 3 Pillars of Good HTML and CSS
1. Responsive Design
2. Maintenance and Scalable
3. Web Performance

### Responsive Design
- Fluid Layouts
- Media queries
- Responsive images
- correct units
- desktop-first vs mobile-first

### Maintenance and Scalable
- clean
- easy to understand
- growth
- reusable
- how to organize files
- how to name classes
- how to structure html

### Web Performance
- Less http requests
- less code
- compress code
- use a css preprocessor
- less images
- compress images

## CSS Specificity
```
Importance > Specificity > Source Order
```

### Importance
- user `!important` declarations
- author `!important` declarations
- author declarations
- user declarations
- default browser declarations

### Specificity
- inline styles
- IDs
- classes, pseudo-classes, attribute
- elements, pseudo-elements

### Source Order
- The last declaration in the code will override all other declarations and will be applied.

***NOTE*** : Always put your author stylesheet last when using third partly stylesheets