# WEB102 Prework - *Sea Monster Crowdfunding*

Submitted by: **Utshah Neupane**

**Sea Monster Crowdfunding** is a website for the company Sea Monster Crowdfunding that displays information about the games they have funded.

Time spent: **8** hours spent in total

## Required Features

The following **required** functionality is completed:

* [x] The introduction section explains the background of the company and how many games remain unfunded.
* [x] The Stats section includes information about the total contributions and dollars raised as well as the top two most funded games.
* [x] The Our Games section initially displays all games funded by Sea Monster Crowdfunding
* [x] The Our Games section has three buttons that allow the user to display only unfunded games, only funded games, or all games.

The following **optional** features are implemented:

* [ ] List anything else that you can get done to improve the app functionality!

## Video Walkthrough

Here's a walkthrough of implemented features:

https://www.loom.com/share/7dac45b7d78045a4a0780bceebbe3bb9?sid=ca7d43f0-e698-4027-9234-37df99470d67

Video created with Loom.  
<!-- Recommended tools:
[Kap](https://getkap.co/) for macOS
[ScreenToGif](https://www.screentogif.com/) for Windows
[peek](https://github.com/phw/peek) for Linux. -->

## Notes

One challenge encountered while building the app was understanding the correct filter logic for funded vs unfunded games. Initially, I had the comparison operators reversed (using `>` instead of `<` for unfunded games), which resulted in displaying the wrong set of games when filtering. This was resolved by carefully reviewing the requirements and testing the filter functions to ensure they displayed the correct games based on whether the pledged amount was less than or greater than/equal to the goal amount.

## License

    Copyright 2025 Utshah Neupane

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <https://www.gnu.org/licenses/>.
