# Fake Artist Online _with 14 people_

An online party game based on Oink Games' tabletop game, _A Fake Artist Goes to New York_. Draw with your phone or a mouse.

Play on Heroku: https://fake-artist-max14.herokuapp.com/

Tech: Vue, Express, Socket.io, Webpack, Mocha

## Changing Max Number of Players

- [Adjust `MAX_USERS`](https://github.com/charut/fao/blob/f725fd1ec074857a612f2565daf33cdde20ca394/src/server/game-room.js#L8)
- [Add more colors](https://github.com/charut/fao/blob/master/src/public/js/playerColors.js)

## Develop

Watch-build public: `npm run watch-p`

Build and run server: `npm run build-s && npm run start`

## Contributing guidelines

I'm not actively seeking contributors, but if you have a pull request I'm happy to take a look!

Some guidelines:

-   I'm not seeking additional keyword prompts. There's already a lot!
-   UI should accomodate iPhone 5 screens (320x568).
-   FAO isn't ambitious. The old Crabhat Spyfall webapp was a huge inspiration for me.
-   As a loose rule of thumb, I'm hesitant to add to or enforce game rules. This is in line with keeping things minimalistic, and also accommodates for players with house rules.

If you have questions, feel free to email me or create a feature request for discussion.

I'm also totally cool with people hosting their own forks, as long as there's credit to the original repo.

## Support

Enjoy the game? Send a tip: [Ko-fi](https://ko-fi.com/krackocloud).

## License

GNU General Public License v3.0

## Credits

Notification SFX from [Material.io](https://material.io/design/sound/sound-resources.html) ([CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/))
