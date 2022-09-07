# Fredrik Hellman

### Museum of Natural History NYC

 Must see exhibits in the museum are **dinasours** and **neanderthals**.

-----------------------------------------------

#### The closest airport is JFK International Airport

1. Take the AirTrain towards Jamaica Station
2. Take the subway towards World Trade Center
3. Take the bus to the Museum of Natural History

- Mythic creatures
- Lizards and snakes
- Beavers
- Blue Whale Model
- Easter Island

[Link to AboutMe.md](AboutMe.md)


------------------------------------------------
## Four cities to visit

Below are four cities I would recommend someone to visit. First column is the city, second column is an important location to visit and the third column is how long you should stay there.


| City | Place to visit | Length of stay |
| ---- | ------ | ----- |
| London  | Big Ben | 2 days|
| Helsinki | Musiikkitalo |2 weeks|
| Madrid  | Santiago Bernabeu  |4 days|
| Paris | Eiffel Tower   |2 days|

-------------------------------------------------

## Pithy Quotes

> Life is what happens when you're busy making other plans. - _John Lennon_

> Get busy living or get busy doing. - _Stephen King_

--------------------------------------------------

## Code snippets

> Generating responsive image html with php?

[Link to stackoverflow](https://codereview.stackexchange.com/questions/278506/generating-responsive-image-html-with-php)

```
 <?
$image= [
    'name' => 'faith',
    'srcset' =>
        [
        'sizes' =>
                [
                'size' => ['xs','sm','md','lg','xl','xxl'],
                'vw' => [ 576, 768, 992, 1200, 1400, 2048 ]
                ],
        'ratio' => ['portrait' => '3x4','landscape' => '3x2' ],
        'format' => ['avif', 'webp','jpg']
        ],
    'caption' => 'Earth Day, Victoria, BC',
];

$sizes = array_combine($image['srcset']['sizes']['size'], $image['srcset']['sizes']['vw']);
?>

```