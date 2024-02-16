---
title: Can we detect Alien Clouds?
date: 2024-02-13
---

It’s a sunny afternoon and you are strolling through your tranquil neighbourhood. You look up at the sky and you see lumps of clouds floating by at a slow pace giving you company.
And then you start to wonder whether another living being on TRAPPIST-1e, an exoplanet which might have life, is also gazing up at its sky and enjoying the company of the clouds.
This trail of thoughts then leads you to the question that we will try to answer in this article, and towards the end, I will talk about an amazing research paper that sought to explore the intricacies involved with the question.

{{< figure src="scr00023.jpg" caption="Photo of a generated planet in Space Engine." numbered="true">}}

First let’s understand **what exactly clouds are?** This will help us understand the context better. Wikipedia gives this definition:

> A cloud is an aerosol consisting of a visible mass of miniature liquid droplets, frozen crystals, or other particles suspended in the atmosphere of a planetary body or similar space.[1] Water or various other chemicals may compose the droplets and crystals. On Earth, clouds are formed as a result of saturation of the air when it is cooled to its dew point, or when it gains sufficient moisture (usually in the form of water vapor) from an adjacent source to raise the dew point to the ambient temperature.

It is complicated but that is exactly what I am here for - to help you understand! Clouds are basically a collection of small liquid droplets, frozen crystals or other particles and because of their light weight, they are suspended in the atmosphere because of the air flowing beneath them, which uplifts them.

Clouds on the Earth primarily consist of water molecules, both in the liquid and solid state. Other molecules could be the primary constituent particles on other planets. For example, Mars has clouds made of ice and carbon dioxide, while Jupiter has high-altitude clouds made of ammonia and ammonium hydrosulfide. 

Now, how do clouds play a role in exoplanet science? Believe me when I say this - they have a major impact on our observations, especially when we produce transmission spectra of planets. I have already explained the concept of transmission spectra in this video about the first detection of a chemical species in a planet’s atmosphere.
{{< youtube vB_UIWmoAiA >}}
Please watch that video to gain a better understanding of how we obtain transmission spectra because it is a pretty interesting concept by itself!

Before going ahead, I would like to explain a very important concept to you, which will not only be useful for understanding exoplanet atmospheres, it will in fact help you understand these everyday-life questions:
1. Why is the sky blue?
2. Why are the sunset and sunrise red?
3. Why is the stop traffic signal red?

According to quantum mechanics, light is both a particle carrying energy (called the <mark>Photon</mark>) and a wave where 2 fields - the electric field and the magnetic field - are oscillating (or moving up and down with a definite period). This wave is called the <mark>Electromagnetic Wave</mark> and for now we will focus on that.

These points here are the peaks of the wave, and these points here are the troughs. The distance between 2 peaks (or 2 troughs) is called the wavelength of the wave. These are the general properties of every wave, so you can use them to describe any kind of periodic oscillations - from sound waves in the air to ripples in a pond of water.

Now, let’s consider a scenario where light with wavelength lambda is travelling towards a particle whose diameter is d. In 1871 and in a series of papers, Lord Rayleigh showed that if d is lesser than lambda, that is, the particle is smaller than the wavelength of the approaching light, then the probability that the light will interact with the particle and get scattered off towards another direction is given by this equation. I know there are a lot of variables involved, so let’s discard the unnecessary ones and simplify it to this form. This is a very interesting result. The left hand side is called the scattering cross section and describes the probability that the photon will interact with the particle and travel in another direction. In the right hand side, the wavelength of the photon is in the denominator and it is raised to the power of 4.

Okay we have a bunch of symbols and you might be asking “SO”? Here’s why this is amazing - if you increase the wavelength of the light on the right, the probability of the light interacting with the particle decreases rapidly! If you decrease it, the probability increases. This is in an inverse relationship. Just look at this plot here and observe how sigma varies as lambda varies.

And now I hope you will understand the beauty of this equation. The wavelength range of the entire electromagnetic spectrum is huge - from metres all the way to picometres. But the light that we see - that is, the region of the spectrum that our eyes can absorb and our brain can understand - is this much - from approximately 400 nm to 700 nm. And the famous VIBGYOR rainbow colour scheme is spread out like this with the blue placed here and red placed here. 

A quick question. Have you ever wondered why our eyes can understand only that particular region of the EM spectrum? Comment down your thoughts below and subscribe to the channel so you will be notified when I release a video discussing that!

Let’s bring back our equation. We can see that when light with shorter wavelength values, that means the blue end of the spectrum, is heading towards a particle, the probability that it will interact and change direction is very very high. Please note that it’s a probability - it’s not 100% sure that it will interact, but the chances are very high. On the other hand, the probability or the chances that the red end of the spectrum (that is light with longer wavelengths) will interact with the particle is very low.

Now we can answer the 3 questions I had posed a while back. The reason the sky is blue is because during that time, the sun is at its zenith position and is nearest to us. The dust particles present in the atmosphere are able to scatter the blue light more effectively than the red light. This is the blue light that eventually reaches our eyes. The reason sunsets and sunrises are red is because during that time, the sun is near the horizon and is the farthest from us. The dust particles scatter off the blue light, and by the time the light reaches our eyes, only the red part of the spectrum is remaining. The reason why the stop signals are red is because you need to be able to see the signal from a far distance so that you can stop in time.

