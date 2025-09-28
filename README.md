# Cloud-Chamber
My step by step process of making a cloud chamber

I was inspired by a Symmetry Magazine article to build a cloud chamber to detect subatomic particles - https://www.symmetrymagazine.org/article/january-2015/how-to-build-your-own-particle-detector?language_content_entity=und

I also found the following webpages useful:

 - https://www.instructables.com/How-to-Make-Cloud-Chamber/
 - https://github.com/lyon-fnal/cloud-chamber

## Planning and Designing:

First, I designed the box. I chose perspex as it is transparent, cheap and fairly strong. All sides were 296x150x4 mm to make construction simple. The lid was made of 2 sheets of perspex, each 2mm thick, with one fitting the outer dimensions of the box (300x300 mm) and the other fitting the inner dimensions (292x292 mm). This was to ensure the lid fit snug in the box, reducing vapour loss.

I ordered pre-cut perxpex from https://www.perspexsheet.uk
This made construction simpler and reduced the risk of issues building the box.

Other things I ordered:
 - 99% isopropyl alcohol
 - black felt (to soak the isopropyl alcohol)
 - silicone adhesive (suitable for perspex)
 - 300x300x0.8 mm metal sheet (for the base of the box)
 - black electrical tape (to cover the metal base)
 - cryogenic gloves
 - safety googles
 - thoriated tungsten welding rods (2% thorium)
 - dry ice (ordered after the box was constructed)

What I already had:
 - small clamps (for holding the perxpex and a right angle)
 - metal oven tray (to hold the dry ice)
 - scissors
 - a torch
 - sealant gun (to apply the silicone adhesive)

![IMG_7748](https://github.com/user-attachments/assets/89fd885c-14fd-49d2-b48e-f75cabb59078)

## Building the box:

I started by glueing 2 of the 296x150x4 mm perspex sheets at a right angle to one another - I then repeated this until all 4 walls were attached.
While they were drying, I covered the metal sheet with black electrical tape (this is to make the vapour trails more visible). I built the lid by glueing the 2 lid sheets together and adding around 3 layers of black felt to the smaller face.

Once the walls were fully dry I attached the base. I then left the silicone to set for around a week.

![IMG_7747](https://github.com/user-attachments/assets/f5ec8a08-2a57-4bbb-b222-769eb900ed1f)

![IMG_7752](https://github.com/user-attachments/assets/4e58a037-f178-4a5a-9eac-48db40f77604)

![IMG_7757](https://github.com/user-attachments/assets/d31066c5-994a-44df-a55c-5f99d882eadd)

![IMG_7763](https://github.com/user-attachments/assets/c4559e1c-8516-4fef-8c03-e7f5a8bbdb92)

![IMG_7766](https://github.com/user-attachments/assets/e6343253-d9fd-4048-ad8e-4c83cb88ccce)

![IMG_7770](https://github.com/user-attachments/assets/06cdfa77-4434-4453-838e-c75fd236a4af)

![IMG_7775](https://github.com/user-attachments/assets/66280129-8fa7-46e8-936b-071b78f0d863)

## Safety:

 - thorium is radioactive, but emits alpha particles which are unlikely to cause harm unless ingested or inhaled. I still gloves to handle them
 - dry ice is very cold and can cause burns, so I handled it with cryogenic gloves. Dry sublimates into CO2 which can cause suffication so should only be used in a well ventilated area
 - isopropyl alcohol is flammable and should also only be used in a well ventilated place
 - I did the experiment outside and stored the dry ice outside as well when I wasn't using it

## Conducting the experiment:

I ordered the dry ice to arrive the day of the experiment, as it doesn't last more then a few days. Once it arrived, I put some in the metal tray and sat the box on top of it. I saturated the felt with alcohol. drained off the excess, and then placed a couple of the welding rods inside the box. After putting the lid on, I left the box for around 20 mins (to give the alcohol time to evaporate and enter a super saturated state). I then shone the torch through the box to view the vapour trails left by the particles as they were emitted from the rod.

At first the vapour trails were barely visible, but after a few minutes they became a lot clearer.

![IMG_7831](https://github.com/user-attachments/assets/66350274-0db5-4831-872b-b3791a968d3b)

![IMG_7836](https://github.com/user-attachments/assets/11471f71-2c5d-4546-841f-4382e52a88ca)

![IMG_7859](https://github.com/user-attachments/assets/5cdae34d-e342-4890-9300-706f7048adaf)

![IMG_7887](https://github.com/user-attachments/assets/737212f3-bd50-47d7-90de-4d0124af647d)

![IMG_7900](https://github.com/user-attachments/assets/fc07ff1f-791e-4001-b068-434ea2b125b1)

https://github.com/user-attachments/assets/696e3565-fcf1-45d9-8326-927bcc577ab5

Some of the trails I saw:
 -  short straight trails (likely alpha decay from the thorium), which made up the majority of trails seen
 -  curled trails (possibly beta decay from radium that the thorium decayed into)
 -  forked trails (unkown cause but indicates other decays happening)
 -  long straight trails (these were not close to the thorium, indicating paritcles form space like muons)

## Using the data:

I wanted to use my observations to estimate the half life of thorium.

I counted 41 short straight tracks coming from the rod in a 29 second period. Given the rod was resting on the base of the box, and I wouldn't be able see any going downwards, I doubled that to 82, giving a rate of approximately 2.8 emissions per second.

The rod weighed, 6.38 grams so should have contained 0.1276g thorium, giving an emission rate of approximately 22 emissions per second per gram of material.

0.1276g thorium is 3.3121 * 10^20 thorium particles, and from this I calculated an estimated half life of 2.5367 * 10^12 years. The published half life for thorium is 1.4 x 10^10 years. 

There were a lot of unknowns which could have caused my calculation to be incorrect. The thorium content of the rod could have been a lot less than the 2% it was said to have contained. It's also possible that alpha particles were blocked before leaving the rod by a protective coating on the rod, a layer of oxidisation or other materials in the rod. Some alpha particles may have failed to leave a vapour trail after they were emitted. 

## Future experiments:

If I repeat the experments I would make:

 - I would use a strong magnet to allow me to see the charge of the particles
 - more even lighting such as a string of LED lights or a larger torch
 - I would try to calculate the speed of the particles emitted
 - clamp the lid to prevent vapour loss
