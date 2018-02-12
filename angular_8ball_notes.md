Thoughts so far:

1. Angular CLI has specific rules for naming projs that I don't like. I got the following error:

```
Project name "angular-8ball" is not valid. New project names must start with a letter, and must contain only alphanumeric characters or dashes. When adding a dash the segment after the dash must also start with a letter.
angular-8ball
```

2. Why are there so damn many files?

	Looks like each component will have the following:
		- HTML page
		- component (in typescript)
		- a module (also typescript)
		- tests
		- CSS

3. Why do I have both an HTML page (with hard coded links??) as well as a component? Not sure of the purpose for both (at least in the 'Getting Started' app)

4. As far as I can tell, HTML tags do not belong in the component. The component seems to be for handling text. This reminds me a lot of angular 1 in that way

	UPDATE: You can put HTML tags and such in the `template` prop of a component. Why they don't show this in the gettings started app is beyond me

5. the double bracket {{ syntax }} remains. I dig that

6. How do you update a class property dynamically??

7. How do you call a function??
	- ng-click seems to be deprecated (at least it isn't working for me)

### Conclusion:

My Magic 8-Ball is basically just one function that returns a string onclick. Nothing is wired up to the input at this time. From start-to-finish, this took about 23 minutes.
