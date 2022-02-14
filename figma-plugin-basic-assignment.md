![image](https://github.com/six7/style-swap/blob/main/coverart.png?raw=true)
# Assessment: Figma Plugin Basics
The assignment has been designed to assess the following skills:
- Git basics and collaboration using fork and pull-requests
- Familiarising yourself with an existing code base
- Making a contribution to an existing project
- Documenting your work
- Basic understanding of Figma Plugin development
- Ability to work with the Figma API
- Ability to create a simple UI

## Assignment
Before you start, have a look at the following figma plugin:

- **plugin**: https://www.figma.com/community/plugin/1067092321907268578
- **repository**: https://github.com/six7/style-swap

### Current state
We have already developed a part of the logic. Currently the plug-in is parameters only, which means it does not have a dedicated UI. 
The plugin accepts and old and new styleName and replaces the style on all matching elements.

### Changes to be implemented
To improve the plugin, you will add a simple UI with the following elements:
- A text area that allows the user to paste a json object
- A validation/help text for the text area
- An 'update styles' button

Further, you will update the logic with the following features:
- On pasting something in the textarea, you validate the input to make sure it contains valid JSON data
- We are expecting a json object that holds an n number of pairs of oldStyle and newStyle key/value pairs.
- On clicking 'update styles', update all the old styles with the new styles for all elements on the current figma page.
- show a success message and the number of nodes that got updated.

### Submitting your assignment
Once you are done, create a pull request and send me an email with a link to your pull request.
