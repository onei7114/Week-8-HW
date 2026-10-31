# Project: Skelton Dance

> - **Files:** skelton-dance.html
> - **Dates:** 2026-10-31
> - **Defaults:** Co Pilot
> - **Status:** keeper
> - **Use:** used 2026-10-31; would use again
> - **Reusability:** local machine but could be pusshed to sharble link
> - **Tags:** single-file-html, game, audio
> - **Takeaway:** easy to make added musica after. the music is okay
> - **Story value:** It is Halloween so it is festive
> - **Surprises:** I was surprised how quicly it was rendered and how accurate it is

# Prompt 1:

> - **Tool:** Co Pilot 2026-10-31
> - **Session:** fresh · attached: none
> - **Time:** 1min 37sec
> - **Verified:** human-tested
> - **Human edits:** none

		Create a standalone HTML file that will be a Skelton dance game. This game should show a Skelton and have arrows dropping from the top to the bottom and users must match those arrows on their key bord. Each time the user hits an arrow at the right time the Skelton should hit a new pose. The user should get points for every correct arrow and, the arrows should get faster each time the user hits 10 correct arrows. Once the user misses three arrows the game is over. 

## Output 1:

        I’ll inspect the existing project structure and conventions, then build and validate the game in the most appropriate location.

        The repository uses one self-contained HTML file per project. I’ll place the game in the existing Skelton_Dance project folder and keep it dependency-free, with canvas rendering, keyboard controls, scoring, speed progression, and a three-miss game-over flow.

        Edited
        skelton-dance.html+308-0
        I found one gameplay cleanup issue during review: successfully hit arrows should leave the playfield immediately instead of accumulating as faded objects. I’m tightening that behavior and making the speed milestone track hits directly, then I’ll run a syntax and smoke validation.

        Edited
        skelton-dance.html+7-4
        Opened Browser

        The file parses successfully, and the browser opened the standalone page with the expected start screen and controls. I’m doing one final browser smoke test to confirm the start action activates the game loop and updates the canvas state.Created the standalone game: skelton-dance.html

        Features:

        Falling arrow gameplay with keyboard controls
        Skeleton pose changes on successful hits
        Score tracking
        Speed increases every 10 hits
        Game ends after 3 missed arrows
        Restart button and responsive layout
        Validated with JavaScript syntax checking and a browser smoke test.

# Prompt 2:
> - **Tool:** Co Pilot 2026-10-31
> - **Session:** continued · attached: none
> - **Time:** 24sec
> - **Verified:** human-tested
> - **Human edits:** none
        add some spooky but fun music

## Output 2:
        Added spooky/fun generated music to skelton-dance.html.

        Haunted arcade-style melody, bass, and beat
        Starts when the game starts
        Stops when the game ends
        Music on/off toggle
        No external audio files or dependencies
        Validated with JavaScript syntax checking and browser testing.