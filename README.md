# Minotar

A Minotar is a global avatar that pulls your head off of your Minecraft.net skin, and allows it for use on several thousand sites. See some uses below.

![clone1018](https://minotar.net/avatar/clone1018/64)
![citricsquid](https://minotar.net/avatar/citricsquid/64)
![Raitsui](https://minotar.net/avatar/Raitsui/64)
![runforthefinish](https://minotar.net/avatar/runforthefinish/64)
![NoMercyJon](https://minotar.net/avatar/NoMercyJon/64)
![Nautika](https://minotar.net/avatar/Nautika/64)
![Notch](https://minotar.net/avatar/Notch/64)
![NiteAngel](https://minotar.net/helm/NiteAngel/64)
![hyp3rdriv3](https://minotar.net/helm/hyp3rdriv3/64)
![S1NZ](https://minotar.net/helm/S1NZ/64)
![drupal](https://minotar.net/helm/drupal/64)
![wildhog101](https://minotar.net/helm/wildhog101/64)
![KakashiSuno](https://minotar.net/helm/KakashiSuno/64)

## Sweet and Simple API

### Simple Heads
Unlike the PayPal API, we keep things nice and simple. For basic usage just provide a username:
`<img src="https://minotar.net/avatar/clone1018">`

You can also set a size. We use pixels and we only need the width. Just add it to the end. 
`<img src="https://minotar.net/avatar/clone1018/100">`

And since some services require an extension we've added simple support for it. Just add .png to the end. 
`<img src="https://minotar.net/avatar/clone1018/100.png">`

### Avatar With Helm
Sometimes you want to display a helm too, that's fine with this endpoint.    
`<img src="https://minotar.net/helm/clone1018/100.png">`


## Advanced API GET!

#### User's Skin
You can even use Minotar's API to get a users skin. We're adding more soon!  
`<img src="https://minotar.net/skin/clone1018">`

You can also set the browser to download the image by using:  
`https://minotar.net/download/clone1018`

#### Random Skin
Randomly generated head? We got that too.  
`<img src="https://minotar.net/random/100.png">`


Licensed under the SIMPL: http://simplaza.net/hax/SIMPL/

### How to install?
If you want to host this yourself you'll need to install this, http://wideimage.sourceforge.net/download/ , we recommend using the pear package. You'll also need to add this to the main folder (where index.php is located) https://raw.github.com/chriso/klein.php/master/klein.php