# Working with the Aviation Edge Satellite Tracker API #
The Aviation Edge satellite tracker API is designed to provide developers with real-time information about the positions of satellites and other orbiting objects. This API allows developers to incorporate this information into their own applications, allowing users to track the location of satellites in real-time. The purpose of this API is to provide developers with a reliable source of information about satellite positions, making it easier to create applications that incorporate this data.



[Satellite Tracker API](https://www.worldindata.com/api/Aviation-Edge-satellite-tracker-api)

The Worldindata API marketplace is a platform that seeks to make APIs more accessible and user-friendly. By indexing a wide range of third-party APIs, the marketplace makes it easier for developers to discover and integrate APIs into their own applications. The goal of the marketplace is to make it easier for developers to find and use APIs, enabling them to build more powerful and useful applications.

## Client Types, Industry, and Sectors ##

**Industry and Sectors**
- aerospace
- communication
- astronomy

**Client Types**
- aerospace platforms
- communication services
- space-related websites




## Objects, Parameters and JSON output ##
The GET /v2/public/satelliteDetails endpoint of the Aviation Edge satellite tracking API allows users to retrieve detailed information about specific satellites.

**filter parameters**
- code
- launchYear
- intldes
- orbitalapogee
- orbitalperigee


```
[
{
"code":408,
"country":"US",
"intldes":"1961-015EH",
"launchDate":"1961-06-29",
"launchNum":"15",
"launchPart":"EH",
"launchYear":"1961",
"name":"THOR ABLESTAR DEB",
"orbitalApogee":"1035",
"orbitalInclination":"66.79",
"orbitalPerigee":"929",
"orbitalPeriod":"104.73",
"result":{
"ECI":{
"posX":0.5454890369,
"posY":-0.2586148768,
"posZ":-0.9850851542,
"velX":0.0575062685,
"velY":0.0304486006,
"velZ":0.0232874073},
"geography":{
"alt":1006.4047009328,
"lat":-58.6467050931,
"lon":129.4707358377},
"satelliteInfo":{
"classification":"U",
"idLaunchNumber":"015",
"idLaunchPiece":"EH ",
"idLaunchYear":"61",
"orbit":99888,
"rightAscension":21.7828,
"satnumber":408}
},
"size":"MEDIUM",
"tle1":"1 408U 61015EH 20129.79820524 -.00000021 +00000-0 +54301-4 0 9997",
"tle2":"2 408 066.7883 021.7828 0070545 199.3274 220.5694 13.74946678998881",
"type":"DEBRIS",
"updated":1589063274000
}
]

```
**Objects**
- code
- country
- intldes
- launchDate
- launchNum
- launchPart
- launchYear
- name
- orbitalApogee
- orbitalInclination
- orbitalPerigee
- orbitalPeriod
- result
- ECI
- posX
- posY
- posZ
- velX
- velY

## SDK ##

The Aviation Edge satellite position API offers Software Development Kits (SDKs) in a range of popular programming languages, including JAVA, PHP, Ruby, Python, and JavaScript. These SDKs make it easier for developers to integrate the API into their own applications and make use of the satellite tracking data.



### Disclaimer of representation ###
Worldindata is a platform that aims to make data from around the world more accessible and user-friendly. We do not own any of the data that we index, but rather we provide a marketplace for developers to discover and integrate APIs from data providers. We are big fans of the Aviation Edge satellite tracker API and are committed to helping developers make use of this valuable resource. Please note that we are not responsible for the accuracy or availability of the data provided by third parties.

[Worldindata](https://www.worldindata.com)
