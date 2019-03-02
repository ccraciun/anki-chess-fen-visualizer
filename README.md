# Anki Chess FEN Visualizer

Plugin for rendering chess diagrams in FEN notation inside anki. You should probably use the card
model from https://ankiweb.net/shared/info/1176122148 instead.

Updated from https://github.com/ospalh/anki-addons to run on Anki 2.1

## Description

Display a record of a chess position in Forsyth–Edwards Notation as a chess board.

The FEN record has to be complete (with active player, castling &c.) and it has to be enclosed in a pair of [fen] [/fen] tags.

This is the way that can be used on AnkiDroid and, apparently by some old Anki1 add-on as well.

Example
Just put ` [fen]n1rb4/1p3p1p/1p6/1R5K/8/p3p1PN/1PP1R3/N6k w - - 0 0[/fen]` on a card.

Fonts
This add-on does the display without any images. When you don’t see the chess pieces you should install a font with them. Maybe one from here or here.

To use a specific chess piece font, use the CSS class chess_board, add a line like .chess_board {font-family: 'my_chess_piece_font';} to your chess note’s styling.
