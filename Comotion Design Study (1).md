#CoMotion Bridge Design Documentation
##What's in a name?
The original ideation and collateral produced and delivered to Roosterpark referred to the key problem that then C4C program users and administrators had identified as 'Gap Learning'. Gap Learning was defined as the informal education and tools that assisted members of the UW community to gain the knowledge, connections, and experience necessary to translate their academic interests into commercial opportunities. As we began to brainstorm and synthesize a vision that would allow CoMotion to reach this goal we recognized that by focusing on the problem, a 'gap' led to ideas that did not grow with the visions expressed in our meetings with the CoMotion executive team.

We feel that framing the description of the program on the successful solution of 'bridging the gap' that exists for the members of the UW Innovation Community we can affect a sense of purpose and growth that acknowledges the principles of hard work, failure, and striving to reach goals that are pivotal to the success of entrepreneurs. For that reason, this document will refer to the product as the **CoMotion Bridge** Program.


#Exploration of CoMotion Personas

##Who are the users?
The users of the CoMotion Bridge application are varied and diverse. They range from corporate executives and entrepreneurs seeking access to the IP and innovation at the UW to the students seeking to understand how they can transition their academic knowledge into 'real world' applications. In this iteration of the CoMotion Bridge design phase we have defined three key personas from which to build the foudation of the CoMotion Bridge Application.

Each of the personas below have different incentives and goals for engaging with the CoMotion Bridge application. We have simplified the more detailed groups of into four key personas, three with focus on the users of the the system, and one which represents the needs of the CoMotion staff.

##Personas
###Innovators 
Comprised of researchers, post­doc students, undergrads, and faculty who are likely to seek engaging with CoMotion to transform their research or academic interests into marketable businesses. Innovators are comprised of researchers, post­doc students,  undergraduates, and faculty seeking to engage with CoMotion to transform their research or academic interests into marketable businesses, as well as those who would like to actively contribute to the projects of others.

>**Key Need:** To translate academic knowledge and experience into real world knowledge and experience. 

###Partners
The various members of the business community or UW faculty who engage with innovators to take their ideas from academia into the market. They represent the mentors, entrepreneurs in residence, and faculty advisors that partner with innovators.

>**Key Need:** To find new innovations and innovators who can form the basis of vibrant new businesses.

###Catalyzers  
Consultants, lawyers, and businesses which provide goods and services to catalyze the process of translating the work of innovators and their partners into entrepreneurial endeavors.

>**Key Need:** To build future advocates and lasting relationships with trendsetters early in their career.

###CoMotion Staff
The CoMotion staff make up another unique group of users who have needs that are the most different from the community. They will be provided with abilities to create content, moderate users, and monitor and review usage and other analytics.

<p></p>
>**What about different users in each persona?**
>  We recognize that within each of the persona groups outlined above there are potentially widely divergent goals and needs. We have chosen to simplify to three key groups to facilitate the design of an application that reaches the most general needs first. As the product continues to grow and evolve we will refine each persona and design and develop features to address concerns unique to more specific users within each persona.

##Five Motivations of CoMotion Users
Below are five key motivations that we feel drive the desire of the users to engage in the CoMotion community. We will use these needs to define the foundation for the application design presented in the following sections of this document. As the design process progresses we will write user stories that address the unique needs of each persona/user and tie them back to these five motivations.

###The Five Key Motivations
1. Find and create connections within CoMotion Community.
2. Create or expand economic opportunities.
3. Advancing understanding of entrepreneurship, business formation, and innovation at UW.
4. Gain experience in their fields of interest.
5. Receive public recognition for contributions to the UW innovation community and the business community at large.


#From motivations to needs
The five motivations defined above have been further simplified into two basic needs that we will use to define the high level features for the CoMotion Bridge program. From these two needs we can begin synthesize the high level features brainstorms and documentation created to date into feature sets and high level scoping for technology that will be developed for this program.

