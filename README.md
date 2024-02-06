# Language tutor - draft 

_Work in progress_

Language tutor app to learn/test chinese pronunciation 

<!-- Used [Quick Start Guide](http://electron.atom.io/docs/tutorial/quick-start) as a starting point. -->

![sample](/sample.png)



## Setup for STT 
- setup Chinese dictation is osx preferences.
- use double click `fn` twice to start dictation.
- if you pronounced correctly you'll see the expected pinyin and english definition/translation. otherwise try again :)

## Setup for TTS
- Download Chinese Mandarin `Ting-Ting`  text to speech language in osx.
- Enable Pinyin Chinese simplified keyboard in osx, with all caps as a switch between keyboard. 
- now you can type using chinese keyboard and Pinyin carachters. eg if you remember how a word is spelled in pinyin but not how to pronunce it in chinese, and want to hear the pronunciation by the tts before trying dictation.


## Development

```
npm install
```

```
npm start
```

## TODO: 

- [x] if you type pinyin, perhaps in another window. then it translates to chinese char, translates to english definition. and then can run say.js on it.  
- [ ] speed control for speech playback, eg with slider? // not urgent
- [ ] try move what's in the script tag in browserify and see if the app will run in the browser as well. eg in github pages demo. 


## Bug 
- [ ] if there is a gap between char it won't recognise. eg `我叫王芳芳 你叫什么`. 


<!-- Possible option for language API https://github.com/imochen/c2e -->


## Contributor 
- [Pietro](https://github.com/pietrop)