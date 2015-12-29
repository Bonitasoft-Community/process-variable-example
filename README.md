# process-variable-example

## Description
Example of forms to display and update process variable

## Known limitation
By default only users with administrator profile are allowed to access process variables.
You can change such behavior by customizing dynamic-permissions-checks.properties. Refer to [REST API authorization](http://documentation.bonitasoft.com/rest-api-authorization-0) documentation for more information.
Overview form is not able to disaply process variable value for an archived process instance (lack of REST API).

## Important recommendations
Generally it is recommended to use business variables instead of process variables.
