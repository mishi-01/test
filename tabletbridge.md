
With the pen representing the scalpel. 

Goldilocks Model Feedback Gauge
Color relating to pressue applied. Red is too much, green is just right. Just like baby bear. 

How to bring the force values that we collected from the skin tests that we slaved away on, into the VR world? What mechanism?

Wacom tablet has pressure sensing capabilities for artists, with more opacity matching with pressure. As seen hurrrrrrr

We first had to see how is the wacom tablet sensing pressure and relating it to opacity? A bit of tinkering with Wacom's SDK revealed it to be a numerical correlation!!!!

So with a few lines of C# I was able to display this number as the pen hit the tablet. 
Then we wanted to see what physical loads correlated with these numbers? And so we strapped the Wacom tablet to the base of the Mark-10 instron, and clamped the pen to the top and lowered it to see the correlation. Collecting all this data revealed a rather distrubing discovery....


KAGIRI DESU
THERES A LIMIT 

I will be conducting a test in December 2017 with more data points to see what the heck is UP ya feel 
Another issue is that this was all with the pen completing vertical, completely perpendicular to the tablet when in reality it is at an angle. So future tests will have to take this into account. 

