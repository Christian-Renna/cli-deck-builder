# cli-deck-builder
Command-line deck-building game in C++ inspired by DC Deck-Building (class project)
goal

theres not really an easy way to play DC deck building online and playing irl needs the whole setup + other people. so this is a simple terminal version of the main loop (shuffle, draw, buy cards) so you can play solo and mess around w different deck strategies

MVP
  starting deck: 7 punch, 3 vulnerability
  shuffle deck, draw 5 card hand
  play hand to get power
  line up of 5 cards you can buy w power (refills when you buy)
  discard pile reshuffles into deck when deck runs out
  game ends after X turns or when main deck runs out
  score = total VP in your deck

  
future plans (v2+)
  supervillains / boss fights
  kick pile
  card effects (draw extra, destroy cards etc)
  2 player hot seat
  basic AI opponent
  save/load

  
tech stack
  C++17
  just the standard library (vector, random, algorithm, fstream, iostream)
  g++ + makefile
  card data stored in a csv file (data/cards.csv), game state is just in memory
  git + github

  
folders
  src/ - code
  include/ - headers
  data/ - cards.csv
  tests/ - tests
  docs/ - eisenhower matrix + system diagram
