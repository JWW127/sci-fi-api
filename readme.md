<div align="center">
<img src="https://res.cloudinary.com/dpc3zrcvs/image/upload/v1665979341/johhny_xocde5.gif">
<h1>Sci-Fi-Api</h1>
</div>

## What is this?

This is a static api that serves science fiction quotes. If you have ever used jsonplaceholder.typicode.com it works in a similar way but at sci-fi-api.netlify.com

## Usage

Since this is a static api you'll get the whole contents of the file at the time of writing this 86 quotes. <br/>
For your own testing you can grab it with simple fetch like so <br/>

```
async function getQuotes() {
  const res = await fetch("https://sci-fi-api.netlify.app/");
  const data = await res.json();
  return data.quotes;
}

```

This api is also in use with [sci-fi-cli](https://github.com/JWW127/sci-fi-cli), which is just a CLI app that returns quotes from this project.

## "The Spice must flow."