##The Two Basic Needs
> **Knowledge:** 
> Acquisition of pertinent knowledge about 'real world' entrepreneurship, innovation at UW, and services provided by the CoMotion program at the UW. This need is strongest for innovators, but also applies to partners seeking to leverage UW IP.
<p></p>
>**Connection:**
>Finding and making the human connections necessary to leverage the knowledge and experience they possess to reach their personal and professional goals.

The feature explanations and scoping in the following section will be separated into two unique 'systems' that meet the needs of acquiring knowledge and making human connections. By enforcing this 'separation of concerns' we can assure that we clearly define and scope the features that meet the needs of both knowledge acquisition and connection. 

#Project Scoping Methodology
In this section we will define the high level scope of an initial product development and design phase, or Minimum Viable Product (MVP), as well as the scope of features that can be added into future iterations of the product. Each section below will contain textual descriptions of the scope of the MVP features, followed by a list of these features. Descriptions of future feature candidates is included after the definition of the MVP scope. Appendix A: Features Prioritization provides a full breakdown of the features prioritization and will form the basis of the next phase of design investigation and prototyping.

#The Need for Connection(s)

At the foundation of the social experience is the creation of community. The CoMotion Bridge Social Network will focus on presenting all users with the opportunity to create social connections which grow the community and lead to a more cohesive and accessible network of people, businesses, and projects. 

> **The CoMotion Bridge Connection**
> A private social network with group and team building features.

##Community Building
Creating communities is hard. It requires not only social intelligence and the ability to find and engage with others, but the introspection necessary to know which communities will be a good fit for an individual. CoMotion is facilitating this challenging task through a painstaking manual process that requires the personal knowledge of the CoMotion staff to make introductions, suggest mentors, and filter incoming and outgoing messages. This system, while very effective, can not be scaled to serve the larger UW student body nor the over 10,000 strong community of entrepreneurs and businesses interested in the UW innovation community.

Below we break down the process of community building into four key steps, joining the community, exploring the community, sharing your talents, and making it 'your' community.

###Joining the community
Joining the CoMotion Bridge community is the first step to gaining access to the wealth of knowledge and connections that are available to the UW innovation community. To join the community, users will be asked to create a unique personal profile with information about their interests, current projects, and what types of opportunities they are seeking. The information users provide in their profile and the signup process will be used not only to help others find them, but as the first step in the process of engaging within the community.  

Upon successful completion of a user profile every user will be presented with a short list of members of the community that share similar interests, goals, or are open to the types of interactions the user is seeking.

>**Key Feature:**  User profile that defines one's goals for connecting.
 
###Exploring the community
The second step in building a community is to assist the community members in finding other members of the community and understanding what their interests are. The CoMotion Bridge Connection app with do this by allowing a user to request connections to another user. When the other user accepts a connection this will open a channel to direct communication.  

In the future, the recommendations engine is likely to integrate quizzes, personality tests, and user interactions into a matchmaking system similar to that found on the social dating website 'OkCupid.com'. Because many of the features of this sort of matchmaking are experimental and will require great attention to detail, these will not be included in the initial version of the CoMotion Bridge Connections application.

>**Key Feature:** Finding other members and creating new connections.

###Sharing your talents
To begin the process of making the community one's own it is necessary to be able to reach both wide audiences and individuals. The CoMotion Bridge Connections application will implement the ability to directly message other users, post information publicly to the wider CoMotion community, and to communicate within groups.  

To prevent any member from being overwhelmed with direct communications several models will be investigated. These will range from providing limited amounts of unsolicited direct messages to the creation of 'virtual social currency'. 

>**Key Feature:**  Direct messaging and broadcast communication. 

###Making it 'your' community
The final step in community formation is to begin to take ownership of your role and place in the community. This is accomplished through the creation of groups/teams which are focused around a common passion, need, or vision. These groups may manifest as project teams, study groups, or entrepreneurial endeavors that eventually grow to become start-ups and businesses. 

CoMotion bridge will provide the users with the ability to organize into groups, to maintain light weight communications tools for communicating within their groups, and to make public the goals, members, and other information about their group to the wider UW innovation audience.

