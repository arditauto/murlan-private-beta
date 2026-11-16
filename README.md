# Murlan Private Beta (test only)

## From iPhone
1. Open github.com, create a private repository `murlan-private-beta`.
2. Upload these project files to repository root (not the ZIP itself). In GitHub mobile browser: Add file > Upload files. Use Request Desktop Website if necessary.
3. Open dashboard.render.com, New > Web Service, connect GitHub and select repository.
4. Runtime Node; Build `npm install`; Start `npm start`; plan Free; Deploy.
5. Share Render URL with friends. Host creates a room; others enter the code.

No database. Rooms and points are lost on service restart, redeploy or free-plan sleep. Never use this beta for paid contests or public tournaments. Only friends with room code can join; not a secure authentication system.

Features: 1-4 players, AI, 45-second turn timer, first hand 3♠, 21-point match, A-2-3-4-5 straight, cut by last winner, 54 cards dealt clockwise ending at cutter, exchange, local fan hand and gather button.

Limitations: mobile drag and server-side gameplay not yet exhaustively tested on four iPhones. The fan uses offline 2.9 layout principles, not its full UI. Cut and deal are processed on server; visible deal animation is not yet implemented.
