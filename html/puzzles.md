# Atari 7800 Impossible Mission - Walkthrough Guide

**DISCLAIMER:** *All screenshots, etc... are the property of Atari.  Copyright (c) 1989, Atari Corporation.  All rights reserved.*

## Where do I get puzzle pieces?

The Instruction Manual says that whenever searching furniture, you may encounter 3 types of items, yet the manual itself provides no pictures as references.  Below is a table showing what you may see on-screen when pressing the "up" botton next to furniture in the game:

| Searching | Nothing Here | Snoozes | Lift Init | Puzzle Piece | 
:----------:|:------------:|:-------:|:---------:|:-------------:
![](../img/searching/searching.png) | ![](../img/searching/nothing_here.png) | ![](../img/searching/password_snoozes.png) | ![](../img/searching/password_lift_init.png) | ![](../img/searching/puzzle_piece.png)

You may wonder why the "Scissors cutting paper" icon is used to indicate puzzle pieces.  Well, the end result of putting 4 puzzle pieces together is a punchcard.  What is a punchcard?  Younger players may not realize that in the early days of computing, paper cards with holes in them were used to program machines.  Whole programs would be written on stacks of cards with these holes punched out.  Here is an example of what they look like (from wikipedia):

![](../img/IBM1130CopyCard.agr.jpg)
(The above image came from [Wikipedia](https://upload.wikimedia.org/wikipedia/commons/d/d8/IBM1130CopyCard.agr.jpg))

In the game itself, a completed punch card looks like the this:
 
![](../img/puzzle_pieces/complete_set1/combos/piece7/punchcard7_v1.png)

In the game, Elvin Atombender took 9 punchcards that when combined created a 9-digit passcode and cut each of them up into four pieces.  That's why there is a scissors on the icon; it indicates that this is part of a punchcard that has been cut up.

## How to Solve Puzzles

While playing the game, you will encounter a large amount of puzzle pieces.  What do they look like?

Here are some examples:

| &nbsp; | &nbsp; | &nbsp; | &nbsp; |
:-----------------------------:|:-------------------------------:|:-----------------------------:|:-------------------------------:
![](../img/puzzle_pieces/complete_set1/unoriented/complete_v1_01.png) | ![](../img/puzzle_pieces/complete_set1/unoriented/complete_v1_02.png) | ![](../img/puzzle_pieces/complete_set1/unoriented/complete_v1_03.png) | ![](../img/puzzle_pieces/complete_set1/unoriented/complete_v1_27.png)

On the Atari 7800 version of Impossible Mission, puzzle pieces only come in 3 colors: Red, Yellow, and Green.  In other versions of the game, the color of the puzzle piece is supposed to indicate what color room the puzzle piece was found in.  However, in the Atari 7800 version, the same room will yield any color of piece; it is all random and not tied to the room colors.

So, how to we get from Puzzle Pieces to finished Punchcards?  Molds!

### Molds

| &nbsp; | **1** | **2** | **3** | **4**
:-------:|:-----------:|:-----------:|:-----------:|:------------:
**A** | ![](../img/puzzle_pieces/molds/mold_a1.png) | ![](../img/puzzle_pieces/molds/mold_a2.png) | ![](../img/puzzle_pieces/molds/mold_a3.png) | ![](../img/puzzle_pieces/molds/mold_a4.png)
**B** | ![](../img/puzzle_pieces/molds/mold_b1.png) | ![](../img/puzzle_pieces/molds/mold_b2.png) | ![](../img/puzzle_pieces/molds/mold_b3.png) | ![](../img/puzzle_pieces/molds/mold_b4.png)
**C** | ![](../img/puzzle_pieces/molds/mold_c1.png) | ![](../img/puzzle_pieces/molds/mold_c2.png) | ![](../img/puzzle_pieces/molds/mold_c3.png) | ![](../img/puzzle_pieces/molds/mold_c4.png) 
**D** | ![](../img/puzzle_pieces/molds/mold_d1.png) | ![](../img/puzzle_pieces/molds/mold_d2.png) | ![](../img/puzzle_pieces/molds/mold_d3.png) | ![](../img/puzzle_pieces/molds/mold_d4.png)

There are 16 "molds" in the game.  Think of them like Cookie Cutters.  When Elvin cut up his punchcards, he did so in a way that makes it easier to solve them.  Each initial cut wwas done with a unuqie cookie cutter / mold to divide it into two pieces.  Then, each half was cut a second time with another different cookie cutter / mold.  This may seem like a lot of information, but the important point is that it creates something you can work from.  Each puzzle piece in the game can be paired with another to make a design that corresponds to one of these molds.  These 9 molds will be unique; they won't repeat.  But, since molds are reused for secondary cuts, this does cause some trickiness:

 * First, the color of the punchcard doesn't matter.  I always make my puzzle pieces yellow so that I can see them better, and they always generate working punchcards when assembled correctly.
 * It is possible that you can line up 2 pieces and make something that matches a mold / cookie cutter layout, but have that be an incorrect pairing.  Sometimes two secondary cuts use the same mold and line up perfectly.  You will know that this has occurred when you can't find the other two pieces that make the other half of the mold.
 * There are situations where you may create a full punchcard, but it's incorect. Each punchcard is made up of 4 specific, known pieces.  Let's say of the 36 pieces, the game knows that piece 4, 7, 22, and 29 are needed for a solution.  If, somehow you cobble together a punch-card that uses the wrong four pieces, the game will not count it as complete no matter how you reorient it.  This is a very rare situation that can occur.
 * Unline the above problem, there are pieces that can be reflected and inserted into a puzzle two ways.  Only one way is correct.  See below for an example:

![](../img/puzzle_pieces/complete_set1/combos/piece1/complete_v1_12t.png)

This means there are a lot of things that can go wrong.  However, a lot of things can go very right, now that you know the secret of trying to replicate mold patterns and then try to find their matching half.

### Solving Puzzles - A Complete Example

| &nbsp; | **Piece A** | **Piece B** | **Piece C** | **Piece D**
:-------:|:-----------:|:-----------:|:-----------:|:------------:
**Found piece** | ![](../img/puzzle_pieces/complete_set1/unoriented/complete_v1_06.png) | ![](../img/puzzle_pieces/complete_set1/unoriented/complete_v1_32.png) | ![](../img/puzzle_pieces/complete_set1/unoriented/complete_v1_12.png) | ![](../img/puzzle_pieces/complete_set1/unoriented/complete_v1_08.png)
**Reoriented and common color** | ![](../img/puzzle_pieces/complete_set1/combos/piece1/complete_v1_06t.png) | ![](../img/puzzle_pieces/complete_set1/combos/piece1/complete_v1_32t.png) | ![](../img/puzzle_pieces/complete_set1/combos/piece1/complete_v1_12t.png) | ![](../img/puzzle_pieces/complete_set1/combos/piece1/complete_v1_08t.png)
**Primary Mold (first cut)** | ![](../img/puzzle_pieces/molds/mold_a1.png) |  ![](../img/puzzle_pieces/molds/mold_a1.png) |  ![](../img/puzzle_pieces/molds/mold_a1.png) |  ![](../img/puzzle_pieces/molds/mold_a1.png)
**Secondary Mold (second cut)** | ![](../img/puzzle_pieces/molds/mold_c2.png) |  ![](../img/puzzle_pieces/molds/mold_c2.png) |  ![](../img/puzzle_pieces/molds/mold_c1.png) |  ![](../img/puzzle_pieces/molds/mold_c1.png)
**Assembling 2 pieces** | ![](../img/puzzle_pieces/complete_set1/combos/piece1/combo1.png) | ![](../img/puzzle_pieces/complete_set1/combos/piece1/combo1.png) | ![](../img/puzzle_pieces/complete_set1/combos/piece1/combo2.png) | ![](../img/puzzle_pieces/complete_set1/combos/piece1/combo2.png)
**Completed** | ![](../img/puzzle_pieces/complete_set1/combos/piece1/combo_4color.png) | ![](../img/puzzle_pieces/complete_set1/combos/piece1/punchcard1_v1.png) | ![](../img/puzzle_pieces/complete_set1/combos/piece1/combo_4color.png) | ![](../img/puzzle_pieces/complete_set1/combos/piece1/punchcard1_v1.png)

----------------------

### All Puzzle Pieces - EXAMPLE 1

| &nbsp; | **Piece A** | **Piece B** | **Piece C** | **Piece D** | **Mold** | **Half 1** | **Half 2** | **Completed**
:-------:|:-----------:|:-----------:|:-----------:|:-----------:|:--------:|:----------:|:----------:|:--------------:
**Puzzle 1** | ![](../img/puzzle_pieces/complete_set1/combos/piece1/complete_v1_06t.png) | ![](../img/puzzle_pieces/complete_set1/combos/piece1/complete_v1_08t.png) | ![](../img/puzzle_pieces/complete_set1/combos/piece1/complete_v1_12t.png) | ![](../img/puzzle_pieces/complete_set1/combos/piece1/complete_v1_32t.png) | ![](../img/puzzle_pieces/molds/mold_a1.png) | ![](../img/puzzle_pieces/complete_set1/combos/piece1/combo1.png) | ![](../img/puzzle_pieces/complete_set1/combos/piece1/combo2.png) | TBD
**Puzzle 2** | ![](../img/puzzle_pieces/complete_set1/combos/piece2/complete_v1_05t.png) | ![](../img/puzzle_pieces/complete_set1/combos/piece2/complete_v1_28t.png) | ![](../img/puzzle_pieces/complete_set1/combos/piece2/complete_v1_29t.png) | ![](../img/puzzle_pieces/complete_set1/combos/piece2/complete_v1_31t.png) | ![](../img/puzzle_pieces/molds/mold_a2.png) | ![](../img/puzzle_pieces/complete_set1/combos/piece2/combo1.png) | ![](../img/puzzle_pieces/complete_set1/combos/piece2/combo2.png) | TBD
**Puzzle 3** | ![](../img/puzzle_pieces/complete_set1/combos/piece3/complete_v1_02t.png) | ![](../img/puzzle_pieces/complete_set1/combos/piece3/complete_v1_09t.png) | ![](../img/puzzle_pieces/complete_set1/combos/piece3/complete_v1_18t.png) | ![](../img/puzzle_pieces/complete_set1/combos/piece3/complete_v1_35t.png) | ![](../img/puzzle_pieces/molds/mold_b1.png) | ![](../img/puzzle_pieces/complete_set1/combos/piece3/combo1.png) | ![](../img/puzzle_pieces/complete_set1/combos/piece3/combo2.png) | TBD
**Puzzle 4** | ![](../img/puzzle_pieces/complete_set1/combos/piece4/complete_v1_20t.png) | ![](../img/puzzle_pieces/complete_set1/combos/piece4/complete_v1_23t.png) | ![](../img/puzzle_pieces/complete_set1/combos/piece4/complete_v1_27t.png) | ![](../img/puzzle_pieces/complete_set1/combos/piece4/complete_v1_36t.png) | ![](../img/puzzle_pieces/molds/mold_d2.png) | ![](../img/puzzle_pieces/complete_set1/combos/piece4/combo1.png) | ![](../img/puzzle_pieces/complete_set1/combos/piece4/combo2.png) | TBD
**Puzzle 5** | ![](../img/puzzle_pieces/complete_set1/combos/piece5/complete_v1_04t.png) | ![](../img/puzzle_pieces/complete_set1/combos/piece5/complete_v1_11t.png) | ![](../img/puzzle_pieces/complete_set1/combos/piece5/complete_v1_15t.png) | ![](../img/puzzle_pieces/complete_set1/combos/piece5/complete_v1_17t.png) | ![](../img/puzzle_pieces/molds/mold_c1.png) | ![](../img/puzzle_pieces/complete_set1/combos/piece5/combo1.png) | ![](../img/puzzle_pieces/complete_set1/combos/piece5/combo2.png) | TBD
**Puzzle 6** | ![](../img/puzzle_pieces/complete_set1/combos/piece6/complete_v1_07t.png) | ![](../img/puzzle_pieces/complete_set1/combos/piece6/complete_v1_10t.png) | ![](../img/puzzle_pieces/complete_set1/combos/piece6/complete_v1_24t.png) | ![](../img/puzzle_pieces/complete_set1/combos/piece6/complete_v1_26t.png) | ![](../img/puzzle_pieces/molds/mold_d3.png) | ![](../img/puzzle_pieces/complete_set1/combos/piece6/combo1.png) | ![](../img/puzzle_pieces/complete_set1/combos/piece6/combo2.png) | TBD
**Puzzle 7** | ![](../img/puzzle_pieces/complete_set1/combos/piece7/complete_v1_13t.png) | ![](../img/puzzle_pieces/complete_set1/combos/piece7/complete_v1_25t.png) | ![](../img/puzzle_pieces/complete_set1/combos/piece7/complete_v1_33t.png) | ![](../img/puzzle_pieces/complete_set1/combos/piece7/complete_v1_34t.png) | ![](../img/puzzle_pieces/molds/mold_a3.png) | ![](../img/puzzle_pieces/complete_set1/combos/piece7/combo1.png) | ![](../img/puzzle_pieces/complete_set1/combos/piece7/combo2.png) | TBD
**Puzzle 8** | ![](../img/puzzle_pieces/complete_set1/combos/piece8/complete_v1_01t.png) | ![](../img/puzzle_pieces/complete_set1/combos/piece8/complete_v1_14t.png) | ![](../img/puzzle_pieces/complete_set1/combos/piece8/complete_v1_21t.png) | ![](../img/puzzle_pieces/complete_set1/combos/piece8/complete_v1_22t.png) | ![](../img/puzzle_pieces/molds/mold_b2.png) | ![](../img/puzzle_pieces/complete_set1/combos/piece8/combo1.png) | ![](../img/puzzle_pieces/complete_set1/combos/piece8/combo2.png) | TBD
**Puzzle 9** | ![](../img/puzzle_pieces/complete_set1/combos/piece9/complete_v1_03t.png) | ![](../img/puzzle_pieces/complete_set1/combos/piece9/complete_v1_16t.png) | ![](../img/puzzle_pieces/complete_set1/combos/piece9/complete_v1_19t.png) | ![](../img/puzzle_pieces/complete_set1/combos/piece9/complete_v1_30t.png) | ![](../img/puzzle_pieces/molds/mold_c4.png) | ![](../img/puzzle_pieces/complete_set1/combos/piece9/combo1.png) | ![](../img/puzzle_pieces/complete_set1/combos/piece9/combo2.png) | TBD

### Try it yourself!  The above puzzle corresponds to a Save Game.

-------------------

## Special Thanks

-------------------

![Back to the main rooms page](./all_rooms.md)

![Back to the main page](../README.md)



