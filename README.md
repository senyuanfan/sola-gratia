# Sola Gratia Worship Scores

This repository contains ChordPro charts and supporting notation
for the Sola Gratia Band at MVCCC.

## Structure
- songs/: ChordPro source files
- notation/: piano intros, melodies, special parts
- sets/: setlists by date
- templates/: song templates

## Editing
- Edit .cho files using VS Code or any text editor
- Import directly into SongBook Pro / OnSong

## Guidelines
- Keep charts simple (lyrics + chords)
- Use notation only when necessary
- Do not hardcode keys unless intentional

## Usage

- ChordPro renderer releases: https://github.com/ChordPro/chordpro/releases
- ChordPro documentation: https://www.chordpro.org/chordpro/home/
- Follow OS-specific instruction to install ChordPro program first
- e.g. on Windows, add ChordPro to PATH
    ```
    $oldpath = [Environment]::GetEnvironmentVariable("PATH", "User")
    $newpath = "$oldpath;C:\Program Files\ChordPro.ORG\ChordPro"
    [Environment]::SetEnvironmentVariable("PATH", $newpath, "User")
    ```
    Then restart your terminal, or apply to the current session with:
    ```
    $env:PATH += ";C:\Program Files\ChordPro.ORG\ChordPro"
    ```
- 