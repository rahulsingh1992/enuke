# enuke
Contains Assignment of Enuke

# Assignments

1. Marco Polo
	: Simple java script code embded with marco_polo.html in marco_polo_game directory. Just click & run on the browser.

2. scope limitation of any angularJS directive can be done by isolated scope concept.
	following are the two ways:
	1. Scope : true ( new scope )
	2. Scope : { } ( isolated scope )

	If we want to use isolated scope for a perticular directive in that case we limit the scope, isolated scope will not be inherited from the parent scope.

	app.directive("customdirective", function(){
	    return {
	        restrict: "EA",
	        scope: {},
	        template: "<div> Here is the name : {{value}}</div>"+
	        "update name name : <input type='text' ng-model='value'/>"
	    };
	});

	We have 3 types of prefixes for isolated scopes : 
	1. "@"   ( one-way binding )
	2. "="   ( two-way binding )
	3. "&"   ( Method binding  )

3. Implementing a User Story
	: All the code for this story is in "Implementing a User Story" folder
	: you need to run only index.html
	: After opeaning index.html "Choose file" element will appear, user have to select valid ascii file as input
	: Output will display after selecting input file on same page.
	: all the js(directive, service and controller) is in js folder.

	Test case:
		: input file "input_user_story_1.txt".
		: see the output just after uploading the input file.
	


