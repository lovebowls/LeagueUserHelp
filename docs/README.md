# League Element User Guide

This guide explains how to use the League Element to view and analyze league information.

## Navigating the Component

The League Element is organized into four main views, accessible through a set of tabs at the top:

*   **Table**: The classic league standings table.
*   **Schedule**: A list of past and upcoming matches.
*   **Matrix**: A grid showing the results of matches between all teams.
*   **Trends**: Visual graphs to track team performance over time.

You can switch between these views at any time by clicking on the corresponding tab.

---

## Table View

The Table View is the default view and shows the current league standings.

### Understanding the Columns

*   **Pos**: The team's current rank in the table. You may see green (▲) or red (▼) arrows indicating if a team has moved up or down in the rankings since the last set of matches.
*   **Team**: The name of the team.
*   **Pts**: Total points accumulated.
*   **P**: The number of matches played.
*   **W**: The number of matches won.
*   **D**: The number of matches drawn.
*   **L**: The number of matches lost.
*   **F**: Shots/Goals For (scored by the team).
*   **A**: Shots/Goals Against (conceded by the team).
*   **±**: The shot/goal difference (F minus A).
*   **Form**: A visual guide to the team's result in their last five matches. Green is a win, yellow is a draw, and red is a loss. The most recent match is on the right.

### Filtering and Exporting

Above the table, you have two dropdown menus:

*   **Filter Dropdown**: This allows you to change the data displayed in the table.
    *   **Overall**: Shows the complete league table with all matches.
    *   **Home**: Calculates the table based only on matches played at home.
    *   **Away**: Calculates the table based only on matches played away.
    *   **Form**: Ranks teams based on their performance in recent matches, rather than total points.
*   **Export Dropdown**: This lets you download the current table view as an Excel, Word, or PDF file.

### Interacting with the Table

*   **View a Team's Schedule**: Double-click on any team's row to switch to the **Schedule View**, automatically filtered to show only that team's matches.
*   **Promotion/Relegation Zones**: Rows may be highlighted in green (promotion) or red (relegation) to indicate their position based on the league's settings.

---

## Schedule View

The Schedule View displays a list of all matches, both past and future. You can see the date, the teams involved, and the score if the match has been played.

If you have double-clicked a team in the Table View, this view will be filtered to show only that team's schedule.

---

## Matrix View

The Matrix View provides a grid that shows the results of every team played against every other team.

*   **How to Read It**: Find the "home" team in the first column on the left, and the "away" team in the header row at the top. The cell where they intersect shows the result of that specific match-up.
*   **Played Matches**: A cell with a score (e.g., "3-1") indicates a match that has been played.
*   **Scheduled Matches**: A cell with "vs" indicates a match that is scheduled but has not been played yet.

---

## Trends View

The Trends View allows you to visualize team performance through interactive graphs.

### Graph Types

You can select from several graph types using the dropdown menu:

*   **Points Over Time**: A line graph showing the cumulative points of selected teams as the season progresses. This helps you see how teams have been climbing or falling in the standings.
*   **Shots For vs Against**: A scatter plot that positions teams based on their attacking (Shots For) and defensive (Shots Against) performance.
    *   **Top-Right Quadrant**: Good attack, good defense.
    *   **Bottom-Right Quadrant**: Good attack, poor defense.
    *   **Top-Left Quadrant**: Poor attack, good defense.
    *   **Bottom-Left Quadrant**: Poor attack, poor defense.
*   **Form Over Time**: A line graph showing the "form" (based on recent results) of teams over the course of the season. This helps identify which teams are currently on a hot or cold streak.

### Interacting with the Graphs

*   **Select Teams**: Use the legend next to the graph to select or deselect teams. Simply check or uncheck the box next to a team's name to show or hide them on the graph. You can also use the "Select All" option.

---

## For Admins/Editors

If you have editing permissions for the league, you will see a few extra features:

*   **Settings Icon (⚙️)**: Located at the top-right of the Table View, this icon takes you to the league's administrative settings.
*   **Requiring Attention Panel**: This panel appears on the right (on desktop) or bottom (on mobile) and lists matches that require your attention, such as past matches where a result has not yet been entered. Clicking on a match in this panel will allow you to enter the result.
*   **Editing Match Results**: In the Matrix View, clicking on a played or scheduled match will open a dialog to edit its details. 