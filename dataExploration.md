## HURRICANE ISLAND SCALLOP GROWTH 
# Data Exploration

### Plot1

**File Name:** _Net_5_Bottom_GSI_2019_

**Image:**

**Code:** 
<pre>
  ggplot(data = Net_5_Bottom_GSI_2019, mapping = aes(x = DateTime, y = Temp)) +
  geom_point() +
  geom_smooth()
</pre>

**Details:** 
In this plot we came to know that the overall temperature for July and August was below 58 degree Fahrenheit. The temperature was almost steady and was not much changing throughout the day. As per the data, the temperature for two days, increased to more than 60 degree Fahrenheit. We have to check how the change in temperature will impact the scallop's growth.


### Plot 2

**File Name:** _GSI_Data_Sheet_

**Image:**

**Code:** 
<pre>
  ggplot(data = GSI_Data_Sheet, mapping = aes(x=Gear_Type, y=GSI, fill=Sex))+
  geom_col(position = "dodge")
</pre>

**Details:** 
In this plot, the scallops _Gear Type_, _Sex_ and _GSI_ are considered together to plot a bar graph. The Caged female scallops has highest GSI of 22 and that of a male is of 30. While the GSI for Lantern Net gear type has the same GSI for the Male and Female scallops.


### Plot 3

**File Name:** _GSI_Data_Sheet_

**Image:**

**Code:** 
<pre>
  ggplot(data = GSI_Data_Sheet) +
  geom_point(mapping = aes(x = GSI, y = Total_Viscera_Weight)) +
  facet_wrap(~ Gear_Type, nrow = 2)
</pre>

**Details:** 
In this plot, the scallops _Gear Type_, _GSI_ and _Total Viscera Weight_ are considered together to form a faceted plot. The plot draws a relationship between the scallop’s weight and their development in terms of their age or reproductive stages based on their Gear type whether the scallops are in cage or lantern net. With the plot we came to know how the _Gear Type_ plays a role in their development.


### Plot 4

**File Name:** _GSI_Data_Sheet_

**Image:**

**Code:** 
<pre>
  ggplot(data = GSI_Data_Sheet) +
  geom_smooth(mapping = aes(x = Shell_Weight, y = Shell_Height, color=Gear_Type))
</pre>

**Details:** 
In this plot, the development of the scallops i.e. _Shell Height_ and _Shell Weight_ based on their _Gear Type_, whether they are in cage or in lantern net. Based on the plot, the scallops in lantern net has higher weight and height as compared to the caged scallops.