This entire phenomenon where the probability of scattering of light by particles depends upon the wavelength is called Rayleigh scattering. Let’s get back to our discussion of clouds and why it is so important while studying exoplanets.

Let’s take a look at this plot here which I took from this book. These are not transmission spectra that we had discussed in the previous video. These are reflection spectra, which are variations in the intensity of the light that is reflected from the planet’s surface itself. These spectra are helpful in getting more information about the deeper parts of the atmosphere. I know there is a lot of stuff going on here and honestly you can unpack so much information about the planet from these spectra that it would require another video just to explain this. I will also be making a video about the different types of spectra that you can use for studying exoplanets.

If you want to get notified about such videos dropping, then like this video and hit that subscribe button!

The X axis of this plot is the wavelength region and the Y axis is the ratio of the planet flux to the star flux. So if there is more light from the planet, then the Y axis value will be higher. Simple as that.

Let’s isolate these 2 plots here and look at this region. We can see that the Y axis values, that is the planet flux values are higher here. That means we are able to record more light from the planet. Hmm. Let’s look down and observe the wavelength values corresponding to this region. It’s actually towards the shorter end of the wavelength region. Isn’t this amazing? This is due to Rayleigh scattering, which we were discussing a few minutes ago! Let’s construct a thought flowchart (or a thought-flow) to understand better.
There is more flux from the planet in the shorter wavelengths.
That means more light with short wavelengths is getting scattered.
This can be characterised as Rayleigh scattering
Rayleigh scattering occurs when there are dust particles or cloud clumps in the atmosphere.
I was blown away when I studied this concept because from a series of simple readings coupled with some amazing physics, we are able to detect clouds on another planet! This of course is a simulated spectrum, but look at this and this and this! We are actually detecting clouds on other planets which are millions of kilometres away!

One conclusion can be immediately drawn - a cloudy planet is brighter than an identical planet with a clear atmosphere. Clouds also decrease the depth to which the photons can penetrate the atmosphere before getting scattered and reaching us. And so even though detecting clouds is pretty cool, they do prevent us from studying the inner depths of a planet’s atmosphere.

Wow. We have discussed a lot about clouds. Thank you so much for still sticking with me till here. Please like this video if you have gained some new understanding about our world and subscribe to show your excitement for more videos!
Let’s move ahead and discuss a very interesting paper related to clouds.

In 2013, Laura Keridberg from University of Chicago, in collaboration with scientists from other institutions, published a paper confirming the presence of clouds in the atmosphere of GJ1214b, a super Earth that orbits GJ1214, a red dwarf star that is 48 light years away. The planet is a super-Earth, which means it’s larger than Earth but significantly smaller than the gas giants in our solar system. The planet is 2.7 times larger and 8 times heavier than Earth, and is the most likely known candidate for being an ocean planet.

The team observed the planet using the Wide Field Camera 3 instrument onboard the Hubble Space Telescope. They obtained light curves from 1.1 to 1.7 micrometre for 4 separate observations. This is the spectrophotometric data of the observations. The dots are the data points recorded by the team, and the lines are the theoretical models that best fit the data. The colours distinguish the wavelength bins in which they observed. 

They obtained the transmission spectrum of the planet from the light curves. Let’s understand this entire plot to appreciate their conclusion. Let’s consider the upper plot first. The black points are the data collected by the team. The grey points are data from previous work of other teams. The orange line represents an atmosphere whose composition is similar to our Sun - primarily Hydrogen and Helium and trace amounts of heavier elements such as oxygen, nitrogen, carbon and others. The blue line represents an atmosphere with a 100% water composition. Clearly, these models don’t fit the data well. 

Let’s zoom into the region observed by the team and check for other models. The green line represents an atmosphere with 100% methane composition, while the red line represents one with 100% carbon dioxide composition. None of these models match the data that they observed. This is the reason they concluded that the atmosphere of this super-earth is cloudy. Clouds can block light from the star that passes through the atmosphere and hide any spectral features that may arise from features below the clouds.

Oh and you might be asking why they considered atmosphere models of only certain chemical species. There are 2 main reasons for this. The first one is that these molecules are expected to be present based on the formation history and evolution of the planet, which has a direct influence on the physical parameters of the planet, which then determines the chemicals present in the atmosphere. I talked about this in this video here. The second reason is the wavelength region they observed at. As I had explained in this video, each chemical species exhibits spectroscopic features at particular wavelengths. Those wavelengths happened to fall in the region observed by the team.



And that is the end of today’s video! Thank you so much for sticking with me through to the end. I know it was a lengthy one, but I had to explain the underlying physics principle so that we can understand the paper better. I hope you learnt something new about clouds and enjoyed watching the video. And I truly hope you are able to appreciate the beauty and simplicity of the physics involved here.

Leave your thoughts and questions in the comments down below! Please like the video and share it with your friends and family, and please do subscribe to the channel because your support and enthusiasm for science keeps me going.

Thank you. Stay Curious!
