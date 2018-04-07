This is a repo for Unity WebGL templates. I made this for myself to make it easier to just add this to my projects as a git submodule for easy editing. Also, Unity requires WebGL templates to be in the assets/WebGLTemplates folder or it won't pick them up (Unity doesn't do a deep search for WebGLTemplates folders...).

## How to install
Add this repo as a git submodule in the assets/ folder of your Unity project.

```
cd UnityGameProjectFolder/assets
git submodule add https://github.com/Mykaelos/WebGLTemplates.git
```

# Templates
## DefaultEmbedded
This is the same as the Default WebGL template, but without the body margin, and the footer. This allows the WebGL player to fit correctly in a specific sized viewport. DefaultEmbedded still shows the Unity splash screen and loading bar.

## MinimalEmbedded
Same as the Minimal WebGL template but without the body margin, so that the WebGL player can be embedded properly in Itch.io's or GameJolt's pages without it being shifted because of the default body margin.
