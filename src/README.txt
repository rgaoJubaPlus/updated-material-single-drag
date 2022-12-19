Assignment:
  Create a custom dashboard with:
    -Angular 11 (NOTE: used v12 because StackBlitz loads it by default),
    -Angular Material, 
    -and SCSS.


Criteria:
  Include one parent component, a module w/ routing that has two components to be used as children components.

  Parent component must wrap the two children component in the app-routing module.
  Children components must be lazy-loaded from their respective module

  One child component must be a dashboard that is completely styled however you'd like (create as many sub components as you feel necessary to create this page)
  Second child component doesn't need content or styling, but is to just show routing between pages

  Must include angular material style overrides.

  Must include a well structured root set of styles. 

  This could include:
    -Typography
    -Angular Material Component overrides
    -Mixins, Functions, Variables, etc.
    -Browser/style resets (if necessary)
    -Anything else you'd find useful to have within your base set of styles.

  Create a service that sends back mock data as an observable that the dashboard can subscribe to, to render data to the user.

  Data must be given an interface to follow
  Everything must be WCAG 2.0 AAA Compliant