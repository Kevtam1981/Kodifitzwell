taken from [https://github.com/mrgsi/tmdbh.players](https://github.com/mrgsi/tmdbh.players)

`direct.pov.json`
```
{
    "name" : "POV",
    "plugin" : "plugin.video.pov",
    "priority" : 500,
    "is_resolvable": "false",
    "play_movie" : "plugin://plugin.video.pov/?mode=play_media&media_type=movie&query={name}&year={year}&poster={poster}&title={title}&tmdb_id={id}",
    "play_episode" : "plugin://plugin.video.pov/?mode=play_media&media_type=episode&query={showname}&year={year}&season={season}&episode={episode}&ep_name={title}&tmdb_id={tmdb}&premiered={firstaired}"
}
```
`direct.pov.select.json`
```
{
    "name": "POV Source Select",
    "plugin": "plugin.video.pov",
    "priority": 500,
    "is_resolvable": "false",
    "play_movie": "plugin://plugin.video.pov/?mode=play_media&media_type=movie&query={name}&year={year}&poster={poster}&title={title}&tmdb_id={id}&autoplay=false",
    "play_episode": "plugin://plugin.video.pov/?mode=play_media&media_type=episode&query={showname}&year={year}&season={season}&episode={episode}&ep_name={title}&tmdb_id={tmdb}&premiered={firstaired}&autoplay=false"
}
```
