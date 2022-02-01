# TodoMVC Hyperapp

This is an implementation of [TodoMVC](https://todomvc.org) using [Hyperapp](https://github.com/jorgebucaran/hyperapp). 

Live demo at [https://zaceno.github.io/todomvc-hyperapp](https://zaceno.github.io/todomvc-hyperapp)

## Running locally

The way I set this up, there is no build system involved – just static code. To run it in a browser it needs to serve the folder with a local http-server. I use [`npx`](https://www.npmjs.com/package/npx) to run:

```sh
npx servor --reload ./
```

Then I visit `http://localhost:8080`

## Types

You can also run `npx tsc` in the folder to verify types. If you are using a typescript-aware plugin in your editor to check types as you code, bear in mind these types require typescript > v4.5
