# FAQ
## What is a public room?
Public rooms are accessible to anyone who knows about your room code. Other people who visit Salad Room on the same network (on the same WiFi) as you will also have access to your room.

Public rooms are **not** listed on search engines. There is **no** list or directory of public rooms.

## How is my data stored?
File data is stored in [Amazon S3](https://aws.amazon.com/s3/). Message data is stored using an in-memory store.

## Why does Salad Room upload files to a server and not use P2P?
WebRTC is great. But to keep this service simple and reliable, particularly on mobile, I've opted to just upload and download files.

## How long do files stay on the server?
Files can remain on the server for up to 24 hours. Files will not be publically accessible after the expiration time.

## How long do rooms exist for?
Currently they last about 30 minutes before needing to be recreated.

## Is Salad Room secure?
Salad Room has basic security like HTTPS and server-side file encryption, however, this service isn't designed to be used to send truly sensitive information.

## How does it automatically put me in the same room when on the same network?
Salad Room uses a [hashed](https://en.wikipedia.org/wiki/Hash_function) version of your IP address to create and match rooms. Your IP address is never stored in plain text and only part of the hash is used to find rooms.

## Is Salad Room good for sending massive files?
Nope. Other services will be better and more efficient for that!

## How is this free?
I think Salad Room has niche appeal and won't be used by a lot of people. Thus it isn't currently costly to maintain. If enough people find this useful and also want to pay me money then I'll add a paid plan.

## How can I help support this service?
For now, you can support me by following [me on Twitter](https://twitter.com/anthonyec) or [buying me a coffee](https://www.buymeacoffee.com/anthonyec) (I don't drink coffee but you know, it's the gesture).

## Do you track analytics?
Salad Room uses privacy focused analytics that collected basic information, e.g visitor count, unique visitors, aggregate button clicks.

## What are the limits?
For each room, the limits are as follows:
- 25 participants
- 2GB per file
- 4000 characters per message
- 50 messages per room

## Why isn't Salad Room open source?
Currently I don't have the time to maintain a [FOSS](https://en.wikipedia.org/wiki/Free_and_open-source_software) project. And I'd also like to see if there is a chance people would be willing to pay for advanced features.

If that doesn't work out then I might look into it.

## Are there any alternatives?
Yeah, and they are great! Check out [fileroom.io](https://fileroom.io) or set up something yourself with [Yopp](https://github.com/josephernest/Yopp).

## Where can I give feedback?
Sure, feedback is greatly appreciated! DM [me on Twitter](https://twitter.com/anthonyec) or send an email to [support@saladroom.net](mailto:support@saladroom.net).

## Why is this called Salad Room?
Well, you see...

