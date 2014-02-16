<ol>
<li>It signifies the total number of rows in the table minus 1. In a more literal definition it says grab all the rows in the table body give me length of that array (the array of rows) and subtract one.
</li>
<li>
Those function calls return the color associated with the number in between the parenthesis according to the function color.  The function associates Rate column linearly with the range of colors from “orangered” to “silver” so it returns the color that is associated with that rate.  Which color corresponds to 0, 10, or 150 is what the calls ask.
</li>
<li>
If the array is passed the minimum and maximum rate values then scale will be based on the actual rates instead of their position in the table.  This will look less uniform then using the position since there are varying differences in the rates between the different entries even if they are next to each other position-wise.  This would be appropriate so that you can better see the difference between each rate instead of the difference relative to each other.
</li>
<ol>