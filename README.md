<div style="text-align: center;">
<img src="media/auth_logo_large.png" alt="Auth Logo" width="200"/>
</div> 

---

Auth is an iOS app that allows users to verify their content online. With recent advancements in generative AI, almost anyone has access to tools that allow for the creation of highly realistic images, videos, and audio. This may potentially cause harm to creators, public figures, and content consumers, leading to misuse of identity to spread misinformation. Auth aims to mitigate this problem through content verification.

I got the idea of creating this app after listening to a [podcast interview with Daniel Ek](https://open.spotify.com/episode/671O5v5twrIfApPuyBdJTv?si=ea4d6b660991441a), CEO of Spotify, talking about the opportunities and challenges of generative AI with Acquired hosts Ben Gilbert and David Rosenthal.

<img width="599" alt="aquired-daniel-ek" src="https://github.com/blankdays/AuthApp/assets/169615361/a55d818c-9126-4867-8ff5-25710bb7d479">

---

Any person or organization can create an Auth account. To make a post or verify content, the user must have verified their identity through the app. Once verified, an 'Auth badge' appears on their profile picture. A user who is not verified can still benefit from Auth by exploring and searching for content verified by others, such as politicians, public figures, and content creators.

> ### Demo: Creating a Post on Auth
>
> Daniel has finished recording a podcast episode with Emma, a local politician who is running for mayor. To showcase to his listeners that Emma was actually present in the episode, Daniel wants to create a post on Auth. He signs into his Auth profile and navigates to the post view. Here he views the posts other users have prompted him to verify, and in the other tab, the posts he has created that are yet to be verified by the linked users.
>
> He creates a new post by clicking the plus button. He is navigated to the create-post view. Here he has the option to add a title and information about the content he wants to verify. He must add at least one link to the post. In this case, the episode is posted on Spotify and YouTube, so he adds the links pointing to the episodes on these platforms. Daniel also adds Emma using her unique Auth hash. He then clicks post.
>

https://github.com/blankdays/AuthApp/assets/169615361/8dd93cf7-8c8b-40a7-8d9a-6022d2dca830

> ### Demo: Verifying a Post on Auth
>
> The post appears under Daniel's posted-but-yet-to-be-verified tab in the post-view. Here he can edit and delete the post if desired. The post gets published once all verifiers have verified the post. In this case, it is just Emma.
>
> Emma now signs into her Auth profile. Emma has also verified her identity, as indicated by the badge on her profile image. She navigates to the post view and to the to-verify tab. Here she can see the post just created by Daniel. She may click on the links to view the content Daniel wants her to verify. Since she was actually present during the interview and approves of the content, she clicks accept.
>
> The post now appears under both Daniel's and Emma's Auth profiles for other users to see.
>

https://github.com/blankdays/AuthApp/assets/169615361/e1ca5df3-aea6-4a98-bd8c-3c2fa4abcd21

---

> ### Demo: Viewing Verified Content
>
> Users, regardless of being verified, can use Auth to view verified content. A product of the verification process is the aggregation of different types of content across different platforms. For example, a user who wants to know more about Emma may seek Emma's Auth profile, knowing that the links in the posts on her profile point to content Emma has verified. This user may choose to follow Emma, and Emma's posts will show on the user's feed.
> 
> Anything that is shareable can be verified on Auth, and users can share Auth posts. For instance, if a user wants to share a specific part of the podcast episode with Daniel and Emma on another platform, like TikTok, they may include the link to the Auth post in the TikTok post's information section. Users can then navigate to the Auth post to access the links to the entire episode.
>
> A benefit of the verification method is the ability for more people to get content linked to them on a single platform, similar to how you get tagged in a photo. If you have an interest in a particular person, you may seek their Auth profile to see all the content they have verified across various media and platforms such as YouTube, Spotify, news providers, and more.
>

https://github.com/blankdays/AuthApp/assets/169615361/ad53f21f-998f-4614-8305-ddc2ec9def71

---

The real value of Auth is created through partnerships with other platforms. I am therefore developing a set of APIs that will allow third-party platforms to query whether content on their platform has been verified. For instance, newspapers and editorial offices may use the API to enhance the integrity of the content they share with their readers. At publication, they include the hash of the users whose content they want to verify, and a badge appears on the site of the publication. The verifiers get prompted to verify the publication through the Auth app. Once done, the badge will display the name and image of the verifiers, as well as links to their Auth profiles. The publication will also be shown on their Auth profile like a regular post.

If you have any questions about the project, feel free to contact me via [email](mailto:didriksummer2024@gmail.com).

---
