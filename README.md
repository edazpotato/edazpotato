
Hey. I see you've stumbled upon my github page somehow.... Congrats.

What do you want an award or something? You here to scoff at how little contributions I've made to the GitHub repositories I am apart of?

Well while you are here I might as well tell you stuff about me.

Where to start, where to start....

Uhh, I like turtles? Yeah that's right I like turtles. Pretty cool fact about me right? Turtles.
(I'm talking about the ones from [ComputerCraft](https://github.com/SquidDev-CC/CC-Tweaked) by the way.)


```js
fetch("https://api.github.com/users/edazpotato/repos", {
	headers: { Accept: "application/vnd.github.v3+json" },
})
	.then((res) => res.json())
    .catch(() => {})
	.then((repos) =>
		repos.map((repo) =>
			console.log(
				`Oh! I am also working on a project called [${repo.name}](${repo.html_url})... Yep very creative I know. Will probably change sooner or later. I'm just too stupid to come up with something right now.`
			)
		)
	)
    .catch(() => {});

// This code works by the way! Try it in your browser console.
```


Uhh, I'm a person... I guess? What do people put in their own README files anyways?

Well I'm pretty boring and I can tell you are bored reading this.

Here are some other cool people you can check out: [TheModdedChicken](https://github.com/TheModdedChicken/TheModdedChicken) | [Archie](https://github.com/archiecodes) | [Grify](https://github.com/grify)

They most likely have more interesting projects.




(Blatenty stolen from [TheModdedChicken](https://github.com/TheModdedChicken/TheModdedChicken) >:))
