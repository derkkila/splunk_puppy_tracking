# Splunk Puppy Tracking Dashboard
A Splunk Dashboard to track the weight of a new litter of pups. In this case, a litter of Newfound puppies from the Newfoundland Club of New England Rescue.

## History of The Newfoundland Club of New England Rescue
<img align="right" src="/static/ncne_logo.jpg">
The Newfoundland Club of New England, Inc. is a non-profit corporation founded in 1969 with clear objectives intended to promote the Newfoundland Dog breed. NCNE has over 600 individual, family, and honorary members.

NCNE is a regional club of the Newfoundland Club of America and offers its members a variety of activities each year from fun days to working events to supported entries at American Kennel Club dog shows and obedience trials. Members are encouraged to participate and help with the organization of these events. NCNE also publishes a bi-monthly newsletter for its membership.

## My intro to the rescue
Last year, our 14 year old Newfie/Lab mix passed leaving our home empty, so we applied with the Rescue to be an option for a rehomed Newfoundland. They had a special Newfoundland that had been given up on my it's previous owners because of his size and lack of training (Their fault!). Titan needed a home without kids because at his size, he didn't know how to live or play with such small creatures, as he clocks in around 160lbs. After several months of training, Titan is such a wonderful dog to have in our home and very well behaved, he just needed the right family!

## Enter Ember and Ash
Ember and Ash were a pair of rescues from a bad backyard breeder who overbred Ember with litters constantly. Vets estimate that she had given birth to 10 litters in her 6 years of life, which is easily 4 times the number a reputable breeder would do. Ash was the male of the pair and also malnourished and not properly cared for either. They noticed upon arrival that Ember was in heat when she was brought it, and signs showed she had either recently given birth or that she might be pregnant. Turns out, she was pregnant. 

## Puppies!!!
On January 15th, Ember's litter of 7 puppies was born and all look healthy initially, however their growth needs to be constantly monitored to make sure they are putting on weight and growing into the healthy puppies they should be. We were chosen as one of the families to adopt one of the puppies and I couldn't be happier to add another giant, fluffy, slobbery pup to our home.

## Yes, you can Splunk puppies!
To help the foster and rescue track their weight I started tracking it in Splunk! I collected the weight data from the foster family watching the mom and pups and enter it into Splunk in a CSV format.

'puppy name','weight(oz)','weight(lbs)','date'

I also have a CSV file tracking life events for the puppies like the date their eyes opened, or their first vet visit, all the way up to the day they go to their furever homes.

'date','event'

This lets me track weight and events on a single dashboard using timecharts and event annotations.
