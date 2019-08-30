# Actions, Resources, and Condition Keys for Amazon Translate<a name="list_amazontranslate"></a>

Amazon Translate \(service prefix: `translate`\) provides the following service\-specific resources, actions, and condition context keys for use in IAM permission policies\.

References:
+ Learn how to [configure this service](https://docs.aws.amazon.com/translate/latest/dg/)\.
+ View a [list of the API operations available for this service](https://docs.aws.amazon.com/translate/latest/dg/)\.
+ Learn how to protect this service and its resources by [using IAM](https://docs.aws.amazon.com/translate/latest/dg/auth-and-access-control.html) permission policies\.

**Topics**
+ [Actions Defined by Amazon Translate](#amazontranslate-actions-as-permissions)
+ [Resources Defined by Amazon Translate](#amazontranslate-resources-for-iam-policies)
+ [Condition Keys for Amazon Translate](#amazontranslate-policy-keys)

## Actions Defined by Amazon Translate<a name="amazontranslate-actions-as-permissions"></a>

You can specify the following actions in the `Action` element of an IAM policy statement\. Use policies to grant permissions to perform an operation in AWS\. When you use an action in a policy, you usually allow or deny access to the API operation or CLI command with the same name\. However, in some cases, a single action controls access to more than one operation\. Alternatively, some operations require several different actions\.

The **Resource** column indicates whether each action supports resource\-level permissions\. If there is no value for this column, you must specify all resources \("\*"\) in the `Resource` element of your policy statement\. If the column includes a resource type, then you can specify an ARN of that type in a statement with that action\. Required resources are indicated in the table with an asterisk \(\*\)\. If you specify a resource\-level permission ARN in a statement using this action, then it must be of this type\. Some actions support multiple resource types\. If the resource type is optional \(not indicated as required\), then you can choose to use one but not the other\.

For details about the columns in the following table, see [The Actions Table](reference_policies_actions-resources-contextkeys.md#actions_table)\.


****  

| Actions | Description | Access Level | Resource Types \(\*required\) | Condition Keys | Dependent Actions | 
| --- | --- | --- | --- | --- | --- | 
|   [ DeleteTerminology ](https://docs.aws.amazon.com/translate/latest/dg/API_DeleteTerminology.html)  | A synchronous action that deletes a custom terminology\. | Write |  |  |  | 
|   [ GetTerminology ](https://docs.aws.amazon.com/translate/latest/dg/API_GetTerminology.html)  | Retrieves a custom terminology\. | Read |  |  |  | 
|   [ ImportTerminology ](https://docs.aws.amazon.com/translate/latest/dg/API_ImportTerminology.html)  | Creates or updates a custom terminology, depending on whether or not one already exists for the given terminology name\. | Write |  |  |  | 
|   [ ListTerminologies ](https://docs.aws.amazon.com/translate/latest/dg/API_ListTerminologies.html)  | Provides a list of custom terminologies associated with your account\. | Read |  |  |  | 
|   [ TranslateText ](https://docs.aws.amazon.com/translate/latest/dg/API_TranslateText.html)  | Translate text from a source language to a target language\. | Read |  |  |  | 

## Resources Defined by Amazon Translate<a name="amazontranslate-resources-for-iam-policies"></a>

Amazon Translate has no service\-defined resources that can be used as the `Resource` element of an IAM policy statement\.

## Condition Keys for Amazon Translate<a name="amazontranslate-policy-keys"></a>

Translate has no service\-specific context keys that can be used in the `Condition` element of policy statements\. For the list of the global context keys that are available to all services, see [Available Keys for Conditions](reference_policies_condition-keys.html#AvailableKeys) in the *IAM Policy Reference*\.