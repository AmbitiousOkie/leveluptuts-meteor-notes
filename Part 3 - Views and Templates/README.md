# Part 3
## Views and Templates

Start your Meteor application by changing to the "resolution" meteor folder and running the command
> meteor

Now connect to [localhost:3000](http://localhost:3000).

## Changes

In this section, we've made some changes to the default files. Changes include:

1. Clearing out all client side data and functions inside of resolutions.js
2. Added a template helper with a premade array of objects to resolutions.js
3. Modified the template "hello" to read as "resolution"
4. Created an unordered list in the body
5. Iterated through the array of objects found in resolutions.js in the unordered list
6. Displayed the "resolution" template in each iteration of the array objects

## Concepts

For each loop - iterates through the resolutions array for each object found
```
{{#each resolutions}}
	<p>Do something</p>
{{/each}}
```

Insert a template - inserts the named template
```
{{> resolutions}}
```

Template - creates a template that can be reused
```
<template name="resolution">
	<li>{{title}}</li>
</template>
```



Video: https://www.youtube.com/watch?v=nF5CRSEC8PA&list=PLLnpHn493BHECNl9I8gwos-hEfFrer7TV&index=5

Visit http://leveluptuts.com/tutorials/meteor-for-everyone for all the videos

