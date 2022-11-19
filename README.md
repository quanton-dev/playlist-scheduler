# playlist-scheduler

purpose of this project is to provide api to schedule playlists.
Will generate a result based on requirements.

###### An example input/output(This is subject to change):

Input:

```json
{
  "name": "90's Techno",
  "options": {
    "interrupt_other_playlists": true,
    "playback_type": "Basic",
    "playback_order": "random"
  },
  "schedule": {
    "repeats": 2,
    "day_of_week": [
      0,
      1,
      2,
      3,
      4,
      5,
      6
    ],
    "start_time": "00:32",
    "end_time": "01:00"
  },
  "metadatas": [
    {
      "name": "Acid Ress part1",
      "duration": "412"
    },
    {
      "name": "Acid Ress part2",
      "duration": "344"
    },
    {
      "name": "Freedom of expression",
      "duration": "221"
    },
    {
      "name": "Dark Acid",
      "duration": "331"
    },
    {
      "name": "Dark Light",
      "duration": "189"
    },
    {
      "name": "Lacrimosa",
      "duration": "403"
    },
    {
      "name": "Symphonic Techno",
      "duration": "947"
    }
  ]
}
```