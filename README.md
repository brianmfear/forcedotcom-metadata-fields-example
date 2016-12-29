# forcedotcom-metadata-fields-example
An example made for [question 153621](http://salesforce.stackexchange.com/questions/153621) on the Salesforce StackExchange.

To use this example in the [Salesforce Workbench](https://workbench.developerforce.com), download this repository to your computer, ZIP the contents of the src folder, and then use the "deploy" option in the "migration" menu.

To deploy the same field to other objects, simply copy the objects/Account.object file so it matches the API name of the object (e.g. Case or MyCustomObject__c). If you want to use other standard objects, you must remember to modify src/package.xml to include the standard object.
