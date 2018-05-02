# README

Height profile in North/South and East/West direction for the Moon crater Theophilus.

## Codebook

### Input file "input/EW.txt"

- **position** (Numeric) [km] Distance from profile start point.
- **GLD100** (Numeric) [m] Height of point.
- **lon** (NUmeric) [°] Longitude of point.
- **lat** (NUmeric) [°] Latitude of point.

### Input file "input/NS.txt"

- **position** (Numeric) [km] Distance from profile start point.
- **GLD100** (Numeric) [m] Height of point.
- **lon** (NUmeric) [°] Longitude of point.
- **lat** (NUmeric) [°] Latitude of point.

### Output file "output/profiles.csv"

- **dr** (Numeric) [km] Distance from crater center.
- **dh** (Numeric) [m] Height above lowest point in both profiles.
- **h** (Numeric) [m] Height of point.
- **direction** (String) Either "EW" when point is from East/West or "NS" when it is from North/South profile.