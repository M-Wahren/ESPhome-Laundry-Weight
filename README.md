# ESPhome Laundry Weight

## Items used
* Wemos D1 mini
* HX711 Amplifier
* Digital bathroom Scale
* Load sensor combinator (Optional)

Just recently finnished building my 2 floor Laundry shoot and realized i will never remember to check the laundry untill im out of cloths and the basement is overflowing with cloths..<br>
After googling a bit on what my options could be for checking how much cloths are in the basket i stumbled uppon a arduino guide using load cells in a bathroom scale for measuring weight.<br>
After cheked my own bathroom scale i orderd the parts needed (as described above) including the Load sensor combinator for a easy soldering.

Connecting my load cells upp to the Load sensor combinator inside the scale and using a cable with four wiers to place my HX711 and Wemos in a more reachable location. (If you look Closely at [Laudry Shoot] upper left corner you can see the cable going to the Wemos)

[Image]

## Time to finish project?
- 30 min soldering
- 10 min writing ESPhome yaml
- 3 h debuging

Apparently you need good solder joints or it will  not work..

## Files
* ESPhome YAML file
* [Image with] Load sensor combinator (as i have it connected)
* [Image without] Load sensor combinator if you go that rout.


[Image]: https://github.com/M-Wahren/ESPhome-Laundry-Weight/raw/master/Current_Setup/Scale_Closeup.jpg
[Image with]: https://github.com/M-Wahren/ESPhome-Laundry-Weight/raw/master/With_Load_sensor_combinator.png
[Image without]: https://github.com/M-Wahren/ESPhome-Laundry-Weight/raw/master/Without_Load_sensor_combinator.png
[Laudry Shoot]: https://github.com/M-Wahren/ESPhome-Laundry-Weight/raw/master/Current_Setup/Laundry_Shoot.jpg
