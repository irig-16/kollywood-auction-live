# Kollywood Auction Live

A live Kollywood star-auction party game for 2 to 4 players, one phone each. Everyone gets the same purse to bid on heroes, heroines, directors and production houses. Then the box office decides who built the best film slate.

**Play now:** https://kollywoodauction.netlify.app/

## Play

1. One player hosts and shares the 4-letter code, invite link or QR.
2. Friends open the same page on their phones and join. No accounts or sign-up needed.
3. Add computer players to fill the table if you're short.

## Features

- Equal purses, minimum bid steps and a live hammer timer.
- Modes for the full cast, heroes only or heroines only.
- A math-based computer bidder with very little luck.
- Box-office results with grades, badges and a simple recap.
- Voice chat, reactions, sounds and vibration on Android.
- A photo studio, with a built-in photo pack for the cast.

## How it works

It's one self-contained HTML file. Devices connect peer to peer over WebRTC using [PeerJS](https://peerjs.com) and its free public broker. There's no backend, and the host's device runs the game.

Budgets, grosses and ratings are game values, not real figures. The game isn't affiliated with any actor, studio or production house.

## Third-party code

- PeerJS 1.5.5 (MIT)
- qrcode-generator 1.4.4 (MIT, Kazuhiko Arase)
