## REST web services

SODA is using the [restful](https://www.drupal.org/project/restful) module to offer an 
HTTP [REST](https://en.wikipedia.org/wiki/Representational_state_transfer) API of its data.

Beyond other we decided to go with the **restful module** and not with other, older Drupal projects 
([services](https://www.drupal.org/project/services), [restws](https://www.drupal.org/project/restws), 
[contentapi](https://www.drupal.org/project/contentapi), [rest_json](https://www.drupal.org/project/rest_json) etc) 
because it was the only one that was satisfying our needs for true REST API as it was declared by 
[Roy Fielding](https://www.ics.uci.edu/~fielding/pubs/dissertation/top.htm) on 2000.

These requirements are:

- **REST settings per dataset**. We wanted to have full control of what data would be exposed with the REST API.
Using restful module we are able to create our REST API as we like with multiple version apis per endpoint.
- **Autodiscovery**. API should allow any requester to find what resources are available.
- Allow for several **request formatters** (xml, json etc) which are also extensible.
- Allow for several **request parsers** (xml, json etc) which are also extensible.
- **Templated requests**.
- **Flexible** as much as possible (eg create the path of the resource as we like).
- **Use Drupal best practices** (hooks, cache, template engine, validations etc) to simplify things.
- **Easy to maintain** (restful module is using Ctools plugins from plain files).
- **Drupal UI (TODO)**.
- Allow for custom permissions and data access restrictions.
- Provide **cached requests**.
- Being fast, solid and reliable.

## Consuming the REST API

With restful module you are able to consume the HTTP REST API using best practices. 

Please find more at the [Restful module wiki](https://github.com/RESTful-Drupal/restful/wiki).

## Browse the REST API

**TODO**

SODA is exposing the resources using a [Swagger interface](http://swagger.io/). This way you can explore the API 
directly from the browser.

## REST API examples

**TODO**

- OPTIONS example (get field settings)
- GET examples (api version, fields, page, filtering, alternative formatter, sort, range, alternative id, 
- POST examples (js, php, within Drupal, ruby, python, with browser extension)
- PUT examples
- PATCH examples
- DELETE examples (delete an endpoint)
- Authentications methods

## HowTo videos

**TODO**

- Create a restful plugin (within Drupal).
- Consume the REST API (examples).
- Restful best practices.

