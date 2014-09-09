# Story map presentation #

## Introduction ##
[insert whatever I wrote before]
I have to simple goals in this presentation. First, I want to understand why story maps are not living up to their promise. I ask, why are story maps not telling stories? Second, I want to explore how we might better insure that our story maps live up to their name and tell a story.

## What is a story? ##

I think since we're all mapping professionals in some way or another it's probably unnecessary to go into particularities of what constitutes a map. But it might be helpful if, before we look closer at story maps, we first step back and think about what a story actually is.

Let's start with the basics. Merriam-Webster provides us with a few nice definitions

- an account of incidents or events
- a statement regarding the facts pertinent to a situation in question
- a news article or broadcast
- a fictional narrative shorter than a novel
- the intrigue or plot of a narrative or dramatic work
- lie, falsehood


Often times it's conceived as a certain set of elements

They transfer information through (Citraro):
- setting
- plot
- characters
- conflict
- theme

Answers the questions:

- Who?
- What?
- Where?
- When?
- Why?
- How?

But in researching for the presentation I discovered that subject of story is being pretty heavily discussed in the the closely related field of data visualization field. While lots of attempts at defining story have arisen out of those discussions, I think Robert Kosara, a well respected researcher and practitioner of data visualization offers a fitting characterization of story that is well suited for evaluating the "storyness" of a story map.

It contains:

- Facts
- Causal relationships
- Narrative sequence

It actively:

- ties facts together
- provides a narrative path through those facts
- presents a particular interpretation of those facts

Fundamentally, Kosara's definition is pretty much the same as the Merriam-Webster's or the elements-based definition, but I think it has a quite a bit overlap with what we consider with our maps, namely data analysis (turning data into information) and the illustration of information (presentation of that interpretation). It is the narrative path through the facts where I think we have some work to do, but I shall address that shortly. 


## How are story maps understood? ##

Next I want to look at story maps as they're presented by the platform makers. How is "story" taken up in these platforms? There are a lot of story map platforms out there. While ESRI Story Map seems to be the most popular or most visible, a little HTML, CSS, and JavaScript can result in comparable results. And of course much of the appeal of ESRI's platform is that you don't need to know any programming to use it. Some of those other platforms include MapStory, Heganoo (doesn't actually claim to make a story map), StoryMapJS (made for journalists primarily), and CartoDB's OdysseyJS. All of these platforms have the potential to suffer the storylessness that I've observed in ESRI Story Maps. Nonetheless, ESRI's rather aggressive marketing of their platform is unique in that it is able to leverage the company's position as an industry leader to define this mapping genre. As such, I'll be using ESRI's Story Map platform to try and answer "Why are story maps not telling stories?"

To ESRI's credit, they have attempted to some degree to explain what they think a story map is. On their Story Map webpage, they ask "What is a Story Map?"
> Story maps use geography as a means of organizing and presenting information. They tell the story of a place, event, issue, trend, or pattern in a geographic context. They combine interactive maps with other rich content—text, photos, video, and audio—within user experiences that are basic and intuitive.

In summary, story maps:

- organize content geographically
- place information in a geographic context
- contain multi-media content

And they also ask, "What are the elements of a story map?"
> Story maps use interactive web maps created with ArcGIS Online, Esri's cloud-based mapping and GIS system. ArcGIS web maps let you combine your own data, including spreadsheets and GIS data, with authoritative content and thematic maps from Esri and the GIS community, on top of our beautiful basemaps. The web maps support visualization, queries, analytics, and pop-ups for map features with rich content including photos and graphs.

In summary, a story map consists of:

- maps (AGOL maps)
- data
- other information

By their own description, pretty much anything that is made with the Story Map platform would qualify as a story map. But it's curious that there is no mention of story or narrative within these definitions that they provide. In fact it's only once you get into their guide for making a story map that there is some indication of how ESRI defines "story." In Step 1 in "6 Steps to Publishing your Story Map," the story mapper is asked "What is the story you're trying to tell?" And critically, an additional consideration is included: "What are the essential components of your story?" Ah, now we're getting close! Recall earlier that we were working with a definition of story that was made of three components: facts, a narrative path through the facts, and an interpretation of those facts. Here ESRI suggests that these essential components include "maps, photos, videos, text." Story, in ESRI's conception, seems to simply refer to media that can provide context. If we try to fit story as understood by ESRI to our more general definition of story, it's possible to end up with a story map that, in the end, may only contain facts, but be without any narrative structure or much in the way of interpretation of the facts by the author. Indeed ESRI is suggesting an entirely different understanding of what a story is! And so, story simply equals content. And if that content is organized around a map, it is a story map. Since that's more or less what ESRI's Story Map platform guides you to do, essentially everything that comes from the platform is a story map.

