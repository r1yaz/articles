# Balance between privacy and usability + WhatsApp Analysis

# My thoughts first

This is a detailed analysis of whatsapp vs telegram vs signal in a technical and privacy centric manner. Before that, I'll state the TLDR below for those

## TLDR

WhatsApp is fishy 🎣 and cannot be trusted.

# Philosophy

I think that it would be good to have a balance between your desire for privacy and your comfort/usability/accessibility. By that, I mean that we should have some good access to the latest messaging apps and other apps but at the same time have a very good control over our privacy.

I'll state two examples of the either sides where one person either gets too paranoid about their own privacy and ends up isolating themselves from apps and any other thing service which provides accessibility and the other who does not care about their privacy and thus uses all the apps and accessibility services out there including social media and gives away all his information just like that.

In the first case, that is not a healthy way to live. You end up being too paranoid and everything around you seems like it's out to get your information/data. You will have to consciously spend quite a bit of effort to avoid giving out any information anywhere you go and that will drain you constantly and slowly.

In the second case, you give out so much information that anything could happen to you if a person knows where to look for

- If you are going out to a mall and you check in in Facebook ⇒ you are not at your house ⇒ that is an open invitation to every thief in the area to try their luck past your house's security system (and if you do not have any, good luck)
- Say you are looking to buy a car or something. That means the insurance salesmen and bots out there in the net will know that by the sheer volume of information you give out for free and increase their prices for insurances just for you. This is possible. And it is happening in some places around the world. What a scary world to live in where a system knows what you want before you do yourself?

# Whatsapp

Say there is a company called F. And that company develops a product called W. F is known for it's horrible reputation when it comes to privacy and data breaches (Cambridge???). Almost every year, there are countless instances where F is caught in data leaks and scandals. In addition, many pay attention to the company’s close interaction with government agencies and commercial organizations. For example, in 2018, F, which is coincidentally Facebook, disclosed data of about 87 million users — TO THE GOVERNMENT.

Quoting, "It comes after the Observer revealed that Cambridge Analytica, which worked with Donald Trump’s election team, acquired millions of profiles of US citizens and used the data to build a software program to predict and influence voters."

Who's to say that won't happen in India? Who's to say it isn't already happening in India?

More [https://www.marketwatch.com/story/facebook-prepares-to-reveal-the-87-million-accounts-affected-by-privacy-violation-what-to-do-if-youre-one-of-them-2018-04-09](https://www.marketwatch.com/story/facebook-prepares-to-reveal-the-87-million-accounts-affected-by-privacy-violation-what-to-do-if-youre-one-of-them-2018-04-09)

I'll go into the technical details here

1. Backup messages are not encrypted
    1. The creators of WhatsApp rely on end-to-end encryption as the primary method of data protection. However,  not many people know that backups of our messages are stored on the devices without encryption: Android users have Google Drive, and iPhone users have iCloud. Why is this happening? Because the messenger encrypts the sent message, and 
    only the sender and recipient can decrypt it. Once it is read and decrypted, it is no longer protected by any encryption.
    2. Whatsapp is free. But, nothing is free in this world. Think about it. How is whatsapp free?

I've gone through the entire privacy policy document by whatsapp. Let me show you some of the things which will make you go.. wait what?

Let us look at the information they collect first

![WhatsApp_Image_1](https://github.com/r1yaz/articles/blob/main/Privacy_Articles/metadata/WhatsApp_Image_1.png?raw=true)

You provide us the phone numbers in your mobile address book on a "regular basis". Good. So they have access to ALL of your contacts (yes, even the ones who are not on WhatsApp)... do i need to say anything further?

![WhatsApp_Image_2](https://github.com/r1yaz/articles/blob/main/Privacy_Articles/metadata/WhatsApp_Image_2.png?raw=true)

This is super awesome. All the photos you sent, the videos, are stored on WhatsApp servers despite them telling they don't because they "may".  The very way in which they explain this is.. not clear. Which means.. they are beating around the bush.

![WhatsApp_Image_3](https://github.com/r1yaz/articles/blob/main/Privacy_Articles/metadata/WhatsApp_Image_3.png?raw=true)

"may". "May" do this. "May" do that. Anyways, it is clear here that they are processing all your contacts to "help" your organize how you communicate with others. Can't we do that ourselves? Just read it again. It is super super fishy. Like every other policy above.

![WhatsApp_Image_4](https://github.com/r1yaz/articles/blob/main/Privacy_Articles/metadata/WhatsApp_Image_4.png?raw=true)

I don't really need to explain any of these but

- They collect information about what you do in the app and how you interact with it. Your messages, what you message, who you message more, etc are all a part of your activity.
- If you are using whatsapp pay, forget privacy. All your bills are sent to them.
- Your entire list of device information is collected. OS, IP address, LOCATION DATA (a no-brainer).
- They try to tell that we collect location data only when you share it but the moment your location is on, they are collecting it. No doubt about it.

![WhatsApp_Image_5](https://github.com/r1yaz/articles/blob/main/Privacy_Articles/metadata/WhatsApp_Image_5.png?raw=true)

Come on. Anyone who has your phone number in their number book is sending information about you to whatsapp. Funny thing is.. they're talking like "you poke him in a similar way he pokes you".

![WhatsApp_Image_6](https://github.com/r1yaz/articles/blob/main/Privacy_Articles/metadata/WhatsApp_Image_6.png?raw=true)

Don't trust their "third party providers" because they do not mention their name. Further, if they say "may" don't trust it. Your data IS being shared with third party providers to form a profile of you which may or may not in the future (don't trust me when I say may) to target you based on advertisments and what not.

The gist is this. Whatsapp is doing shady stuff. No doubt about it.

[https://www.whatsapp.com/legal/privacy-policy](https://www.whatsapp.com/legal/privacy-policy)

Read the entire thing. I can go on typing about it on and on and even give a talk for an hour and a half about the document and how shady it is. The article will become way too long if i keep taking screenshots and sharing my views on it but there is more. And i will do so. See this - 

![WhatsApp_Image_7](https://github.com/r1yaz/articles/blob/main/Privacy_Articles/metadata/WhatsApp_Image_7.png?raw=true)

It is pretty clear what they are saying.

![WhatsApp_Image_8](https://github.com/r1yaz/articles/blob/main/Privacy_Articles/metadata/WhatsApp_Image_8.png?raw=true)

Ahh, finally they mention about the ads and relevant offers. It goes like this - you use whatsapp - they anaylze that information and push to facebook - and then use that to show you relevant ads.

![WhatsApp_Image_9](https://github.com/r1yaz/articles/blob/main/Privacy_Articles/metadata/WhatsApp_Image_9.png?raw=true)

All your data is being shared with the above companies and even more which are not listed and are named as third parties.

Note that customers in California and Brazil have different policies because the laws there are strict.

In the meantime, do read the privacy policy yourself with the mindset of "If I owned WhatsApp and wanted to hide the fact that I collect information and share it for money, how would I frame my policy document".
