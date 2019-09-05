=====================
Paper optimising
=====================

Introduction
============

Paper servers can be optimised by changing server configurations in

1.  paper.yml
2.  spigot.yml
3.  bukkot.yml

by using notepad or just a simple text editor.

paper.yml
========

Find world-settings


Max-entity-collision by default is on 8, try lowering it:
::
   
    max-entity-collision: 4

Max-auto-save-chunks-per-tick by default is on 24 but halving it makes a big difference:
::
   
    max-auto-save-chunks-per-tick: 6

