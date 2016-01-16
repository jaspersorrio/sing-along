# singalong

This project is generated with [yo angular generator](https://github.com/yeoman/generator-angular)
version 0.15.1.

## Automated verse scrolling

singalong aims to provide instrument players a helper that helps them scroll through the song automagically.

## Features to implement

### Automagic scrolling

singalong will help you scroll based on what you have sang or played.

Use case:
Guitarist, pianist and other instrument players don't have a free hand to flip to the next page while singing.
The verses should 'fade out' when they are no longer active.

e.g

###### You call me out upon the waters

##### The great unknown where feet may fail
 
#### And there I find You in the mystery

### In oceans deep

## My faith will stand

# And I will call upon Your name

## And keep my eyes above the waves

### When oceans rise, my soul will rest in Your embrace
 
##### For I am Yours and You are mine

###### Your grace abounds in deepest waters



### Screen broadcast

Use case:
Phone is used as a receiver. But the phone is too small to share with friends.
Go to a unique url, singalong.com/uniqueUrl to be able to follow what the singer is singing. 

### Offline version

Use case:

The musician needs to do a live gig and the wifi/3g might not be good to use.

## Resources

[Frequencies of musical notes](http://www.phy.mtu.edu/~suits/notefreqs.html)

[Demo that uses the Web Audio API](https://mdn.github.io/voice-change-o-matic/)

[The Web Audio API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API)

[Case study by Paul of Guitar Tuner App](https://aerotwist.com/blog/guitar-tuner/)

[Guitar Tuner App built by Paul @google ](https://guitar-tuner.appspot.com/)

[Better app that can understand chords!](http://www.proguitartuner.com/guitar-tuner/)

[Google Speech Recognition Spec](https://dvcs.w3.org/hg/speech-api/raw-file/tip/speechapi.html)

[Tutorial for Google Speech Recognition](https://developers.google.com/web/updates/2013/01/Voice-Driven-Web-Apps-Introduction-to-the-Web-Speech-API?hl=en)

## Build & development

Run `grunt` for building and `grunt serve` for preview.

## Testing

Running `grunt test` will run the unit tests with karma.
