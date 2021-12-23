# Sound Synthesis

## Tasks / Requirements
```
1.  An Ableton project
      1.  Without using any sampler (Sampler, Simpler, Impulse, Drum Rack, etc.)
      2.  Using real time, non-realtime input
      3.  Using edited note, velocity
      4.  Using MIDI controller
      5.  Using Recorded, edited automation
      6.  Using at least 2 built-in software synthetiser
      7.  Using at least 2 Insert effect
      8.  Using at least 2 Send/Return effect
2. At least 700 word analysis
3. Presentation
4. WAV file (90 sec)
```

## Synthesis Analysis - rule 30
*Luca Nagy*

*You can read it in Hungarian [here](https://github.com/lucanag/music/blob/main/rule30.pdf).*

### Inspiration

I chose my inspiration source based on the topics which I felt as the greatest gravity to my personality. These are the improvements in different sciences and my infinite curiousity regarding the future affected by our current knowledge in scienses. [Stephen Wolfram, A New Kind of Science](https://www.wolframscience.com/nks/) named book is which I recenty read and have been amazed ever since, especially the rule 30 named cellular automation model in it. The questions regarding future I encounter when I understand this model is which I wanted to use when I syntetised sounds to use a concept as  an abstract future picture on the improvements. This picture is not a relaxed idil picture, rather fulfilled with excitements, challenges, but in the same time with dark tone, atmospheric sounds which are not experienced in our natural direct environment. I followed this concept when I syntentiyed 4 sounds, based on its style I would say dub-techno especially that I was inpired by [Heavenchord - 01 H.C.R.D.1 (dub44)](https://www.youtube.com/watch?v=i9sBLThQ4Cc) in structure  and secquence. The following picture shows [rule 30](https://en.wikipedia.org/wiki/Rule_30)
 which is the base source thought of the New Kind Of Science book. 
 

<img src="https://user-images.githubusercontent.com/43001496/147131176-0c1b8273-9e87-42b5-93ce-417e1c7067f0.png" width="500"/> 

> *"It always bothers me that according to the laws as we understand them today, it takes a computing machine an infinite number of logical operations to figure out what goes on in no matter how tiny a region of space, and no matter how tiny a region of time. How can all that be going on in that tiny space? Why should it take an infinite amount of logic to figure out what one tiny piece of space/time is going to do? So I have often made the hypothesis ultimately physics will not require a mathematical statement, that in the end the machinery will be revealed and the laws will turn out to be simple, like the chequer board with all its apparent complexities. But this is just speculation." - Richard Feynman*

### Implementation Process

I divided my sounds into 3 groups, such as KERNEL, DRUMS, and ORNAMENT. The KERNEL and ORNAMENT mirrors my predefined concepts in Inspiration paragraph. Regarding the DRUMS I only tried to not modify the ambient, mystic mood by synentizing strong drums. From the 7 sounds I used 5 times Operator, once Analog and once Wavetable. I havenát used presamples, but reused some sounds which I syntetised in more channels with tiny differences. I used 2 times Send/Return Delay as I would have been using with the same parameters on top of those sounds.

<img src="https://user-images.githubusercontent.com/43001496/147131851-562c7008-3d33-4678-9384-a32f63fe7c99.png" width="100" /> 

Firstly I started with the KERNEL - SICK sound which I tried to make as mystic as I can. Due to this I thought a substractive syntesis will be the proper from a rich sound, then I would slightly modify the Decay of the filter envelope on the Operator to receive an additional more dominant sound. With this and small editation CHORD was burn during I tried NATIVE INSTRUMENTS KOMPLETE KONTROL M32 during. I tried to create similar melodies on the two channel.

Then I continued with the DRUMS synthesis where I used additive sznthesis or used only one oscillator with more audio effects.

<img src="https://user-images.githubusercontent.com/43001496/147131866-1ab3d37a-4129-40d4-80a1-c80eac216eba.png" width="300" /> 

Then I still felt some lack between the overall mood and the inspiration part, so I started experiencing with the ORNAMENT group where I synthesised a PAD with the help of Wavetable and used some HIGH STUFF with Analog.

--------

#### 1, KERNEL

<img src="https://user-images.githubusercontent.com/43001496/147132252-847a4e2b-0f6f-4f3b-a652-d1f621b05a2c.png" width="500" />

##### a, SICK

Since I wanted a more abstract but not a soft and supressed sound, I used a SwD wave with the built-in Operator with long attack and release time and playing with the filter as a substractive synthesis. Since I don't have a solid musical background using Chord was a huge help asince a simple moll can be set easily only once and I can forget it in the followings when I set the notes.

<img src="https://user-images.githubusercontent.com/43001496/147132272-5be4c331-694a-49e1-97ed-0972bd563185.png" width="500" />

I used low pass filter MS2 based on (link) and set the filter envelope to open and close fast with short decay. I wanted pitch sensitivity so I increased Freq Key.

<img src="https://user-images.githubusercontent.com/43001496/147132298-9d478ad6-e691-4857-8c0b-db6e86e49b9e.png" width="500" />

During I played with a controller, I realised I need more high frequency, so I used a band pass filter on Auto Filter with small rezonanse. In order to make more exciting and make some movements I used and LFO with small amplitude. Since I felt the sound a ittle bit dry, in order to fill with more colour, I used a ping-pong Delay on the middle frequencies with high feedback. Then I realised I would use on other channels too, so I used as a Send/Return effect instead of Insert. I used automation in order to decrease the realese time which was effected by the high feedback. 

<img src="https://user-images.githubusercontent.com/43001496/147132315-54b4d1b8-2f5a-499b-99c1-ad366d4cfe45.png" width="500" />

<img src="https://user-images.githubusercontent.com/43001496/147132328-fe07a8be-b638-426a-85f8-906c52d9be8f.png" width="250" />

I set notes by use of controller then I chose quantitized option besides some manually edited notes. I also played here with velocity values.

At this point I was sutisfied wiht this sound, as the higher frequencies of this sound reminded me the voices of the Heptapods from the Arrival named movie, which movie's mood is not so far from my vision defined in the inspiration part. For the reason that I used this sound heavily.

##### b, CHORD

Since I wanted a much strong, but inherited from the previous sounds for fit in the mood, I just copied the Chord and Operator from SICK and only modified the decay of filter envelope to increase it for fulfill with harmonics.

<img src="https://user-images.githubusercontent.com/43001496/147132341-983fce76-6b09-4815-95ee-dbb7feba2a53.png" width="500" />

The new sound got to be more stronger with this so I used as the lead. I used Auto Filter LFO and automated it's amplitude for movements. I recorded this automation. I only used a logic to decrease the value when HIHAT appears for get back to the base CHORD sounds.

<img src="https://user-images.githubusercontent.com/43001496/147132350-38574fea-e5ee-4826-bac4-7782b3861377.png" width="500" />

Similarly to the SICK I used Reverb and Delay, but with highlighting higher freqyencies and using as Insert effect.

<img src="https://user-images.githubusercontent.com/43001496/147132395-2ad11fa4-09de-44ed-9872-57aef342f096.png" width="500" />

Similarly to the SICK I used Reverb and Delay, but with highlighting higher freqyencies and using as Insert effect.

--------

#### 2. DRUMS

<img src="https://user-images.githubusercontent.com/43001496/147133285-05df0069-cf4b-49ee-ab76-e781c995e72a.png" width="500" />

##### a, KICK

I wanted a sound fulfilled with harmonics so I again strted from a Sw3 wave with zero attack and sustain with a middle long release. 

<img src="https://user-images.githubusercontent.com/43001496/147133298-e490334d-085d-409b-aebc-282ceb9899f6.png" width="500" />

I played a lot with the Pitch evelope decay value which has key role in finding out the proper KICK which is not to strong to fit to my taste.

<img src="https://user-images.githubusercontent.com/43001496/147133320-c8794a48-7673-4536-956e-670790108436.png" width="500" />

I used a Low pass filter with tiny resonance with zero attack and fast closing.

<img src="https://user-images.githubusercontent.com/43001496/147133363-c42e5044-4106-41da-ac95-2dfcafb97f3c.png" width="500" />

By playing the drive parameter of the Saturator i made the sound more determined, then made the high frequencies more soft with an EQ Eight. In order to open the KICK gradually during the lead (CHORD), I automated the low pass filter on the Operator. 

##### b, BASS

I used fixed 52 Hz and sinus wave, as I wanted a more soft element than the KICK. Due to it I was more cautious with the Pich envelope as well as the low pass filter cut point (??). Drum Bass drive was used for increasing the leftover frequencies.

<img src="https://user-images.githubusercontent.com/43001496/147133387-102664b7-4ae1-4d4a-9b37-88f14c7df026.png" width="500" />

##### c, HIHAT

I spend a lot time with the HIHAT as first I check a [tutorial](link yt) where they only used a white noise with the built-in Operator. This was not so interesting as the metal elements were missing from it, so I used a custom wave fromate with additive ssynthesis whit small and middle amplitue harmonics. I cut the low frequencies but it was still not the best, so I realised that increasing the resonance is a good solution.

<img src="https://user-images.githubusercontent.com/43001496/147133399-f10ecfa4-d19a-45e6-b280-c2c003679d80.png" width="500" />

<img src="https://user-images.githubusercontent.com/43001496/147133404-9e16e1f7-ce95-4a98-a504-31ef21363f59.png" width="500" />

On top of these I used Redux and Chorus for make it more dirty and metallic?. Then I realised the problem was with my note lenght, so I shorten them. In the ending part I didn't know on how to finish it softly so I just started decreasing the number of notes and using more automation on Redux dry/wet and Echo. 

<img src="https://user-images.githubusercontent.com/43001496/147133423-2ac4e285-0a43-4952-996c-ad0ec73a10e1.png" width="500" />

<img src="https://user-images.githubusercontent.com/43001496/147133433-3be6ea30-e916-4d73-814f-25d5abff3a2b.png" width="500" />

--------

#### 3. ORNAMENTS

The picture regarding the style and mood was clarified after the KERNEL and DRUMS implementation, I wanted a pad noise which has more dark tone with some noises in the ending part. In the same time I felt week in high frequencies so my aim in this part was also synthetising some ornament high noises. 

<img src="https://user-images.githubusercontent.com/43001496/147133448-802e8fb2-4929-4ef9-af79-55f295086594.png" width="500" />

##### a, PAD

The aim was here to synthetise a background sound which is little bit worrysome affect has. I used a Wavetable Pink Noise with 26Hz Square wave LFO. I wanted only the release part of it so I set high release of the amplude envelope then used Saturator and Echo with high feedback on high frequences.

<img src="https://user-images.githubusercontent.com/43001496/147133458-efbb58bd-5a9d-477f-9807-871c15a9b78c.png" width="500" />

In order to soothe the impact of this sound, I increased the envelope's attack and simply cut the track volumes on the note on part (I knew this is not the most elegant solution but it worked). Then I usedd Auto Filer on the high frequencies to cut them. Even it was only a pad noise I wanted to make it more colourful so I used LFO as a modulator on the Auto Filter. I realised that the Echo's Noise generator is also fit to this sound, so I set some automation to it. 

<img src="https://user-images.githubusercontent.com/43001496/147133489-de9a2381-1973-4543-a773-358116538fa0.png" width="250" />

<img src="https://user-images.githubusercontent.com/43001496/147133502-21594284-93c0-4a3e-9308-daaaca2df962.png" width="200" />


##### b, HIGH STUFF

The aim was to fulfill the boring parts with some higher frequencies. I used Analog with two oscillator with sawtooth waves to obtain more harmonics.

<img src="https://user-images.githubusercontent.com/43001496/147133517-e5f7e73c-516d-4cb4-bee2-943c521e7315.png" width="500" />

I set the note to G3 to fit to the CHORD and SICK main frequencies. I tried to soften this sound with by increasing the filter and amplitude's envelope attack of the first oscillator to open the low pass filter gradually. Then to make more movements and make the overall impact more colourful I set the second oscillator 2 octave up. Echo and Decay was used with high feedvack. For movements I used LFO on the Auto Filter and Delay as a Send/Return effect.

<img src="https://user-images.githubusercontent.com/43001496/147133535-c6755988-0013-4dbe-819e-c0709fc189ac.png" width="500" />

--------

## Presentation

## Wav file
