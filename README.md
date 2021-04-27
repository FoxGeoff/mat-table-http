# MatTableHttp

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 11.2.6.

## Kanban Task: Setup Project

1. Add. Angular Material
2. HOW TO FIX ERROR: <https://www.thecodebuzz.com/angular-null-injector-error-no-provider-for-httpclient/>

```TypeScript
/**
 * Ref https://www.thecodebuzz.com/angular-null-injector-error-no-provider-for-httpclient/
 */
ERROR NullInjectorError: R3InjectorError(AppModule)[HttpClient -> HttpClient -> HttpClient]: 
  NullInjectorError: No provider for HttpClient!
    Angular 9
    TableHttpExampleComponent_Factory table-http-example.component.ts:16
    Angular 5
    AppComponent_Template app.component.html:1
    Angular 20
core.js:6210
    Angular 1
```

1. REMEMBER TO RESTART SEVER AFTER ADDING MATERIAL MODULE
