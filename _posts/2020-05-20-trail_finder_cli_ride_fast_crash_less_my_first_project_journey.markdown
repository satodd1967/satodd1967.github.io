---
layout: post
title:      "**Trail Finder CLI "Ride Fast Crash Less" my first project journey.**"
date:       2020-05-20 13:24:47 -0400
permalink:  trail_finder_cli_ride_fast_crash_less_my_first_project_journey
---


     So the hardest part and what became the best part of my first project didn't even involve the project directly.  I'm a self led student and I'm behind due to allot of work related issues and that whole virus thing so I wanted to get into this as quickly as possible.  Problem!!!  The IDE wasn't working for me at all after work.  I could login if I wated maybe 15 minutes and then it would inevitably crash 20 minutes later and not login again.  So I went to our unsung heroes behind the Ask Question button and asked if anything could be done.  They said the team was working on it, but that there was no eta.  I told them I was behind and asked if I should skip ahead and try and setup my local environment.  They thought that was a great idea!  Should be pretty easy on a mac they said!
		 
		 Soooo about 3 hours later I was up and running and good to go with a validated setup.  To be fair everyone was great and very helpful, there were just issues, guess thats why we have the IDE.  New Problem!!! I had no idea how to use this thing and the heroes informed me that they couldn't help me with any part of the CLI project, even local environment issues.  What?  All the tutorials were for the IDE....  Go with it and press on time is wasting!
		 
		 Soooo after allot of googling, reading and checking multiple different previous and upcoming lessons and mostly a metric $#^% ton of trial and error I had a skeleton app setup and I was on my way to glory.  And by glory I mean choosing a project that was way too complicated and got me in way over my head.  I didn't realize that at first.
		 
		 Trail - Finder - My plan was to allow Riders(users) to login, get presented with a list of featured cities and either choose one of those cities, or enter thier own city to find mountain bike trails pulled from the MTB Project API.  What I didn't realize up front was that the API pulled data based on latitude and longitude, not on city and state.  This meant that I had to find another API or website that would give me data to convert city and state into lat/lon and enter it into the API params for the MTB Project API....... needless to say it just continued to get more and more complicated from there. I most definately should have kept it simple considering I hadn't even gotten to the code part yet, which I was already not very confident in.
		 
		 Surprisingly things went really really well.  I was able to pull from the API's convert using JSON merge the data output information and deal with the tons of error handling.  Knocked it all out in a few days and was very proud.  Then as I was finishing up I watched the video that AVI did on Anti Patterns.  I realized I was a very proud parent of a bunch of garbage code that wasn't effectively extensible or scaleable and I wasn't sure if I could write in the appropriate way.
		 
		 After spending the rest of the weekend going through videos and trying to refactor I decided to start from scratch while still utilizing the pieces of code that were usefull and the error handling patterns that I had put together for input.  I took the next day off of work and stared at the screen from 10AM until midnight like Cartman playing World of Warcraft.  By midnight I had it all working again with only a few issues remaining.  I learned a ton in that one day.
		 
		 So I spent some time tonight fixing those issues and should submit it soon and we will see how it goes.  Thanks for reading and happy coding!  
