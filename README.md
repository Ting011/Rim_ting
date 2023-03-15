# Rim_ting
Vim in Rust by Ting

This is an early version of Rim(Vim in Rust) for practice used.
The main idea of text editor is following the implementation of [Hecto](https://www.flenker.blog/hecto/);

Thank you, flenker.blog!
-------
### Progress now
- [x] Implement a basic text editor Hecto editor
- [ ] Transfer basic input key of Hector editor into Vim keywords
  - [ ] classify the input keys of Vim into Motion, command, operator and extra parts
  - [ ] design the user input memory system
- [ ] Modify state line to record and show current key input
- [ ] Seperate reading and writing mode
- [ ] Design the vim functions
  - [ ] Command (TODO)
    - [ ] uU -- do and undo
    - [ ] iI -- enter insert mode
    - [ ] aA -- append mode
    - [ ] dD -- delete or delete line
    - [ ] pP -- paste before and after
    - [ ] /% -- search and jump
  - [ ] Motion
    - [ ] hjkl -- move ←↑↓→
    - [ ] weWE -- next word, pre word
    - [ ] HL -- screen top bottom
    - [ ] +-$^ line operation
  - [ ] Operation
    - [ ] d -- delete
    - [ ] c -- change
    - [ ] y -- yank(copy)
    - [ ] = -- auto format
    - [ ] <> indent and unindent
  - [ ] Extra and combination
      - [ ]  :wq and :q! -- save and quit
