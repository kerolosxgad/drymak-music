# [drymak-music](https://music.codexeg.net/)

Turns Youtube playlists into nice standalone pages. Great for parties, or to send to friends. https://music.codexeg.net/

![image](https://user-images.githubusercontent.com/4929974/89713446-93b6c180-d98f-11ea-8f5e-33f5e847c11c.png)

## Usage

On the home page, just paste the youtube link of a video contained in the playlist. Or you can build the link yourself: https://music.drymak.me/?&list={playlist_id} where `{playlist_id}` is the ID of the Youtube playlist (the `&list=` parameter in the url).


Some form of Ad blocking is reccomended to skip commercials inbetween playlist videos.

## Development

First install dependencies:

```sh
npm install
```

To run in hot module reloading mode:

```sh
npm start
```

To create a production build to the `dist` folder:

```sh
npm run build
```

