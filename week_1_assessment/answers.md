variable = "variable"


This data type is a string.

eg. of data types:

integers = 1

boolean = true/ false

floats = 2.2

array = [1 ,2, "array"]

hashes = {key: value}

:002 > car = {wheels: 4, max_speed: 180, color: "white"}
2.7.0 :003 > car
 => {:wheels=>4, :max_speed=>180, :color=>"white"} 
2.7.0 :004 > car2 ={wheels: 3, max_speed: 90, color: "pink"}
2.7.0 :005 > car2
 => {:wheels=>3, :max_speed=>90, :color=>"pink"} 
2.7.0 :006 > vehicles = [car, car2]
2.7.0 :007 > vehicles
 => [{:wheels=>4, :max_speed=>180, :color=>"white"}, {:wheels=>3, :max_speed=>90, :color=>"pink"}] 
2.7.0 :008 > vehicles[1]
 => {:wheels=>3, :max_speed=>90, :color=>"pink"} 
2.7.0 :009 > vehicles[1].color
2.7.0 :011 > vehicles[1][:color]
 => "pink" 