# Channel Of Awesome

http://dfcb.github.com/channel-of-awesome/

I built this to play fullscreen video on TV screens around the office. There are two ways you can make your own Channels of Awesome.

One is to fork this, then add a playlist array (or change the one I made) to the script. For example, to make a Channel of Awesome Cats:

```
var playlists = {
  cats:[
  	'youtube:wf_IIbT8HGk',
    'youtube:plWnm7UpsXk',
  	'vimeo:23608259'
  ],
  tech:[
    'youtube:c3-wIICjAhE:12',
    'youtube:Llmq2hYWXHo:11',
    ...
  ]
}
```
Then, view the channel by going to index.html#cats

Or, the quicker, easier way is to just put a comma-delineated playlist in the hash, like so:
http://dfcb.github.com/channel-of-awesome/index.html#youtube:wf_IIbT8HGk,youtube:plWnm7UpsXk,vimeo:23608259