# Data Cleaning Changelog for FIFA 21 Players Dataset

## Date: 2023-08-27

### Time: 9:30 pm

- **Action:** Removed 20 duplicate values by column long_name
- **Result:** 19213 unique values remaining
- **Description:** Duplicate values in the long_name column were removed to ensure each player name is unique.

### Time: 9:33 pm

- **Action:** Renamed columns:
  - sofifa_id to id_number
  - short_name to player_short_name
  - long_name to player_name
- **Result:** Improved column names for better clarity.
- **Description:** Column names were updated to be more descriptive and aligned with the data they represent.

### Time: 11:34 pm

- **Action:** Removed the following columns:
  - List of columns including player_url, player_positions, and others
- **Result:** These columns were removed from the dataset.
- **Description:** Unnecessary columns were removed from the dataset as they won't be used for analysis.

### Time: 11:55 pm

- **Action:** Data transformation on specific columns:
  - Cleaned special characters and symbols from player_short_name, player_name, club_name, and nationality_name columns.
  - Modified weight_kg column for appropriate formatting.
  - Adjusted date formats in club_joined and dob columns for consistency.
- **Result:** Improved data readability and formatting.
- **Description:** Special characters were removed from player and club names for better readability. Date columns were formatted uniformly.

---

# Data Cleaning Documentation for FIFA 21 Players Dataset

## Introduction

This document outlines the data cleaning process applied to the FIFA 21 Players dataset. The purpose of this cleaning process is to ensure data quality, consistency, and improved readability for analysis.

## Steps Taken

### Duplicate Removal

Duplicate values in the long_name column were identified and removed to maintain unique player names.

### Column Renaming

Column names were updated for better clarity:
- sofifa_id to id_number
- short_name to player_short_name
- long_name to player_name

### Column Removal

Several columns that are not required for analysis were removed from the dataset:
- player_url
- player_positions
- overall
- club_team
- league_name
- league_level
- club_loaned_from
- nationality_id
- nation_team_id
- nation_jersey_number
- weak_foot
- skill_moves
- international_reputation
- work_rate
- body_type
- real_face
- release_clause_eur
- player_tags
- player_traits
- pace
- ls
- st
- rs
- lw
- lf
- cf
- rf
- rw
- lam
- cam
- ram
- lm
- lcm
- cm
- rcm
- rm
- lwb
- ldm
- cdm
- rdm
- rwb
- lb
- lcb
- cb
- rcb
- rb
- gk
- player_face_url
- club_logo_url
- club_flag_url
- nation_logo_url
- nation_flag_url

### Data Transformation

Special characters and symbols were removed from columns:
- player_short_name
- player_name
- club_name
- nationality_name
weight_kg column was formatted for consistency.
Date columns (club_joined and dob) were adjusted to uniform date format.

## Conclusion

The FIFA 21 Players dataset has undergone comprehensive data cleaning, including duplicate removal, column renaming, removal of unnecessary columns, and data transformation for improved readability. This cleaned dataset is now ready for analysis and insights.
