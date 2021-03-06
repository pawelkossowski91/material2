Angular Material comes packaged with Angular CLI schematics to make
creating Material applications easier.

## Install Schematics
Schematics come packaged with Angular Material, so once you have
installed the npm package, they will be available via the Angular CLI.

Using the command below will automatically install Angular Material for you
and run the install schematic.

```
ng add @angular/material
```

The install schematic will help you to quickly add Material to a new project. 
This schematic will:

- Ensure project dependencies are placed in `package.json`
- Ensure project dependencies are placed in your app module
- Add Prebuilt or Setup Custom Theme
- Add Roboto fonts to your index.html
- Apply simple CSS reset to body


## Generator Schematics
In addition to the install schematic, Angular Material has three schematics it comes packaged with:

- Navigation
- Dashboard
- Table

### Navigation Schematic
The navigation schematic will create a new component that includes
a toolbar with the app name and a responsive side nav based on Material
breakpoints.

```
ng generate @angular/material:material-nav --name <component-name>
```

### Dashboard Schematic
The dashboard schematic will create a new component that contains
a dynamic grid list of cards.

```
ng generate @angular/material:material-dashboard --name <component-name>
```

### Table Schematic
The table schematic will create a new table component pre-configured
with a datasource for sorting and pagination.

```
ng generate @angular/material:material-table --name <component-name>
```
