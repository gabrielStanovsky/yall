# Identifying plurality in English second person pronouns

This repo contains the data described [Y’all should read this! Identifying Plurality in Second-Person Personal Pronouns in English Texts](paper-link). The data is composed of two domains: [Twitter](./data/twitter) and [Europarl](./data/europarl). 
In each, we identified and annotated gold plurality labels for the ambiguous English "you".



## Data format

Each file is in json lines format, where each line is a an *unmasked* entry in the dataset.
Here's an example entry:

```
{
    "raw_tweet": "Good morning Twitters! It's early, barely 5:30 hope you all have a wonderful day! Peace and blessings! Audi",
    "min_ind": 52,
    "max_ind": 59,
    "you_type": ";;;plural;;;",
    "you_str": "you all",
    "user_id": "37274847"
}
```


## Citing

If you found this useful, please cite:

```
TODO
```
