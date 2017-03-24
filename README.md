# Pandemic Legacy Calculator
A Spreadsheet for recording Pandemic Legacy infected cities and calculating some relevant probabilities.

Go to [How to play](#how-to-play) to start a game with Pandemic Legacy Calculator, and keep track of what cities are
in danger!

# Table of Contents
- [Overview](#overview)
- [How to play](#how-to-play)
- [Copyrights and Disclaimer](#copyrights-and-disclaimer)
- [Credits](#credits)

# Overview

## Main Tab

### Game Summary Section
Range: (C3:N6)

Includes:

- Next Explosion: number of top cards containing the next Epidemic card
- Safe: number of top cards GUARANTEED NO Epidemic card
- Active Cities: Infected Cities (top City Cards or discarded City cards)
- Cards Left: Remaining Player Card deck size
- ProbAdhoc: Explosion probability. Details in [Adhoc Tab](#adhoc-tab) and [Epidemic explosion probability](###epidemic-explosion-probability).
- Player actions (H3:K4): Remaining turns for each player until Player Cards exhausted.
- Infection Rate: current infection rate. (Number of city cards revealed during infection phase)
- Turns since last Epidemic: As its name
- \# Explosions: number of epidemic cards revealed during the current game

### City Recording Section
Range: (A7:P55)

Includes:

- \# (City number): Background color indicates the type of virus
- Alert: Alert level for infection. Larger number means coming sooner. 
  * Background color 
  + Red: Urgent
  + Yellow: Secondary
  + Green: Discarded
- City: 
  * Font color: virus type
  * Background color: other connected viruses (the largest one)
- Connection: Connected cities (B:blue, Y:Yellow, K:Black, R:Red)
- Infection Records:
  - Pre-Epid: Infection markers before the 1st Epidemic (including 1st Epidemic)
  - 1st Epid: Infection markers between the 1st and 2nd Epidemic (including 2nd Epidemic)
  - 2nd,3rd,4th,5th Epid: similar as above
  - 6th Epid: Infection markers after the 6th Epidemic
- Infection Coming Indicators:
  - IsComingSoon: Top City Cards
  - IsComingLater: Deeper Infected Cities
- Population Resilience: Special marker for the city removed from game


### Probability Section
Range: (X7:AA55)

Includes:

- InfectProb1: Infection probability for Tier 1 Cities
  See [Infection probability](###infection-probability) for details
- InfectProb2,InfectProb3: Similar to above
- EpidProb: Epidemic infection probability
  See [Epidemic explosion probability](###epidemic-explosion-probability) for details

## Static Tab

## Adhoc Tab

# How to play

## Record the Game

1. Reset the file
2. Record the initial cities
3. Record the new infections
4. Record the epidemic!
5. Record special funding effects

## Use the statistics

### Safe turns
### Remaining actions
### Infection probability
### Epidemic explosion probability

# Copyrights and Disclaimer
Copyright (C) 2017 Lin Xu 

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program, please see the LICENSE file. If not, see 
<http://www.gnu.org/licenses/>.

# Credits
Designed and created by Lin Xu. Tested and documented by Lei Shi. 
