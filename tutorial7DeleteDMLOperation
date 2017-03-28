//http://mytutorialrack.com/
//Check the complete course here https://mytutorialrack.com/salesforce-platform-developer-1-certification-course/

//Deleting the Test customers from Database
//fetch the customers which are created for Testing
List<apex_customer__c> customerListToDel = [SELECT id FROM apex_customer__c WHERE apex_customer__c.Name LIKE 'Test%'];

//DML Statement to delete the Invoices
delete customerListToDel;
System.debug('Success, '+customerListToDel.size()+' Records has been deleted');
