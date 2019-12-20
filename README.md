# Sound
### a JavaScript sound manager library

A way to play multiple sounds at once, the ability to stop them from playing.
Nice sound fade out when stopping instead of abruptly ending.


## Installation

```
npm install @patomation/sound
```
or
```
yarn install @patomation/sound
```


## Usage

```Javascript
import sound from '@patomation/sound'

sound.add('mysoundID', 'pathToSound/mysound.mp3')

sound.player.play('mysoundID')
```

### Stopping the sound
```Javascript
sound.player.stop('mysoundID')
```

### Setting master volume
```Javascript
sound.player.volume(0.6)
```

### Removing a sound
```Javascript
sound.remove('mysoundID')
```