>**Key Feature:**  Group creation and private group communication.

###High Level Scoping of MVP Features
* Individual Social profiles for all CoMotion community members.
* Finding community members via search and shared interests.
* Ability to 'connect' to other members of the community.
* Ability to directly message connections
* Limited ability to message users to whom you are not connected.
* Group/Team creation profiles.
* Group/Team private communication tools.

###Future Enhancements
####Personalized Connection Recommendations
With the power of a social graph in hand, there are numerous modes of recommending connections between members in the social network. Some examples of these mechanisms include the ability to recommend meetings to other users, recommendations by profile similarity, recommendations based on recent activity, and recommendations based on attendence of events. 

#### Intelligent matchmaking services
At present the CoMotion staff is presented the daunting challenge of learning about the unique desires and personality traits of all the Innovators and Partners who they engage with. They use their experience with each to attempt to facilitate matches between innnovators and partners that are likely to reduce the friction to creating great new businesses. While highly effective, this method can not be scaled to reach the broader UW audience. 

We will investigate the process and methods of the CoMotion staff to understand what the key metrics and indicators are in their current manual process, translate these into measurable data and then attempt to apply machine learning techniques to create a unique recommendation engine for 'blind matchmaking'. 

>**Risk Assessment:** This feature will require highly trained machine learning experts as well as process analysts and consultants to develop. 

