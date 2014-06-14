Music Backlog
=============

The purpose of this repository is to use git branches to keep track of
different pathways of exploration for my own personal music discoveries. Each
branch is a different discovery pathway. The only file here is a text file
`musicback.log` (and this README), which is just a list of the songs on the
branch, but the discovery tree structure can be viewed with a tool like `gitk`.

Tree Structure
==============

* The `master` branch serves as the root of the tree.
* Everytime a new song or artist is discovered independentally (not related
  to a ongoing music listening session or a continuation of exploring), a
  new branch is split off from master.
* When a single new song/artist is discovered from a song on the branch, the 
  file is updated with the new song and the commit is made in the current
  branch.
* When multiple new song/artists are discovered from a song on the branch, the
  current branch remains at the last commit, and a branch is made for each song.
  Each file in the new branches are updated with the songs responsible for
  the split, and the commits are made to the respective branches
