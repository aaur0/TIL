### Component
<br/>
The Component is the most fundamental of Angular concepts. A component manages a view - a piece of the web page 
where we display information to the user and respond to user feedback. Technically, a component is a class that controls a view template. 
A class becomes an Angular component when we give it metadata. Angular needs the metadata to understand how to construct the view and how the component interacts with other parts of the application.

```javascript
import {Component} from 'angular2/core';

@Component({
    selector: 'my-app',
    template: '<h1>My First Angular 2 App</h1>'
})
export class AppComponent { }
```

### Modules

<br/>
Angular apps are modular. They consist of many files each dedicated to a purpose.

```javascript

export class AppComponent { }

```

The act of exporting turns the file into a module. The name of the file (without extension) is usually the name of the module.



select substr(date_string_p,6,2) month, account_name, campaign_name, sum(clicks), sum(adspend), sum(revenue_v1), sum
(revenue_v2), sum(revenue_v3) from daily_kgl_traffic_revenue where date_string_p between '2015-02-01' and 
'2016-01-31' group by substr(date_string_p,6,2), account_name, campaign_name;