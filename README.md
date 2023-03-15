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
  - [ ] Command
    - [ ] uU -- undo times or line
    - [ ] iI -- enter insert mode
    - [ ] aA -- append mode
    - [ ] dD -- delete or delete line
    - [ ] pP -- paste before and after
    - [ ] /%? -- search and jump
    - [ ] rR -- replace char or replace mode
    - [ ] m -- set mark
  - [ ] Motion
    - [ ] hjkl -- move ←↑↓→
    - [ ] weWE -- next word, pre word
    - [ ] HL -- screen top bottom
    - [ ] +-$^ line operation
    - [ ] ' -- goto mark
    - [ ] M -- screen middle
    - [ ] nN -- find next and prev
  - [ ] Operation
    - [ ] d -- delete
    - [ ] c -- change
    - [ ] y -- yank(copy)
    - [ ] = -- auto format
    - [ ] <> indent and unindent
  - [ ] Extra and combination(combination of int and operation)
      - [ ] :wq and :q! -- save and quit
      - [ ] int+hjkl -- move int lines
      - [ ] gg -- move to end
      - [ ] int + y + y/$/... -- copy with different attribute
      - [ ] int + d + d/^/... -- delete with different attribute
- [ ] Further feature
  - [ ] open multible windows
  - [ ] open multible files
