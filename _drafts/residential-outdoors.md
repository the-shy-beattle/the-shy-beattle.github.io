---
layout: ''
title: residential outdoors
subtitle: ''
preview: ''

---
# Residential Outdoor and Landscaping Water Use

In this water footprint challenge we focus on residential outdoor water use. Between 50-75% of residential water consumption in the U.S. is outdoor water use ([Milesi et al., 2005](http://secure.ntsg.umt.edu/publications/2005/MREDTN05/MappingCristinaMIlesi.pdf)). Outdoor water use for lawn irrigation peaks in the summer months, the same time when water delivery systems operate at peak system capacity, and is therefore an important target for water conservation programs. Some cities in the western U.S. target water conservation for outdoor use through rewards systems that encourage the transformation of lawns into xeriscaping. “[Brown is the new green](http://www.nytimes.com/2014/03/13/garden/brown-is-the-new-green.html)” is the motto of these campaigns.

In this challenge you will explore residential outdoor water use in the western U.S.

## Reflect on factors impacting evaporation

During the month of July the highest average evaporation rate in California is 20.98 in (Death Valley, CA) and the lowest is 4.49 in (Ferndale, CA). Review [this table](http://www.wrcc.dri.edu/htmlfiles/westevap.final.html) to learn more about how this is calculated. Now go “visit” these places using an online map such as Google Earth, Apple Maps or Bing Maps.

There is also a third argument you can use when slicing - `step`. This specifies how often to step through the list. By default, this is 1 which means it will iterate over every single element in the list, however you can change this to be any integer, positive or negative. If `step` is a negative integer it will iterate through the list backwards (which is often using when determining if a string is a palindrome).

### Evaporation from swimming pools

Evaporation from swimming pools In this step you will estimate the amount of water lost each year by a swimming pool. We will focus on Riverside, CA, a city with an evaporation rate that is only slightly higher than the evaporation rate in Los Angeles.  Find the annual mean evaporation rate.

### Find the dimensions of an example swimming pool

Using [Google Maps](https://www.google.com/maps/place/4393+Riverview+Dr,+Riverside,+CA+92509/@33.994539,-117.4220176,183m/data=!3m1!1e3!4m2!3m1!1s0x80dcb3c59e15bf21:0x36fe5d89360fd0db) or [Bing Maps](http://binged.it/1DI3a0c) navigate to the Memorial Park public swimming pool at the following address: 4393 Riverview Dr, Riverside, CA 92509. and measure the size of the outdoor pool using [Google’s distance tool](http://www.screencast.com/t/bvuvJye9eHh) or estimate based on Bing’s map legend in the lower left corner.

Pool length: _________________________ feet

Pool width (don’t worry about the slightly wider part at the stairs): ___________________ feet

Using the Python built-in function `sum()` we're able to pass an iterable and it will add each element together.

### Calculate how much water evaporates from a pool

To calculate the volume of water evaporated from the pool you need to multiply the pool length, width and amount of water evaporated, in feet. (Remember, Volume =LxWxD). In this case, volume is equal to the number of cubic feet of water lost to evaporation annually. You could convert cubic feet to gallons, or you can use this [simple swimming pool volume calculator](http://www.swimmingpool.com/maintenance/testing-your-water/pool-volume-calculator). To use the website, enter the pool length, width, and evaporation rate, converted to feet and rounded to the nearest number.

### How much water is evaporated each year from the pool surface?

about _________________ gallons

## Understand evaporation from lawns

Now we would like you to think about the amount of water that would be lost due to [evapotranspiration](http://www.cimis.water.ca.gov/Resources.aspx) over a lawn that has the same size as the Memorial Park swimming pool in Riverside.

### Evapotranspiration rate

Evapotranspiration rate in Riverside, CA _______________

### Monthly lawn water use

Monthly amount of water required by the piece of lawn during the peak watering month (Baseline): ___________________ gallons/month

### Annual lawn water use

Estimate the amount of water per year needed for the lawn (for simplicity, multiply the amount by 12 but be aware that this overestimates the amount of water):_________________________gallons/year

## Compare water footprints of swimming pools and lawns

Compare the amount of water lost due to evaporation on an uncovered pool surface and that of a lawn.

### 6a Water lost to pools

Amount of water lost from pool surface annually __________________ gallons

### Water lost to lawns

Amount of water lost from lawn surface annually __________________ gallons

### Reflection

Now that you’ve examined both water loss from swimming pools and from landscaping what, if anything, surprised you? What recommendations might you make regarding landscaping and pool construction policy in drought stricken CA?