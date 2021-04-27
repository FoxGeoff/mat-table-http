# MatTableHttp

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 11.2.6.

## Intoduction

1. This project illustrates the use of the Material Table with a common/http data source

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

### Task: FIx Error

```Typescript
ERROR Error: NG0100: ExpressionChangedAfterItHasBeenCheckedError: Expression has changed after it was checked. Previous value: 'undefined'. Current value: '[object Object]'.. Find more at https://angular.io/errors/NG0100
```

1. Ref. <https://stackoverflow.com/questions/43375532/expressionchangedafterithasbeencheckederror-explained>