Now I do want to take a breather from what probably appears to be some pretty blatant ESRI bashing. I am not suggesting at all that the Story Map platform is bad, that anything created with isn't guided by a more traditional understanding of story is sub-par, or that ESRI's platform is the only one that is perhaps being a little cavalier with their notions of what a story is. Story Map is a good platform that makes it easy to make maps with rich content. If you're familiar with ESRI products, don't want to spend time working outside their ecosystem, or maybe don't have time or interest in programming it's powerful tool to have at your disposal. Also, having perused the ESRI's Story Map gallery, there are some beautiful maps that are informative, but that I would suggest lack much story to them. That doesn't invalidate their worth. Sometimes being informative is all you really need to be. And I stated earlier that I would be using ESRI as an entry point to help me address this question "Where's the story?" I think that ESRI's influence on the way we talk about GIS and mapping means that their jargon should probably be looked at more closely, especially when they start wandering into concepts such as story that are better practiced by a lot of other industries and trades.That said, there are other story mapping platforms, many of which appear to be modeled after the templates that ESRI has made, that I would suggest conceive of story in a similar manner to ESRI. 

## Who cares? ##
By now I'm sure some of you are thinking I'm being a bit pedantic so far. Why does it even matter that we call it a story map? We could call these maps Bob, as long as these platforms can help you communicate the information to your audience that you need to convey, that's probably the most important thing. But I think we miss a great opportunity if we loosen this definition of story to the point where it's just content and information on a screen. I think we can learn some lessons from ongoing discussions in the data visualization field on then merits of engaging a more traditional understanding of story in the communication of information gleaned from data analysis. I know, we might want to think of maps as something special or different, but they do represent a type of data visualization. We use points, lines, polygons, and cells to visually represent the particular instances of and relations among observable phenomena in space. 

## How can we rethink story maps to insure they tell a story ##
- Focus on story first!
- Recognize that maps don't tell stories, people do. Placing content in a geographic context only yields a story once someone can make the connections between that content
- Look to those who regularly practice storytelling
	- Artists
	- Choreographers (Brooke's interview)
	- Movies/TV
- Data Viz is currently having this discussion now and has a lot of good stuff for us to think about in terms of balancing story with exploration

## Putting my money where my mouth is: Telling the story of Scott County's development through transportation ##
[insert process]
[insert story map]


## Spare text ##
### Defining story ###
Perhaps the first one listed here is the most all-encompassing and while seemingly vague, is quite revealing. Breaking down the definition into two parts. In the first we have "an account" and in the second we have "incidents or events." The second part points to some sort of action that has occurred. A story contains some activity and luckily there is an infinitesimal flurry of activity going on every every second in both the real world and in our imaginations. We have a lot of source material to work with! But how do we make sense of it all? What is important? That's where the first part of the definition comes in. We don't have THE account. We have AN account. A story is a a subjective arrangement of those "incidents and events." It requires an author who makes decisions about what events are used, how they are described, and how they are arranged. Indeed the lesser definitions - fiction, lie, falsehood - highlight this subjectivity as a key component of story. 

### Looking at ESRI examples ###
How does this play out? ESRI  categorizes their platform into three broad types templates: Sequential, Place-based Narratives, Curated List of POIs, and Comparing Two or More Maps. Quickly, I'm going to pull up one example from each template type and use them to help us see why the platform doesn't seem to be resulting in stories being told. I suggest we engage in some side-by-side evaluation of these examples  how these story maps evaluate as story maps under ESRI's definiton and a presence of story under Kosara's definition of story. 
show some examples from storied to least storied [Story Map app list](http://storymaps.arcgis.com/en/app-list/ "Story Map app list")

We can see more clearly what ESRI means by story map by looking at their story map templates. 

- Sequential, Place-based Narratives
	- [![Out of the office trip(NZ)](http://www.arcgis.com/sharing/content/items/d08167a71752468a84d8c56617aa3c7f/info/thumbnail/cover_pic_2.png)](http://www.arcgis.com/apps/MapTour/?appid=d08167a71752468a84d8c56617aa3c7f)

- Curated List of POIs
	- [![Cape Cod](http://www.esri.com/~/media/Images/Content/landing-pages/story-maps/conservation-1)](http://gis-services.capecodcommission.org/apps/Buy_Fresh/TabbedStoryMap/index.html)

- Comparing Two or More Maps

### How does ESRI present story maps? ###
- Their answer to "What is a story map?"
	> Story maps use geography as a means of organizing and presenting information. They tell the story of a place, event, issue, trend, or pattern in a geographic context. They combine interactive maps with other rich content—text, photos, video, and audio—within user experiences that are basic and intuitive.
- Breaking down the parts of the definition
	- Geography is the organizing structure
		- This is what most maps are
	- It puts information in a geographic context
		- This addresses setting/where.
	- It combines maps with other media for simple user-experience
		- It allows for other media forms that add context that might not necessarily be spatial