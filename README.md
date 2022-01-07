[comment]: # "Auto-generated SOAR connector documentation"
# IFTTT \- Maker Channel

Publisher: Ryan Kranz  
Connector Version: 1\.1\.0  
Product Vendor: IFTTT  
Product Name: IFTTT \- Maker Channel  
Product Version Supported (regex): "\.\*"  
Minimum Product Version: 3\.0\.190  

IFTTT Maker Channel connector


This app allows arbitrary automation within IFTTT

### Suggested Use-cases

For Example:

-   Send and SMS Message to the SOC manager.

### Future Features

### Requirement

### References


### Configuration Variables
The below configuration variables are required for this Connector to operate.  These variables are specified when configuring a IFTTT \- Maker Channel asset in SOAR.

VARIABLE | REQUIRED | TYPE | DESCRIPTION
-------- | -------- | ---- | -----------
**api\_key** |  required  | string | Maker Channel API Key

### Supported Actions  
[test connectivity](#action-test-connectivity) - Validate the asset configuration for connectivity\.  
[run action](#action-run-action) - Trigger an ifttt action \(via the Maker Channel\)  
[send message](#action-send-message) - Send and SMS message via send\_sms\_message IFTTT Maker Channel event  
[upload file](#action-upload-file) - Save Container details to Google Drive  

## action: 'test connectivity'
Validate the asset configuration for connectivity\.

Type: **test**  
Read only: **True**

#### Action Parameters
No parameters are required for this action

#### Action Output
No Output  

## action: 'run action'
Trigger an ifttt action \(via the Maker Channel\)

Type: **generic**  
Read only: **True**

#### Action Parameters
PARAMETER | REQUIRED | DESCRIPTION | TYPE | CONTAINS
--------- | -------- | ----------- | ---- | --------
**action** |  required  | Name of Action/Event to trigger\. | string | 
**value1** |  optional  | First Optional Value | string | 
**value2** |  optional  | Second Optional Value | string | 
**value3** |  optional  | Third Optional Value | string | 

#### Action Output
No Output  

## action: 'send message'
Send and SMS message via send\_sms\_message IFTTT Maker Channel event

Type: **generic**  
Read only: **True**

#### Action Parameters
PARAMETER | REQUIRED | DESCRIPTION | TYPE | CONTAINS
--------- | -------- | ----------- | ---- | --------
**message\_title** |  optional  | Message Title | string | 
**message** |  optional  | Message Text | string | 

#### Action Output
No Output  

## action: 'upload file'
Save Container details to Google Drive

Type: **generic**  
Read only: **True**

#### Action Parameters
PARAMETER | REQUIRED | DESCRIPTION | TYPE | CONTAINS
--------- | -------- | ----------- | ---- | --------
**value1** |  optional  | Field 1 \(Optional\) | string | 
**value2** |  optional  | Field 2 \(Optional\) | string | 
**value3** |  optional  | Field 3 \(Optional\) | string | 

#### Action Output
No Output