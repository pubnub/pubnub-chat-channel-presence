# HTML5 WebSockets Real-time Chat on Mobile using PubNub's new Global Presence

## Live HTML5 WebSockets App with Presence - Open Source MIT

[Live PubNub Presenece App](http://pubnub.s3.amazonaws.com/rally/index.html)

Click the link above to try the app live!

## More PubNub Channel Presence Links

 - [Read Blog: Announcing PubNub Channel Presence](http://blog.pubnub.com/announcing-pubnub-channel-presence/)
 - [Play Video: PubNub Channel Presence – Introduction – As seen on Hacker News](https://vimeo.com/47541092)
 - [Play Video: PubNub Channel Presence – Introduction](https://vimeo.com/47742118)
 - [Play Video: PubNub Channel Presence – Code Walkthrough](https://vimeo.com/47740670)

![PubNub Channel Presence](https://s3.amazonaws.com/pubnub/assets/pubnub-real-time-channel-presence-global.png "PubNub Channel Presence")

## Channel Presence

Go straight to the [Live Chat App Powered by PubNub Channel Presence]() and
you can also watch the videos and continue reading about
PubNub Channel Presence.  The video links are just a bit further down.
Also you can skip ahead to the code walk-through in this blog to save time if
you already know about PubNub.
Otherwise you can learn a lot more by reading through this article.

If you are looking for the full source code, you are in luck!
This app is Open Source and under the MIT License.
This means you can do anything you want or need with no obligations to
the future or past contributors/creators.
Download the source from our GitHub repository: [Download Source Code](https://github.com/pubnub/pubnub-chat-channel-presence)

## Videos: HTML5 PubNub Chat Channel Presence Series

PubNub is the first Earth Scale infrastructure to innovate
Global User Presence.
Today, PubNub is the only service on the planet that streams Channel
Connectivity and Occupancy Analytics directly to your consumer devices such
as iPhones and Android phones and tablets.
PubNub Presence is a new type of framework that never existed before;
allowing you to be notified with user discovery events
on a PubNub channel instantly.
This enables new capabilities in your app such as User Events with Join/Leave
Status Changes.
PubNub Channel Presence in essence become consumable streams of events,
strait to your device.
The number of active users connected to a PubNub channel is streamed to
you automatically as the number of users actively waiting to receive
data on a channel changes over time.

The Real-time Web for Mobile Apps and Web Apps is undoubtedly a powerful
advent following HTML5 WebSockets, WebRTl and more.
Now with PubNub you can create groups of people and one-to-one apps on all
platforms easily without having to consider technologies or transports as
discussed in Are HTML5 WebSockets the Panacea for Real-Time Data Push.
Channel Presence plays a contending role,
especially paired with PubNub Galaxy and PubNub Pulse.
PubNub Galaxy provides unlimited scale of users on a single channel
(or billions of channels) enabling you to broadcast information and updates
to unlimited number of active users.
PubNub Pulse provides fast and efficient one-to-few messaging
capabilities at a condensed price point.

With PubNub Channel Presence, you can provide Live Real-time stream of
information based on the availability of users on your channels.
You get updated timelines which provide a peek into the past while delivering
an instant activity stream with details about a PubNub Channel at this very
moment in time.

Check it out!
PubNub has a new app to share with you, that is written
and constructed in cross-browser HTML5
and CSS3 code under the MIT License.
The App uses Twitter @Anywhere for authentication and
the user IDs provide a simple
way to join the presence experience via group chat and timeline streams.
You will also be able to see who is online and offline via their
Twitter Account Name and Account Photo.
The MIT App provides a new and elegant interface with quick accessible group
functionality with an inviting streamline appearance rendered in HTML5 and
CSS3 for your Mobile and Web Apps.

## New Dev Console V2

![Live PubNub Presenece App](https://s3.amazonaws.com/pubnub/assets/pubnub-dev-console-v2.png)

As we launch PubNub Channel Presence, we needed to provide a way for you to
debug and learn about the Presence Event Delivery Format.
That's why we've created for you a new and improve Developer Console V2 with
Presence Events built directly into the console interface.
Now you can easily see the data in JSON format as you build your app.
As a bonus your app will become an anonymous user and count as a real person
on your channel to help you debug presence events and occupancy counters.
Learn more by checkout out the new PubNub Developer Console V2.
Also you can see a demonstration of the Developer Console V2
in use in this video: PubNub Channel Presence -
Code Walk-through video on Vimeo.

## Real-time Mobile Apps and Web Apps

Getting devices to communicate with each other is practially free with PubNub
because it is so simple for your team to use our two function SDK.
Yes, you really only need just two functions!
Now that your app is able communicate efficiently, you simply need to answer
the question: "What to do when communication occurs?"
With PubNub you pretty much focus on the User Interaction and in most cases
you are driving UI - User Interface -Updates on a Mobile Phone or Web App.

Real-time allows you to strike a visual appeal creating powerful capabilities
through a user interface experience. Without the interface,
it is hard to understand what Real-time Web really means,
especially in the context of mobile.
The best way to understand Real-time is by producing an actively animating
user interface, constantly changing and updating in real-time as information
becomes available.
This is what PubNub enables.
Coming up Next is our walkthrough of the new MIT
open source app we built for you.

## Walkthrough of How it Works

When something changes someplace on Earth,
you want to be notified the instant this happens.
A trigger is invoked and anyone who is interested in the notification
instantly receives a PubNub message, and this message can be used to update
an interface or log records or make a phone ring or flicker a blinking light
or update text on the screen.

A lot can happen and the possibilities are seemingly endless.
We are going to talk about the app we made and what you can do with it.

## HTML5 and CSS3 Interfaces with Websockets and Real-time Web

You get to do some pretty amazing things with PubNub when
pairing with a User Interface.
We'll go over the code used to create the free app we provided for you to use
any way you need.
You should watch the video: [Play Video: PubNub Channel Presence – Code Walkthrough (SHORT)](https://vimeo.com/47740670)

## Customizing The Interface

Display styling is located in the `default.css` CSS3 file.
You can modify this file to change the appearance.
Some notable sections include the background image:

```css
#main {
    z-index: 50;
    margin: 0;
    border: 0;
    padding: 0;

    position: relative;
    overflow: hidden;

    width: 1024px;
    height: 768px;

    background: #fefef2 url(chat-bg.jpg) no-repeat;

    color: #ffe;
    font-size: 15px;
    font-family: "Open Sans";
    font-weight: 400;
    text-shadow: 1px 1px 1px rgba(0,0,0,0.2);
}
```

This section includes the main background image `url(chat-bg.jpg)`
that is used to set the tone of the chat experience.
You may want to modify this to fit your needs.
The CSS File itself is larger and there is a lot to see.
Thankfully all design elements and styles in the User Interface considerations
have been properly abstracted into the CSS file.

## Main Index File

The `index.html` file will contain information regarding the primary content
and components pieced together such as the Fonts, CSS and JavaScript.
The default Twitter user is defined in this file as well
as all language content.
You can internationalize this file by updating the english
words with replacement variables.

## JavaScript Source Code Intro

We'll discuss the important aspects to the source code here pertinent
to PubNub Channel Presence.
There are two aspects to obtaining Presence Events.
You can stream presence events as they occur directly to your target device
with the PubNub Presence Callback located inside the
PubNub Subscribe Function call.
You can also invoke a "Here Now" call which returns information about the
current state.
Note that the "Here Now" function will give you the full state information of
the channel where the Presence Callback would only stream new events to your
mobile app or web app.

## PubNub Channel Presence Callback

The Presence Callback is located inside the PubNub Subscribe Function as an
optional paramater.
When included in the subscribe function, you will automatically receive
presence events streamed to the specified callback.
Note that we will be using JavaScript as the language to demonstrate PubNub
Channel Presence; PubNub Channel Presence is available
in many other languages.
This is a sample usage in JavaScript of Channel Presence:

```javascript
// Open Bidirectional Socket Connection
PUBNUB.subscribe({
    channel  : "my_channel", // Channel Name
    connect  : connect, // OnConnect Callback
    callback : chat,  // Received Message Callback
    presence : presence // Presence Callback
});
```

As you can see the Presence Callback refers to a
JavaScript Function Reference.
The event information will pass to you in the following Format when
a User Joins the Channel:

```javascript
{
   "action":"join",
   "timestamp":1345546797,
   "uuid":"175c2c67-b2a9-470d-8f4b-1db94f90e39e",
   "occupancy":2
}
```

Next you need to know about the format when a User Leaves a Channel:

```javascript
{
   "action":"leave",
   "timestamp":1345549797,
   "uuid":"175c2c67-b2a9-470d-8f4b-1db94f90e39e",
   "occupancy":1
}
```

Notice that the occupancy number updates as expected.
The uuid section is a programmable ID that is associated with each user.
You can set this to whatever you need it to be in order
to identify your user.
When you init the PubNub instance,
you can set the UUID as an optional paramater.
The default value is a random UUID.

```javascript
// Setup Connection Based on User Data
// This will provide Connectivity References
var PUBNUB = PUBNUB.init({
    publish_key   : 'demo',
    subscribe_key : 'demo',
    ssl           : false,
    cipher_key    : '',
    uuid          : "YOUR UNIQUE USER ID HERE!"
});
```

With this example you see that you can set the UUID to anything you need.
This UUID value will be transmitted on Join/Leave events;
and also the here_now function.

## PubNub Channel Presence Here Now Function

The PubNub Channel Presence Here Now function provides you the ability
to answer the question: "Who is here right now?".
You will receive a list of UUIDs as well as an Occupancy number.
Here is an example of how to use the Here Now function:

```javascript
// Get List of Occupants and Occupancy Count.
function connect() {
    p.here_now({
        channel  : channel,
        callback : presence
    });
}
```

You pass in the channel name and the callback function to be used to send
the data to.
The Here Now data response will look like this:

```javascript
{
   "uuids":[
      "UUID1",
      "UUID2",
      "UUID3"
   ],
   "occupancy":0
}
```

As you can see you get a list of UUIDs of your users.
The UUIDs will either be randomly generated for anonymous users or will be
the UUIDs you supplied when you initialized the PubNub instance.

And now you know the basics for the PubNub Channel Presence with JavaScript.
Note that other Language SDKs wil provide similar interfaces with easy
copy/paste documentation on our GitHub Repository.
Checkout your source code for the PubNub API GitHub Repository.

Check us out at
[DevLink this August, 2012](http://devlink.net/Conference/Sessions.aspx)
where we will talk about PubNub Presence
and other amazing Real-time solutions:

## Building Real-Time Apps for Mobile and Web

You will Learn to build Real-time Messaging for Business Class Apps using
the best technologies available.
Live App under MIT Open Source License will be revealed.
We will cover DIY options and ready-made solutions for building applications
that communicate on the real-time web for mobile and tablet apps.
You will discover the intended use cases for AJAX, WebSockets and
Long Polling as we build an application in this session.
You get to understand the ubiquity of HTML5 and CSS3 on Mobile and Web for
interface development.
You will leave this session with a cookbook on making interactive
applications that communicate using the Best Mobile and Web Technologies
Available including PubNub and HTML5.


