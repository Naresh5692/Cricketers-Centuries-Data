# Cricket Century Data Analysis

This repository contains an Excel file that records centuries made by various cricket players along with their performance details, match context, and additional data points.

## Overview

The Excel file contains the following columns:
- **Century #**: The century number.
- **Start Date**: The date when the match started.
- **Player**: Name of the player who scored the century, along with their country.
- **Runs**: The number of runs scored by the player.
- **Status**: Whether the player was out or not out.
- **Mins**: Time spent at the crease (in minutes).
- **Balls Faced**: Total balls faced by the player.
- **Boundaries**: Number of fours hit.
- **Sixes**: Number of sixes hit.
- **Strike Rate**: Strike rate during the innings.
- **Innings**: Whether the innings was the first or second.
- **Opposition**: The opposing team.
- **Ground**: The venue of the match.
- **Day, Month, Year**: Date information of the match.
- **Weekday**: Day of the week when the match started.
- **Performance Ratings**: Subjective ratings for how the player and the match went.
- **Player Country**: The country the player represents.
- **Additional Metrics**: Various calculated fields like player initials, surname, and performance flags using functions like `VLOOKUP`, `HLOOKUP`, `MID`, `LEN`, and `UPPER`.

## File Structure

The data is structured to allow detailed analysis of players' performance across different matches, providing insights such as:
- **Player Performance**: Tracking how well players performed based on strike rate, runs scored, and the number of boundaries.
- **Match Context**: Information about the opposing team, venue, and date for added context to each century.
- **Calculated Fields**: Several functions (`VLOOKUP`, `HLOOKUP`, `CONCATENATE`, etc.) are used to generate insights like player initials, country, and performance.

## Usage

The Excel file can be used for:
- **Cricket Data Analysis**: Perform deep analysis of batting performances.
- **Educational Purposes**: Learn how to utilize Excel functions like `VLOOKUP`, `HLOOKUP`, and string manipulation functions.
- **Sports Enthusiasts**: Get detailed insights on cricket centuries spanning multiple decades.

## Contributing

Feel free to fork this repository, make improvements, and open a pull request. Any additional statistics, insights, or improvements to the data structure are welcome.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
