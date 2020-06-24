## What is the AEM SPA Editor JS SDK?

In short, the SPA Editor JS SDK is a collection of open source JavaScript libraries that provide a framework for allowing authors to edit the contents of a Single Page Application deployed in AEM. AEM delivers the content in the form of JSON and the SPA Editor JS SDK maps the JSON to React components. Please read SPA Editor Overview for a more comprehensive view into how the SPA Editor works. 

# The AEM SPA Editor JS SDK is made available via three NPM modules:

    @adobe/cq-spa-component-mapping - provides helpers to map AEM Components to SPA components. This module is not tied to a specific SPA framework.

    @adobe/cq-spa-page-model-manager - provides the API to manage the model representation of the AEM Pages that are used to compose a SPA. This module is not tied to a specific SPA framework.
    
    @adobe/cq-react-editable-components - provides generic React helpers and components to support AEM authoring. This module also wraps the cq-spa-page-model-manager and cq-spa-component-mapping to make these available to the React framework.
