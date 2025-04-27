# Microfrontend using Single-SPA
- Important: use <br>
`nvm use 20` <br>
`npm install -g create-single-spa` <br>

Splitted the project in some phases, for each parcel I'm creating (Base application, Angular, React)
I'm having a lot of issues about the package management and versions using `create-single-spa` 
so i'm documenting all the steps as a knowledge base
On April 11th I created the base aplication (single-spa root config)
On April 14th 2025, I created the Angular parcel (micro or wtvr it is called) with success.

## Angular-SPA
It is important to mention which Angular version I'm using: <br>
`npm i -g @angular/cli@13 @angular/core@13`<br>
PS: I created this mfe using when I installed LTE version, which is `create-single-spa@6`

Today, April 22nd 2025, I started to dealing with React parcel, and I'm already having 
issues with package installing.
I created the React app using `create-single-spa@4`

## React-SPA
Doesn't work well at first, but then I solved installing `npm install react@18.2.0 react-dom@18.2.0`

## Conclusion
Microfrontends are stricted to use only if it needed. It's not perfomartic way to use different components from legacy. Should have a unique case to use
