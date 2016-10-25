# template-content-store
Prototype content repo for new Template Repository service.
___
Hierarchical collection of email templates used within the FamilySearch ecosystem.

__Directory structure__:
	/template-store/{template-name}/{version}/
  
A template directory (folder) will typically hold:
* Primary Velocity template, name: {template-name}.vm
* Secondary Velocity templates (common content included from a primary template), name: {sub-template}-{template-name}.vm
* Language specific resource bundles, name format: bundle-{template-name}.{language-id}
  
