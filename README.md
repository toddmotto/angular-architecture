<h1 align="center">
<img width="40" valign="bottom" src="https://angular.io/assets/images/logos/angular/angular.svg">
Angular Architecture Guide
</h1>
<h5 align="center">A cohesive guide for building Angular applications for teams.</h5>

<p align="center">:warning: Work In Progress :warning:</p>

## Folder Structure

```
index.html
app/
│    app.component.scss
│    app.component.spec.ts
│    app.component.ts
│    app.module.ts
└──  meal-planner/
   │         meal-planner.module.ts
   │         meal-planner.service.spec.ts
   │         meal-planner.service.ts
   ├── components/
   │         meal-viewer/
   │             meal-viewer.component.scss
   │             meal-viewer.component.spec.ts
   │             meal-viewer.component.ts
   │         meal-editor/
   │             meal-editor.component.scss
   │             meal-editor.component.spec.ts
   │             meal-editor.component.ts
   │         meal-recipe/
   │             meal-recipe.component.scss
   │             meal-recipe.component.spec.ts
   │             meal-recipe.component.ts
   ├── containers/
   │         meal-planner/
   │             meal-planner.component.scss
   │             meal-planner.component.spec.ts
   │             meal-planner.component.ts
   └── models/
              meal.interface.ts
              recipe.interface.ts
```

## Stuff I wanna include

* Root + feature module architecture
* Directory structure
* TypeScript models/interfaces

* CSS options (Sass/etc)
* Component architecture
* Container + Presentational components
* State management (ngrx/store etc)
* Route configuration
* Structure practices (maybe lifecycle hooks/DI practices)
* Tooling (AoT/Webpack/etc)
* Build process info (platforms)
* Resources section
