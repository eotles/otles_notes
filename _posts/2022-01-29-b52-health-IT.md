# What Can Healthcare IT Learn from the B-52?
[Erkin Ötleş](https://eotles.github.io) <br />
January 29th 2022

Topics: Healthcare Information Technology, Maintenance, Upgrades, B-52, Technical Debt, Total Cost of Ownership <br />
[PDF Version](b52_health_IT.pdf)


A lot of aviation videos show up on my YouTube feed (thank you, [DarkAero](https://www.youtube.com/c/darkaeroinc) team). A video that popped up recently was about the Boeing B-52 Stratofortress (B-52) engine retrofit project. According to wikipedia the B-52 is a “long-range, subsonic, jet-powered strategic bomber” that has been used by the US Air Force since 1955. [1] Despite being designed and built 6 decades ago, the US Air Force still uses these planes and plans on using them well into the future. This desire to keep using them into the future is where things get interesting and we in healthcare IT can learn some lessons.

![image](https://user-images.githubusercontent.com/6284187/151667024-47aad415-ee6e-4138-a166-f2a321d8d09f.png)

As an aside, my personal belief is machines like this are pretty odious. I like machines, I like making physical things, and I like planes. But when the thing in question is expressly designed to kill people and destroy property, I start to have some problems. Obviously there’s a reason why these exist (and why they’ve been used) but I find their existence troubling and I wish we lived in a world where these types of machines did not have to exist.

The upgrading of these planes is covered well by wikipedia, an Air Force Magazine article, and the original YouTube video that sparked my interest in the topic. [1-3] Basically, the last B-52 rolled off the assembly line in 1962 and the Air Force has been refurbishing the original engines as time has gone on. In order to keep the planes flying into the 2040s the US government has decided to order new engines for the existing planes. Note an emerging connection, both the US government and US healthcare organizations are loathe to let old technology die. We gotta squeeze all the usable life out of those faxing systems…

New engines old plane, makes sense right? Sure, but take another glance at the B-52 (image above). Look at how many engines there are. Four pairs of small jet engines, for a total of 8 engines! Seems like we have an opportunity to cut down on the number of engines, right? Two turbofan jet engines is the standard for most modern commercial aircraft being delivered by Boeing or Airbus these days. Even if we didn’t go down to two we could go down to four easily. No need to change the number of mounting points! This is very logical, but it’s not truly feasible.  Why? Because of design decisions made 69 years ago. 

This underscores a concept that is not discussed widely enough in healthcare IT circles:

> Your choices for tomorrow are ultimately constrained by what you designed yesterday.

The jet engine technology of the 1950s ultimately informed how the rest of the B-52 was designed. The references go into more detail, but if you were to re-engine the B-52 with a smaller number of more powerful engines you would have to totally redesign other parts of the plane. For example the rudder, wings, and control systems would have to totally be redesigned. Doing that might mean that you’d have to rethink the fuselage as well. You would be better off designing a new airplane from the ground up. So the choice becomes maintain with significant constraints or totally redo.

When thinking about the health IT landscape we can see this concept everywhere. Why do we still put up with aging faxing servers and paging systems that are down more often than not? Because we built a system around them and the costs associated with their wholesale replacement are not tenable. Healthcare IT budgets are not infinite, so more often than not we have to focus on how to keep things going by repeatedly doing smaller upgrades. The best we can do is to try to strike a balance between current capabilities and future-proofing. 

Even though the B-52 engine retrofit project is significantly constrained, the fact that we are still able to use it at all and will be able to keep it flying till 2040 is a testament to the prowess of the original engineers. And all the engineers who have worked on it since. There is an aspect to this longevity that is inspiring. However, it is important to ask: would it have been better to do a clean sheet design and pay-off the accrued technical debt? [4] 

This is a question that can be asked of healthcare IT as easily as it can be asked of the US military. Heck, over half of all patient in the US have their electronic health records coded up in a programming language that was originally released in 1966. [5, 6] Both healthcare IT and the US military are ponderous creatures that generally ascribe to “if it ain’t totally broke don’t fix it”. There’s a lot more to discuss on this topic. It closely relates to the concept of total cost of ownership (might dive into in the future). But its important to recognize how the decisions we make today will impact the decisions we can make in the future.

Youtube video embedded below:

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/02_geGISTLg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<br />


Erkin  <br />
[Go ÖN Home](../../index.md)


## Bibliography
1.	Boeing B-52 Stratofortress - Wikipedia. 2022; Available from: https://en.wikipedia.org/wiki/Boeing_B-52_Stratofortress.
2.	The B-52 is Getting New Engines... Why Does it Still Need 8 of Them?
3.	Tirpak, J.A. Re-Engining the B-52. 2019; Available from: https://www.airforcemag.com/article/re-engining-the-b-52/.
4.	Technical debt - Wikipedia. 2022; Available from: https://en.wikipedia.org/wiki/Technical_debt.
5.	MUMPS - Wikipedia. 2022; Available from: https://en.wikipedia.org/wiki/MUMPS.
6.	JEFF GLAZE jglaze@madison.com, -.-. Epic Systems draws on literature greats for its next expansion. 2022.
