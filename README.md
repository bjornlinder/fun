Treasure Hunter
===
Thank you for your interest in Treasure Hunter. The game basically involves walking around digging for treasure.

Card games excuded, I figure that most games are based on some sort of grid, so writing the code for the grid was the focus of the project. At this point I've gone through some of the Ruby Primer and some of the Well Grounded Rubyist. I haven't learned any user interface yet so it's just command line, and I haven't used many of the more advanced techniques that I have learned.

There is one bug in the Treasure Hunter game I have thus far been unable to figure out. The map should have a uniform depth of 3 for each tile; however some tiles will only allow to dig out the first or second level before hitting the bottom.

2-7-14

The issue described above was fixed by upgrading Ruby to version 2.1. The grid hash also works with 1.9.3, but has an issue with Ruby 1.8.7. Next thing to work on will be a cleaner map print method.
