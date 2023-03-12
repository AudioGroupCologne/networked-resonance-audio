# networked-resonance-audio

Resonance Audio Networked A-Frame component, for WebRTC broadcasted audio as a Resonance Audio source.
Based on the Networked-Aframe Networked Audio Source : [NAF](https://github.com/networked-aframe/networked-aframe/)

## Dependencies

Use this component in [A-Frame](https://aframe.io), together with the [Networked-Aframe](https://github.com/networked-aframe/networked-aframe) library and the [Resonance Audio](https://github.com/AudioGroupCologne/aframe-resonance-audio-component) component.  


## Usage

### Add the networked-resonance-audio component and a resonance-audio-source to NAF avatar entity:

```html
      <a-entity
            class="avatar"
            networked-resonance-audio
            resonance-audio-src="
        visualize: true;
        loop: true;
        autoplay: true;"
      >
```


## Run
See the Glitch project for implementation: [networked-resonance-audio](https://networked-resonance-audio.glitch.me/) 

## Acknowledgements

The networked-resonance-audio component is based on the NAF networked-audio-source.js found at [networked-audio-source](https://github.com/networked-aframe/networked-aframe/tree/master/src/components) 
