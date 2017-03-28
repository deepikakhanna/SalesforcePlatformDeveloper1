//http://mytutorialrack.com/
//Check the complete course here https://mytutorialrack.com/salesforce-platform-developer-1-certification-course/

APEX_Customer__c objCust = new APEX_Customer__C();
objCust.Name = 'Test ABC';

//DML for Inserting the new Customer Records
insert objCust;
	
//Inserting the New Records using insert DML statement
APEX_Invoice__c objNewInvoice = new APEX_Invoice__c();
objNewInvoice.APEX_Status__c = 'Pending';
objNewInvoice.APEX_Amount_Paid__c = 1000;
objNewInvoice.APEX_Customer__c = objCust.id;

//DML which is creating the new Invoice record which will be linked with newly created Customer record
insert objNewInvoice;
System.debug('the customer we added '+objCust+' and the corresponding invoice for the customer:'+objNewInvoice);
