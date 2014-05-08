# UK European Parliamentary Candidates 2014

On Thursday 22nd May 2014, voters in the UK will head to their polling station to cast their votes for the European Parliament.
For the larger parties, voters might be aware of their candidates from the familiar leaflets through the door but for smaller groups,
let's say the "Pirate Party" in the North West, it's not viable to flyer an entire region.

This fact, combined with the parlous state of the regional press in the UK, means that often voters will be reading many candidates names
for the first time as they receive their voting slip. I for one think this is a poor state of affairs and bad for democracy in this country.

## Parliamentary Candidates as DATA

Using pdf scraping techniques, I've collated the entire set of 2014 UK MEP hopefuls into a JSON file, based on information provided by the European Parliament.

The source for the data is here: [http://www.europarl.org.uk/en/european_elections/candidates2014.html](http://www.europarl.org.uk/en/european_elections/candidates2014.html)

## What can you do with this?

As an example of what you can do with this, I've ran the name of every UK MEP candidate through the [OpenCorporates API](https://opencorporates.com/) to see who among them are directors of UK companies.
The results are a little rough as many candidates don't give their full legal name, but it has yielded thousands of results. They're viewable as csvs in the folder above. (NB I work for OpenCorporates, but this research is my own).

### Example directorships

  * UKIP's Dianne Martin James (South East) - [Director of "BLACK & WHITE CONSULTING"](https://opencorporates.com/companies/gb/03887600)
  * UKIP's Nigel Farage (South East) - [Director of "THORN IN THE SIDE LIMITED"](https://opencorporates.com/companies/gb/07650770)

## Stats

  * 760 candidates
  * 44 parties

## Fields Available (master.json)

  * name
  * address
  * party
  * party slogan (varies by region)
  * region

