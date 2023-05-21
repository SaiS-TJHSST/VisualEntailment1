# VisualEntailment1

Visual entailment algorithm to see whether two images and their associated captions contradict, imply, or unrelate to each other. Custom multimodal model used which comprised of a ResNet 
visual encoder and a BERT textual encoder.

![image](https://github.com/SaiS-TJHSST/VisualEntailment1/assets/94657753/a16931b2-817c-4eba-9e97-16434517c2b2)
![image](https://github.com/SaiS-TJHSST/VisualEntailment1/assets/94657753/3f359aa6-8cc9-43f5-a9f7-e3fcbf1ea9ed)

Text one: @CapcomFighters 

I really think that Capcom should verify the votes. Zenith from Brazil is winning the fan voting. Brazil is known for spamming on all social media. I truly believe that there are several fake accounts voting for him to win over Tokido. 

#SFVCE #CPT2020 https://t.co/xwbFf12jTS
Text two: It's impossible to believe that Tokido or even Punk would lose to Zenith in a popularity contents for #CPT2020 as you can see in the current nominations #SFVCE 

Brazil is the Country with most spamming in the whole World. Please @CapcomFighters verify the votes and do a recount. https://t.co/N2FU4ZHaMq
Label: NoEntailment

![image](https://github.com/SaiS-TJHSST/VisualEntailment1/assets/94657753/6604c006-7443-40a6-9802-5d32e2d20d4c)
![image](https://github.com/SaiS-TJHSST/VisualEntailment1/assets/94657753/41925dc9-33b4-478e-9240-baa888d9d8cd)

Text one: Hey buddy! #wildkamera #wildlife #nature #hunting #trailcam https://t.co/zaMACd3Kx7
Text two: Hey buddy! #wildkamera #wildlife #nature #hunting #trailcam https://t.co/VVHFlN1hk3
Label: Implies

![image](https://github.com/SaiS-TJHSST/VisualEntailment1/assets/94657753/3612b11a-be48-4822-a3bc-2bdc51a64af9)
![image](https://github.com/SaiS-TJHSST/VisualEntailment1/assets/94657753/c85b8e56-d499-4e1f-af8f-0bee507b3783)

Text one: Friends, interested all go to have a look!
@ToddStallsworth @kris1010 @TeamColumbusHky @llfrankart @AXIAnet @ConroyRoth @sr_Saggebz @DBuchananBiz1st @GreatestQuotes @muogroyk https://t.co/xqWQGKXtCR
Text two: Friends, interested all go to have a look!
@dcisgur57 @schoenwriter @pattymcqueen @SpaceConscious @PaschalChuks12 @StephenBus @mdeluciabooks @NewHavenMuseum @CCSUJournalism @TheLaurelCT https://t.co/VIQNBvrwOQ
Label: Contradictory

