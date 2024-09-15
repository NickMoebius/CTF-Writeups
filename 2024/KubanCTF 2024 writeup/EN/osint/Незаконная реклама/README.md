# Illegal Advertising
---

> **Illegal Advertising**
> 
> **Difficulty**: Easy
> 
> Recently, in Saint Petersburg, a man was spotted near a quarry distributing possibly illegal advertising by putting up posters. One of these posters somehow made its way into the reviews of a popular city map directory. Your task is to find the location where the poster was placed and determine what he was advertising.

## About the Challenge
---
In this challenge, we need to find quarries within the city limits of Saint Petersburg, Russia, and search nearby for possible advertising locations.

## How to Solve It
---
The challenge description mentions "a popular directory's reviews." The most popular Russian online directory is **2gis.ru**, so we’ll focus our search there.

It's crucial that the quarries are **within the city limits**, so in **2gis**, click on "Saint Petersburg" to display the city borders as a faint blue line. There are many quarries around Saint Petersburg, and **2gis** tends to suggest places even outside your search area, so we need to stay within these boundaries during our search.

![[city-borders.jpg]]

Next, search for "карьер" and try to find relevant ones while reviewing any attached photos and reviews.

I checked around 15 search results, and the most relevant seemed to be:

- Ivanovsky Quarry
- Shuvalovsky Quarry
- Orlovsky Quarry

However, none of these locations had reviews with photos of illegal advertising.

After six hours, no one had solved the challenge, so the organizers provided a hint:

> **Hint 1**
> 
> We just received information that the suspect placed a QR code near a gazebo by a body of water.

This hint led me to think that the "quarry" we need might not be labeled as a quarry on the map, even though it is one. So I started checking larger bodies of water visible on the Saint Petersburg map.

My attention quickly shifted to the **Firefighters’ Heroes Park**, which had bodies of water that resembled small quarries. I searched for more information and found that these were once clay pits from an old brick factory, though now they're considered ponds.

Additionally, the hint provided crucial information: the advertisement was placed near a **gazebo**. Fortunately, **2gis** conveniently shows gazebos ("беседка") on its map.

![[alcove.jpg]]

I checked all the gazebos within the initially relevant quarries and the ponds of **Firefighters’ Heroes Park**, where users had also left reviews.

The correct gazebo was quickly found: [link to 2gis](https://2gis.ru/spb/search/%D0%B1%D0%B5%D1%81%D0%B5%D0%B4%D0%BA%D0%B0/geo/70030076429075570?m=30.408271%2C59.853555%2F16.13)

In the reviews, there was a photo with a QR code attached to a poster: ![[qr-code.jpg]]
[Original photo](https://i0.photo.2gis.com/photo-gallery/f0e177a8-4041-4702-a4f9-19f1beaec8c2.jpg)

After scanning the QR code, we get the flag:

Копировать код

```
CSC{th1s_is_ill3gal_4dvert1sing}
```
