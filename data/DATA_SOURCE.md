#Data Source: Roadside Air Quality Monitoring

This dataset contains air quality measurements collected at a roadside monitoring station.

##Data Access
- View in Google Sheets: https://docs.google.com/spreadsheets/d/1XpAvrpuyMsKDO76EZ3kxuddBOu7cZX1Od4uEts14zco/edit?usp=sharing
- Direct CSV download: https://drive.google.com/uc?id=1SOe9b4VJ1FCtDVgZ2T8d00-jTw2Kux1i

##Notes
- Skip the first line (`Chatham Roadside`) when reading the CSV.
- Dates are text with inconsistent formats; convert to datetime.
- Times are inconsistently formatted.
- Nitrogen Dioxide values may include `"nodata"`; filter/remove before casting.
- `Status` is constant and should be dropped.

##Used in this project for
- Cleaning/wrangling
- Type conversion
- Feature engineering (weekday)
- Sorting by NO₂ level