####Incentivizing Failure
>"It's fine to celebrate success but it is more important to heed the lessons of failure."
[**Bill Gates**](http://www.investinganswers.com/education/famous-investors/50-quotes-wealthiest-man-america-3088) 

It is common to see all forms of praise for success, but what is often overlooked is the long hard road paved with failures that lead to success. We will research various methods for recognizing the hard work of individuals and groups, to create badges and other public acknowledgements of the completion of projects, not just the success of projects.  The specific means by which we will incentivize CoMotion Connections members will require further research and design.

####Solicited feedback about social interactions
One of CoMotion's internal goals is to allow for honest and direct feedback about the interactions between community members who engage in CoMotion programs. We will investigate non-invasive methods of gathering feedback about the subjective rating of interactions between innovators and partners, and provide means of highlighting both highly successfully and potentially challenging community members. This feature will initially focus on converting subjective feedback into data which the CoMotion Staff can use to assess the success of students and mentors who create partnerships and/or mentor-mentee type relationship in the CoMotion Connections community. 

####Social Graph Visualization
Visualizing the full set of connections amongst the CoMotion Connection community may allow for users to find other members whom they may not have otherwise been exposed to. It also allows users to explore the connections within the group and understand how the community is connected.

####Novel Modes of Creating Connections
The social networking space has recently begun to expose many new and novel modes for assessing mutual interest in connections. Because of the ubiquity of location aware smart devices services such as [Weave](https://itunes.apple.com/us/app/weave-local-professional-networking/id788443696?mt=8) have cropped up that allow members to scan for other members in their general vicinity, provide them with information about each other, and allow users to 'swipe' to express interest in meeting a member. If two members both rate the other member as 'interesting' then the system connects them together and facilitates further discussion.

>**Risk Assessment:** The current state of  location aware applications in web based platforms is unlikely to provide the level of quality that a user expects in a social matching application. For this reason, this feature will require creation of a native smartphone application to be successful.



#The Need for Knowledge

Translating academic pursuits, personal research and intellectual property, and personal experience into actionable real world businesses can be challenging for even the most driven individuals. It requires understanding complex financial instruments, the level of one's own knowledge and experience, and significant knowledge of the domains one is interested in pursuing. Much of this information can be found through start up forums ( news.ycombinator.com ), user groups ( cascadia ruby ), online courses and publications ( stanford's startup course, coursera ), even print publications ( Inc, Fast Company ), however, few, if any of these modes of delivery attempt to help the user determine what information will be most helpful to them where they are now. 

>**The CoMotion Bridge Knowledge Base**
>A content management system with recommendation features.

##Basics of the Bridge Knowledge Base

At it's heart the Bridge Knowledge Base will be a publishing platform that allows the CoMotion team to curate, organize, and publish content that bridges the gap between academic curricula and the 'real world'. The knowledge base will be content type agnostic, meaning that it will allow for the creation and inclusion of numerous forms of content deliverable with modern web technologies. 

###Content Types
The platform will be populated with content of the following types:

####Media:
* Short and long form video content ( via youtube, vimeo, etc ?)
* Short and long form audio content ( podcasts + soundcloud )

####Text and Documents
* Text content published and stored directly in the platform.
* Curated external content ( documents and links ).

####Events
* Lectures / Speaking engagements
* Entrepreneurship Skills workshops 
* Pitch contests
* Hackathons and other product creation contests
* Publishable Events Calendar ( publish to RSS, iCal, google etc)

Events are a unique type of content that will include a location and and time component. Each event will be published to one of a number of  calendaring solutions such as google calendar, outlook, as well as being published via services such as RSS. This will  allow users to subscribe to and receive updates about events in the mode that is most applicable to them.

####Micro Courses 
Users of the Commotion Knowledge Base are likely to need assistance in assessing their current level of knowledge, and knowing the logical next steps they should take to grow. Micro Courses will be sequences of content curated by the CoMotion staff to assist users in exploring subjects that build upon each other. We will create a means of allowing the CoMotion content creators to create unique 'Micro Courses' by linking existing Knowledge Base content together into an ordered 'course'. A simple 'progress' mechanism will be provided that tracks a user's progress through the course.

###Finding the Right Content
From day one it will be possible to perform keyword searches on the text portions of all content in the knowledge base. Additionally, the ability to create 'Microcourse tracks' will also be supported to allow for curating content into themes, or tracks, that help to organize content and give the users a sense of direction and hints about what areas to explore next. Content will also contain user generated metadata about popularity , quality ( ratings), and subject matter (tags). A means for recommending content to a user based on their interests and activities in the knowledge base will be investigated. 

###Content Metadata
All content is not created equal, and all content will not pertinent to the interests of all users at all times. To help users navigate the content three metadata elements will be added to each piece of content. 

####Popularity ( View Count ):
 A numerical count of the number of times the content was viewed by users of the Knowledge Base. This will provide a proxy to usefulness or popularity.

####Rating: 
A subjective estimation of the quality of the content, by the users. 

####Tagging: 
The ability to add keyword tags to all pieces of content. These tags will provide additional input to keyword searchs, filters, and provide data that can be used by any content recommendation engines.

By including this metadata as an integral part of each content piece we can provide progressive enhancements will be allow for the creation of services that leverage this data to recommend content to users, create reports which can be used to evaluate content creators and expose needs/desires of the users, as well as provide data that can be used to do analysis of usage of the application.


###High Level Scope of Knowledge Base MVP Features
* Provide centralized repository of audio, video, text, and mini course content
* Provide centralized events and events calendaring functionality.
* Ability for CoMotion staff to create, edit, and delete content.
* Keyword search of all knowledge base content.
* Provide interface for capturing quality rating and keyword tags.
* Recommendation of content based on rating, popularity, and tags
* 

##Future Improvements to Bridge Knowledge Base

###User Generated Content
Initially it is planned that all content creation for the Knowledge Base to be handled by the CoMotion staff and curriculum creators. As the system matures, adding the ability for users to create content of their own to add to the system will be investigated. 

###Content Recommendation
Initially the quanity of the content is likely to be manageable for users to navigate. As the content in the knowledge base grows, particularly if UGC is enabled, the sheer quantity will quickly overwhelm the simple

###Badges and Achievements
As an incentive to engage with the content, complete the educational minicourses it was suggested that a system of achievements be used to gamify the various educational oppportunities presented by the Bridge application. A distinct strategy to award users who actively create, curate, review, and complete content can be created.

###Location Aware Content
Some content, events in particular, are inherently associated with locations and the fact that most users have a mobile device which is capable of being location aware opens the possibility of giving live notifications for events or other members in the location of the user. 

###Notifications
As the content library grows, content is updated, or UGC elements of content are added ( such as comments ) the ability to notify a user via email or on a mobile device can be added.

>**Risk Assessment:** The current state of  location aware applications and push notification to mobile devices in web based platforms is unlikely to provide the level of quality desired by the user. As such this feature will require creation of a native smartphone application to be successful.

###Tests, Surveys, Quizzes
There is a plethora of valuable information that deals with both personal introspection ( Myers Briggs, Eneagram, Gallup StrengthsFinder ) and allows users to understand more about others. Sites such as OKCupid.com have been wildly successful at using these tools to gather information about users and utilizing it to improve their matchmaking algorithms. Additionally, a general system for creating content of this type could also be developed to allow for integrating custom 'tests' and 'quizzes' into mini-courses.

#Features Prioritization
This section features an an initial prioritization of the high level features for the Bridge Knowledge Base and the Bridge Social Networking application. The feature names used below map directly to the names of the features in the 'Scoping' section in the document above. 

##Minimum Viable Product Features
Below we separate out a set of features that form the core of a minimum viable product. We believe that without these core features should be built before any other features are added. As such they are grouped together into MVP feature sets and treated as a single 'feature' in the prioritization lists below.

###Native Mobile Features
Some features defined in the scoping document will require a native mobile application to be incorporated in a manner that will be useful to the users. In general, any features which rely on location or push notifications to mobile devices will require a native mobile application to be developed. 

##CoMotion Bridge Connect Social Network
### MVP Features
- User profile
	- Photograph
	- Contact information
	- Major / Field of Interest
	- Current Role / Position
	- Desired or Available Role ( mentor, maker, angel investor, etc)
	- Academic or Business Interests
	- Skills / Proficiencies
	- Goals for connecting ( to contribute to project, to find an investor for IP )
	- Groups / Organization
	- Connections
- Search for users by name, keyword, email
- Create a connection between users ( similar to facebook friend action )
- Send direct messages to connected users
- Limited ability to send direct messages to unconnected users
- Status posts ( similar to facebook wall)

###Group Social MVP Features
- create new group
- invite members to group
- Group Profile
	- Group name
	- Group members
	- Group mission 
	- Group type ( project, student group, project team, start up, advisory group, other)
	- Group needs ( seeking legal services for incorporating as a business)
	- Public status ( similar to facebook wall )
- Search for group via keyword, user, and email of user involved
- display group membership on member profiles
- Private group communication space ( similar to facebook group wall )

##Social Network Features in Priority order
**MVP:** Social Basic Features
**MVP:** Group Social Basic Features

####Future Enhancements in Priority Order
 1. Personalized Connection Recommendations
 2.  Intelligent matchmaking services
 3. Incentivizing Failure 
 4. Solicited feedback about social interaction 
 5. Social Graph Visualization
 6. Novel Modes of Creating Connections

####Features which require native mobile application
1. Location Aware Modes of Creating Connections ( weave style, A views B gives +, B views A gives +, system recommends they meet)


##CoMotion Bridge Knowledge Base 
###Knowledge Base MVP Features:
- ability for CoMotion Staff to create new content
- creation of following content types
	- video
	- audio
	- documents ( pdf, doc, ppt )
	- text entries ( testimonials, etc )
	- external resources ( podcasts, links, etc)
	- events ( with organizer, location, and date/time, attendees )
	- mini-course tracks
		- collections of content with a prescribed progression
- keyword search of all content items
- publishing of all events to one or more event calendars
	- google calendar
	- outlook
	- RSS feed
- content metadata
	- popularity ( view count )
	- user rating
	- keyword tags


##Knowledge Base Features in Priority Order
**MVP:** Knowledge Base MVP Features

####Future Enhancements in Priority Order
1. User Generated Content
2. . Content Recommendation
3. . Tests, Surveys, and Quizzes
4. Badges and Achievements


####Features which require native mobile application
1. Location aware content
2. Push notifications

