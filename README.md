# Shitposting Cube
Makes any string into a shitposting cube, ready to use in [pcj](https://www.reddit.com/r/programmingcirclejerk/). Special thanks to [stone_henge](https://www.reddit.com/r/programmingcirclejerk/comments/8axnso/in_go_the_programmer_is_encouraged_to_handle/dx5hzj9/) for the original algorithm, however, since Python only has the lol too slow variant and the lol not turing complete variant I decided to rewrite it in a real, 4D webscale, futuristic language like Go, then ditched it all and rewrote it in OCaml for wageslaves

# Features
Well, it's a webservice now, you can find it at [Heroku](https://cubeposter.herokuapp.com/). You can also clone this repo, open it with Visual Studio and compile it (or edit app.fsx with VSCode, compile it with Mono and have Nuget install your dependencies because I'm too lazy to change to paket), then run it and visit localhost:8080/ to see a frontend that at least has a button and a textbox. I use [Suave](https://suave.io/) for the webserver because it's the ~~only one with a logo hipster enough for me~~ most decent webserver I found that's wrote on F# so you're stuck with it too. 

# Roadmap
 * ~~I'll make it into SaaS (Shitposting as a Service) by putting up a webservice~~ ~~I'll put the webservice somewhere in the actual web so you don't have to clone the repo, compile it and run it locally, but it runs now~~ Finally, it plays along with heroku!
 * I'll add more transformations to it (mainly squareposting and hypercubeposting for the moment)
 * Maybe I'll transcompile it to JavaScript, post it as an npm package and get 10 million downloads a day because if is-even can do it so can I.
 * I may also port it to VB.NET because @fukkaudekku once said it's best language and I realized she's right.
 * Until then, it's only available in OCaml Enterprise Edition&trade;, so enjoy and don't forget to spam "lol no hkts"

# Conclusion
This is mainly a proof of concept to get a grasp of how to do web development on F#. Nothing of this is to be taken seriously, although I do plan on expanding this to add several different templates for "ASCII art" with strings. Feel free to use it, fork it, spam lol no hkts or do whatever with it.
