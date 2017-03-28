//http://mytutorialrack.com/
//Check the complete course here https://mytutorialrack.com/salesforce-platform-developer-1-certification-course/
//Restore the deleted customers
List<apex_customer__c> fetchDelCustomers = [SELECT id FROM apex_customer__c WHERE apex_customer__c.Name LIKE 'Test%' ALL ROWS];

//DML Statement to delete the Invoices
undelete fetchDelCustomers;
System.debug('Success, '+fetchDelCustomers.size()+' Records has been restored');
