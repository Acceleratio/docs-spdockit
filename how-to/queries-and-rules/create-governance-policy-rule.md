---
title: Create SharePoint Governance Policy Rule
slug: create-governance-policy-rule
---

# Create SharePoint Governance Policy Rule

This section describes how to use the SPDocKit wizard to create a rule to help you enforce your governance policies. We will now create a rule that will enforce that all document libraries require checkout.

1. Go to __Queries & Rules__ on the navigation bar and click __New Rule__ on the Home ribbon.

1. Select the rule type. Available rule type depends on the selected scope: list or subsite.

   Rule name will, by default, be the same as the rule type, but you can edit that later. Click Next to continue. Read more about supported rule types.

1. Under Rule Configuration, select Yes to require documents to be checked out before they can be edited. Click Next to continue.

1. Define how your rule will be executed. You can choose between the manual or the automatic option.
   * __Manual execution__ – you will have to start this rule from the Home ribbon using the Run button every time you want to enforce the selected policy.
   * __Automatic execution__ – requires an active SPDocKit Service and defined  scheduling options.

   If the SPDocKit service is not running, a warning bar will appear. Click Configure to enable the SPDocKit Service.

1. Use filters to enforce your rule on SharePoint document libraries only. Select the List Template as a filtering condition, click the underlined value “specific” and choose Document library as a preferred template. Click Next to continue.

1. Define the extent to which you wish to enforce this rule across your SharePoint farm. You can target __the entire web application or specific site collections, subsites, lists and list items__. Each time the rule runs, it will configure that all document libraries from the specified scope require document check-out before editing.

   If you have chosen the manual execution in the previous steps, you can skip this step – select the Skip target selection; ask me on execution checkbox. You will be able to choose the desired scope each time you start the rule.

1. Click Finish to close the Rule Wizard.

1. Run this rule right away or wait for the scheduled time for the rule to run automatically, after which you can explore the results. Each time you or the SPDocKit Service executes a rule, a history record is created. Click on the desired record and explore which changes, and where, were made on that particular day.


#### Tips & tricks

SPDocKit comes with a couple of predefined manual rules: Document Library Checkout Required and Document Library Version History. Also, you can edit their definitions to make them better suit your needs.