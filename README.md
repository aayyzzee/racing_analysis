# Racing Performance Analysis, 2022-2026

I'm on a Formula SAE Electric team, and I wanted to know how our electric car has actually done at Formula SAE Michigan over the years, not just how it felt. So I built this workbook. It covers the Michigan electric competition from 2022 to 2026, plus the 2026 Formula Hybrid+Electric event. The team name is hidden as [SCHOOL] throughout.

The file is `Racing_Performance_Analysis_2022-2026.xlsx`. It's a normal Excel file with 13 sheets and 14 charts. Most of the numbers are formulas, so you can click a cell and see where it comes from.

I started from a spreadsheet of my own. The original analysis, with identifying names removed, is the file named "Racing_Analysis_2022-2025_(original).xlsx" if you want to compare.

## What's in it

- **Dashboard and School Trend:** our place, score, gap to the winner and percentile for each year
- **Event Deep Dive:** our rank in every event, every year, next to the field average and the best team
- **Field Overview and Leaderboards:** how strong each year's field was
- **2026 Results:** all 88 ranked teams
- **Competitors:** 15 teams I tracked across all five years
- **Car Specs Analysis:** motors, voltage and weight against score
- **Data Quality and Sources & Notes:** what I checked, what I couldn't, and links to every source

## Where the data came from

- **2026:** the official SAE results PDF. I checked all 88 ranked teams against it, row by row, and found no mismatches.
- **2022 and 2025:** also checked against the official SAE results PDFs. Every ranked team's place and total matches.
- **2023 and 2024:** I couldn't find the official electric results PDFs, so I checked places and totals against FS World, a third-party site. They match, but FS World rounds scores to whole numbers.
- **Car specs:** 2025 and 2026 come from the team information pages in the SAE PDFs. 2023 and 2024 come from my original spreadsheet, and I haven't been able to check those against anything official.

The competition-source links are on the Sources & Notes sheet. One source, our team website, had its URL removed to keep the team anonymous.

## Three things I found

1. **2026 was our best year since 2023.** We finished 4th of 88 with 756.9 points, up from 13th of 78 in 2025. That's 238.9 more points. We were 2nd in 2023.
2. **Endurance is where the points go.** We got 21 of 275 in 2025 and 186.2 in 2026. In 2026 we left about 89 points on the table there. Presentation was the other big gap: 30.2 of 75, which was 46th in that event.
3. **More motors goes with higher scores.** Across 2023 to 2026, the correlation between number of motors and total score is about +0.41. Weight is about -0.26, and voltage is weak at +0.14. This is only a pattern. Teams with more motors also tend to be better in lots of other ways, so it doesn't show that motors cause the score.

## Things to know before you trust it

- 2022 event data is thin. Only a handful of teams have event scores in the source, so 2022 event ranks aren't comparable to later years. Totals and places are fine.
- SAE labels the car specs "for information only, not validated", so they're self-reported by teams.
