# template-content-store
Prototype content repo for new Template Repository service.
___
Hierarchical collection of email templates used within the FamilySearch ecosystem.

__Directory structure__:
	/template-store/{template-name}/{version}/
  
A template directory (folder) will typically hold:
* Primary Mustache template, name: {template-name}.mustache
* Secondary Mustache templates (common content included from a primary template), name: {sub-template}.mustache
* Language specific resource bundles, name format: {language-id}.property
  
