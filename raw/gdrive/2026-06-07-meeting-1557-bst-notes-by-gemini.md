---
source: farmer/gdrive
farmed: 2026-06-08T00:00:00Z
drive_id: 1hUP0BQ5jYt9u-ZWloowpmD3NV_ENDVK_IVrgWDD2Fno
title: Meeting started 2026/06/07 15:57 BST – Notes by Gemini
mime_type: application/vnd.google-apps.document
folder: SUO Meeting Recordings
modified: 2026-06-07T16:16:46.525Z
owner: anis@human-edge.io
---

#  Notes  

 Jun 7, 2026

## Meeting Jun 7, 2026 at 15:57 BST

Meeting records [Transcript](https://docs.google.com/document/d/1hUP0BQ5jYt9u-ZWloowpmD3NV_ENDVK_IVrgWDD2Fno/edit?usp=drive_web&tab=t.8nb1zauj94bw) 

  
  

### Summary

The team reviewed extensive robot iteration documentation and finalized key design improvements for competition runs.  
  
**Robot Iteration Documentation Review**  
The team organized documentation for robot runs 1 through 8. They clarified task ownership and refined methodologies for displaying mechanical iterations.  
  
**Design and Code Improvements**  
Participants implemented critical post-nationals updates, including stall prevention, gear ratio modifications, and speed optimization. The team also addressed artifact handling issues through mechanical refinements and strategic code adjustments.  
  
**Presentation Strategy and Physics**  
The team solidified plans to present iteration history via detailed files and anchor slides. They confirmed scientific reasoning behind mechanical force and speed adjustments for judges.

  


  
  

### Decisions

## **ALIGNED**

  - **Documentation format for extra designs** The team established that extra, unused robot designs should be documented using footnotes or footer text boxes within the presentation table.
  - **Presentation format for judges defined** The project work will be presented to judges using both detailed documentation files and a single summary slide within the poster to demonstrate iterations.

  

We've **updated the Decisions section** using your feedback.


  
  

### Next steps

  - \[Elliot\] Document Run History: Add notes explaining that missions were performed separately during pre-regionals.
  - \[Elliot\] Document Sand Adjustments: Include details regarding the removal of the frame to resolve sand mission failures.
  - \[The group\] Review Documentation: Verify the accuracy of the completed robot iteration documentation.
  - \[The group\] Send Media Assets: Provide missing images or videos of robot iterations to Elliot for the project slides.
  - \[Elliot\] Highlight Design Innovations: Mention the circular lift design as an original and successful solution in the project report.
  - \[Elliot\] Format Design Notes: Create a text box at the documentation footer for explaining extra design iterations. Reference these notes back to the main text using footnotes.
  - \[Guhan Karthicraja\] Implement Stall Prevention: Complete the stall prevention logic for the mission as discussed.
  - \[Elliot Newman\] Verify Stall Prevention: Oversee that the stall prevention code is properly added and finalized.
  - \[Guhan Karthicraja\] Share Photo: Photograph the fixed pin and share the image with Elliot.
  - \[Guhan Karthicraja\] Notify Team Member: Send the fixed pin photograph to the specified team member.
  - \[KG\] Post Physics Explanation: Analyze the flag drop physics and share the findings with the group on WhatsApp.
  - \[The group\] Review Documentation: Study the meeting records and shared details to align on project iterations.

  
  

### Details

  - **Robot Iteration Documentation Setup**: Elliot Newman took the lead on organizing the robot iteration documentation with assistance from Guhan Karthicraja. There was initial confusion regarding task assignments, but it was clarified that Elliot Newman is the lead, and they would be using screen sharing to review the documentation together ([00:00:20](https://docs.google.com/document/d/1hUP0BQ5jYt9u-ZWloowpmD3NV_ENDVK_IVrgWDD2Fno/edit?ouid=104118343287414385523#heading=h.r4j7prq0nlje)).
  - **Run 1 Iterations and Design Adjustments**: The team reviewed iterations for Run 1, covering pre-regionals, post-regionals, and post-nationals. Key design changes included making the arm lighter for better control during pre-regionals ([00:05:44](https://docs.google.com/document/d/1hUP0BQ5jYt9u-ZWloowpmD3NV_ENDVK_IVrgWDD2Fno/edit?ouid=104118343287414385523#heading=h.198xsdhd1sg4)). For post-regionals, the team implemented "stall prevention" and added side wheels to the robot ([00:07:31](https://docs.google.com/document/d/1hUP0BQ5jYt9u-ZWloowpmD3NV_ENDVK_IVrgWDD2Fno/edit?ouid=104118343287414385523#heading=h.vklv3cj6wlvo)). Post-nationals improvements involved lowering the wheel position to improve performance ([00:09:01](https://docs.google.com/document/d/1hUP0BQ5jYt9u-ZWloowpmD3NV_ENDVK_IVrgWDD2Fno/edit?ouid=104118343287414385523#heading=h.fozlhimtd1wp)). They also removed a frame that was previously obstructing the robot's movement to ensure free access to mission areas ([00:13:04](https://docs.google.com/document/d/1hUP0BQ5jYt9u-ZWloowpmD3NV_ENDVK_IVrgWDD2Fno/edit?ouid=104118343287414385523#heading=h.t23lq3jymu10)).
  - **Run 2 Documentation - Map Reveal and Brush Mission**: Elliot Newman and Guhan Karthicraja discussed the evolution of Run 2 (Map Reveal/Brush mission). Guhan Karthicraja explained that the first iteration involved a detachable piece to complete mission two passively ([00:16:02](https://docs.google.com/document/d/1hUP0BQ5jYt9u-ZWloowpmD3NV_ENDVK_IVrgWDD2Fno/edit?ouid=104118343287414385523#heading=h.8n0bmmd7301)). The brush collection mechanism evolved from using prongs to a "bed of axles" slam-down method, and eventually to a rack and pinion system for better efficiency ([00:17:32](https://docs.google.com/document/d/1hUP0BQ5jYt9u-ZWloowpmD3NV_ENDVK_IVrgWDD2Fno/edit?ouid=104118343287414385523#heading=h.ko0dabw8b65n)).
  - **Run 2 Post-Nationals and Code Enhancements**: Regarding post-nationals updates for Run 2, the team focused on stabilizing the rubber band trap by increasing the number of holding arms from one to two ([00:20:57](https://docs.google.com/document/d/1hUP0BQ5jYt9u-ZWloowpmD3NV_ENDVK_IVrgWDD2Fno/edit?ouid=104118343287414385523#heading=h.b2jy2pi8lijd)). They also updated the code to include a deceleration phase before the robot approaches the brush, which reduces oscillation and allows for a more precise, smaller-radius approach to the mission ([00:22:45](https://docs.google.com/document/d/1hUP0BQ5jYt9u-ZWloowpmD3NV_ENDVK_IVrgWDD2Fno/edit?ouid=104118343287414385523#heading=h.358y87oipf3)).
  - **Run 3 Documentation - Missions 3 and 4**: The team reviewed the documentation for Run 3, which involves missions 3 and 4. The design includes a claw and a lifting arm for the "precious artifact" ([00:24:17](https://docs.google.com/document/d/1hUP0BQ5jYt9u-ZWloowpmD3NV_ENDVK_IVrgWDD2Fno/edit?ouid=104118343287414385523#heading=h.s4vj6vzhp22a)). Guhan Karthicraja emphasized the need to detail the passive rack and pinion attachment used to trigger the claw’s grip ([00:25:22](https://docs.google.com/document/d/1hUP0BQ5jYt9u-ZWloowpmD3NV_ENDVK_IVrgWDD2Fno/edit?ouid=104118343287414385523#heading=h.ilai87y35r14)). The pre-regional code for this run involved a turn and forward movement to complete the mission requirements ([00:24:17](https://docs.google.com/document/d/1hUP0BQ5jYt9u-ZWloowpmD3NV_ENDVK_IVrgWDD2Fno/edit?ouid=104118343287414385523#heading=h.s4vj6vzhp22a)).
  - **Run 3 Post-Nationals - Artifact Extraction Solutions**: During post-nationals, the team addressed the challenge of spilling the artifact during extraction. They settled on a design using a circular lift, which provides constriction to hold the artifact securely ([00:26:34](https://docs.google.com/document/d/1hUP0BQ5jYt9u-ZWloowpmD3NV_ENDVK_IVrgWDD2Fno/edit?ouid=104118343287414385523#heading=h.m02xhympt2f1)). Florence Ingram offered an alternative design using a simple lifting arm with two side prongs; while it provides effective lift, the team noted it requires extreme precision due to a lack of "wiggle room" for closing the arm ([00:29:34](https://docs.google.com/document/d/1hUP0BQ5jYt9u-ZWloowpmD3NV_ENDVK_IVrgWDD2Fno/edit?ouid=104118343287414385523#heading=h.7ea8gi3jp2fc)).
  - **Run 4 Overview and Documentation Logistics**: Elliot Newman reviewed the documentation for Run 4, which includes a flag dropper and a lifting arm. Guhan Karthicraja provided guidance on how to handle extra designs not used in the final competition, suggesting that these should be included as footnotes or specific text boxes at the bottom of the slides rather than squeezed into the main table ([00:33:23](https://docs.google.com/document/d/1hUP0BQ5jYt9u-ZWloowpmD3NV_ENDVK_IVrgWDD2Fno/edit?ouid=104118343287414385523#heading=h.kko6ohafjnhn)).
  - **Run 4 and Run 8 Interference Management**: The team identified a conflict where the code for Run 8 was inadvertently undoing the work of Run 4 by pushing out collected artifacts. They resolved this by updating the code in Run 8 to avoid the artifacts and approach the statue from a different angle ([00:35:55](https://docs.google.com/document/d/1hUP0BQ5jYt9u-ZWloowpmD3NV_ENDVK_IVrgWDD2Fno/edit?ouid=104118343287414385523#heading=h.jxdl4r6yiwdj)). Additionally, they utilized a "free flowing" holder design for the flag, which the team jokingly named the "dancing prongs" ([00:37:29](https://docs.google.com/document/d/1hUP0BQ5jYt9u-ZWloowpmD3NV_ENDVK_IVrgWDD2Fno/edit?ouid=104118343287414385523#heading=h.61eaund1g64x)).
  - **Run 4 Post-Nationals Adjustments**: To resolve issues where artifacts became trapped due to friction during nationals, the team smoothed the inside of the mechanism ([00:41:39](https://docs.google.com/document/d/1hUP0BQ5jYt9u-ZWloowpmD3NV_ENDVK_IVrgWDD2Fno/edit?ouid=104118343287414385523#heading=h.lj0bzibp4t7z)). They also modified the robot's movement pattern, adding a reversal maneuver before approaching the home area to prevent the prongs from getting stuck in mission components ([00:42:42](https://docs.google.com/document/d/1hUP0BQ5jYt9u-ZWloowpmD3NV_ENDVK_IVrgWDD2Fno/edit?ouid=104118343287414385523#heading=h.ghw7aa9o1ecc)).
  - **Run 5 Iterations - Boulder Collection**: The team reviewed components for Run 5, specifically the boulder collector and arm ([00:44:01](https://docs.google.com/document/d/1hUP0BQ5jYt9u-ZWloowpmD3NV_ENDVK_IVrgWDD2Fno/edit?ouid=104118343287414385523#heading=h.23ptkh5hwcxj)). They discussed design changes made since regionals, including shifting from a single pin on the lift arm to a two-pin design to increase consistency ([00:44:59](https://docs.google.com/document/d/1hUP0BQ5jYt9u-ZWloowpmD3NV_ENDVK_IVrgWDD2Fno/edit?ouid=104118343287414385523#heading=h.zbqc9id2wvvg)). The gear ratio was also modified to address previous performance issues ([00:45:49](https://docs.google.com/document/d/1hUP0BQ5jYt9u-ZWloowpmD3NV_ENDVK_IVrgWDD2Fno/edit?ouid=104118343287414385523#heading=h.emdts127djtn)).
  - **Run 5 Post-Nationals - Operational Improvements**: For post-nationals in Run 5, the team implemented a one-way lock and refined the positioning levers to ensure more consistent engagement ([00:46:49](https://docs.google.com/document/d/1hUP0BQ5jYt9u-ZWloowpmD3NV_ENDVK_IVrgWDD2Fno/edit?ouid=104118343287414385523#heading=h.fqs8cu4laizn)). Toby contributed a "hanger" design to assist with placing missions on the table, which the team decided to formally include in their documentation ([00:49:25](https://docs.google.com/document/d/1hUP0BQ5jYt9u-ZWloowpmD3NV_ENDVK_IVrgWDD2Fno/edit?ouid=104118343287414385523#heading=h.z23zzh5coa1i)).
  - **Run 6 Iterations - Scale Pan and Bucket**: Elliot Newman detailed the components for Run 6, which covers missions 10 and 11, including a one-way system used to collect the scale pan ([00:50:06](https://docs.google.com/document/d/1hUP0BQ5jYt9u-ZWloowpmD3NV_ENDVK_IVrgWDD2Fno/edit?ouid=104118343287414385523#heading=h.8ls5yow2gxc3)). For post-regionals, the team switched to using a blue long panel for alignment and refined the mechanism for hitting the bucket ([00:51:32](https://docs.google.com/document/d/1hUP0BQ5jYt9u-ZWloowpmD3NV_ENDVK_IVrgWDD2Fno/edit?ouid=104118343287414385523#heading=h.xnp88jibbw7u)).
  - **Run 6 Post-Nationals and Stall Prevention**: In post-nationals for Run 6, the team added an aligner for market wares and optimized the one-way system. KG instructed Guhan Karthicraja to implement stall prevention for this run, as it had stalled several times during previous tests, which the team agreed to prioritize ([00:53:09](https://docs.google.com/document/d/1hUP0BQ5jYt9u-ZWloowpmD3NV_ENDVK_IVrgWDD2Fno/edit?ouid=104118343287414385523#heading=h.fnndrouw8o8u)).
  - **Run 7 Iterations - Hammer and Speed**: Run 7, focusing on mission 8, utilizes a hammer and rotational arm ([00:54:22](https://docs.google.com/document/d/1hUP0BQ5jYt9u-ZWloowpmD3NV_ENDVK_IVrgWDD2Fno/edit?ouid=104118343287414385523#heading=h.q6nvtk2bkza)). The team discussed the shift from using high-torque black wheels in the regional competition to using smaller, faster wheels for nationals to prioritize speed over raw torque ([00:55:39](https://docs.google.com/document/d/1hUP0BQ5jYt9u-ZWloowpmD3NV_ENDVK_IVrgWDD2Fno/edit?ouid=104118343287414385523#heading=h.3dq9wnutbr9b)). They also added counterweights to balance the mechanism and fixed a pin-related issue ([00:56:58](https://docs.google.com/document/d/1hUP0BQ5jYt9u-ZWloowpmD3NV_ENDVK_IVrgWDD2Fno/edit?ouid=104118343287414385523#heading=h.22ltszji76qu)).
  - **Run 8 Documentation Overview**: The meeting concluded with a brief overview of Run 8, which involves half of mission 3 (minecart transport) and a third of mission 15 (sites) ([00:58:00](https://docs.google.com/document/d/1hUP0BQ5jYt9u-ZWloowpmD3NV_ENDVK_IVrgWDD2Fno/edit?ouid=104118343287414385523#heading=h.ah0hbf1m7lt1)).
  - **Flag and Artifact Dropper Improvements (Post-Regionals)**: Elliot Newman and Guhan Karthicraja discussed updates made to the active and passive components, specifically the flag and artifact droppers, following issues identified during regionals. Guhan Karthicraja explained that a piece was added to the flag to stabilize it and prevent breakage upon impact ([00:59:05](https://docs.google.com/document/d/1hUP0BQ5jYt9u-ZWloowpmD3NV_ENDVK_IVrgWDD2Fno/edit?ouid=104118343287414385523#heading=h.ert59ce079ah)). KG facilitated a conversation regarding the physics of "elastic bounce," clarifying that the design modification aimed to improve energy transfer through increased surface area rather than relying on specific Newtonian laws ([01:00:17](https://docs.google.com/document/d/1hUP0BQ5jYt9u-ZWloowpmD3NV_ENDVK_IVrgWDD2Fno/edit?ouid=104118343287414385523#heading=h.22bssliev09q)).
  - **Post-Regionals Adjustments to Fork and Mission 14**: Elliot Newman detailed post-regionals changes, including adjustments to the gear ratio in the fork to improve accuracy and code modifications for both the fork and the reverse-out movement for mission 14. KG cautioned the team to avoid violating equipment constraints related to mission 3 and instructed them to develop a strategy for potential collisions if an external component from another team enters the map during run 8 ([01:01:39](https://docs.google.com/document/d/1hUP0BQ5jYt9u-ZWloowpmD3NV_ENDVK_IVrgWDD2Fno/edit?ouid=104118343287414385523#heading=h.qqkhw96o9s8j)).
  - **Physics Concepts and Mechanical Force**: KG addressed the application of physics within the team's designs, specifically how gravity and mass influence the function of the flag dropper and the generation of force by the wheel. KG encouraged the team to ensure their scientific reasoning regarding these mechanical changes is sound ([01:03:09](https://docs.google.com/document/d/1hUP0BQ5jYt9u-ZWloowpmD3NV_ENDVK_IVrgWDD2Fno/edit?ouid=104118343287414385523#heading=h.ykgrnradhk1k)).
  - **Post-Nationals Design and Code Modifications**: Elliot Newman summarized the post-nationals design improvements, which included a new wheel cover, an improved flag dropper, updated pins in the collector, a stopper for the fork, and minor code changes ([01:03:09](https://docs.google.com/document/d/1hUP0BQ5jYt9u-ZWloowpmD3NV_ENDVK_IVrgWDD2Fno/edit?ouid=104118343287414385523#heading=h.ykgrnradhk1k)). The team collectively discussed the decision to drastically increase the speed of run 8 to save time and optimize the flag's trajectory ([01:04:51](https://docs.google.com/document/d/1hUP0BQ5jYt9u-ZWloowpmD3NV_ENDVK_IVrgWDD2Fno/edit?ouid=104118343287414385523#heading=h.9c1pem2mvgls)).
  - **Speed Optimization and Parabolic Path Reasoning**: Guhan Karthicraja and Elliot Newman explained that increasing the speed of the flag drop allowed the item to travel further and land accurately within the square, as lower speeds caused the flag to drop short ([01:04:51](https://docs.google.com/document/d/1hUP0BQ5jYt9u-ZWloowpmD3NV_ENDVK_IVrgWDD2Fno/edit?ouid=104118343287414385523#heading=h.9c1pem2mvgls)). KG validated this approach by explaining that a faster release maintains momentum, creating a better parabolic path, while noting that precise calculations are required to ensure the attachment does not inadvertently lift or throw the flag after release ([01:05:59](https://docs.google.com/document/d/1hUP0BQ5jYt9u-ZWloowpmD3NV_ENDVK_IVrgWDD2Fno/edit?ouid=104118343287414385523#heading=h.58t6fpx0iynb)).
  - **Presentation Format and Documentation**: Adjoa Appiah inquired about the presentation strategy for the judges. KG clarified that the approach is twofold: providing detailed written documentation in files and utilizing an anchor slide during the poster presentation to demonstrate the iteration process, such as the changes made to runs 3 and 6. KG emphasized that all team members should familiarize themselves with the documentation to ensure consistency and to be prepared to answer any questions judges might ask, particularly regarding the team's iterative development process ([01:07:05](https://docs.google.com/document/d/1hUP0BQ5jYt9u-ZWloowpmD3NV_ENDVK_IVrgWDD2Fno/edit?ouid=104118343287414385523#heading=h.jdkxinqri8j9)).

  
  


*

# ð Transcript*  
*

 Jun 7, 2026

## Meeting Jun 7, 2026 at 15:57 BST - Transcript

### 00:00:20

  

**KG:** Hello children. Can you all hear me?

**Elliot Newman:** The F.

**Guhan Karthicraja:** Yes.

**Aaliya Mohamed:** Yes.

**KG:** Okay. So, what's the plan? Who is who is leading the conversation today?

**Guhan Karthicraja:** I I'm going to be here for like I just need to do some stuff about the robot iterations and then I'm not going to have to leave.

**KG:** Okay.

**Elliot Newman:** Uh,

**KG:** So,

**Elliot Newman:** I'm leading the

**KG:** all right.

**Elliot Newman:** conversation.

**KG:** Perfect.

**Elliot Newman:** Um, Well,

**KG:** You can get

**Elliot Newman:** hello everybody. Um, hello everybody. Um, I'm going to talk about the robot iterations. I've done some work on it already. I just need to finish it off and get some extra details. Um, some that I don't know about the robot and I was hoping you guys could help. Uh, if I share my screen and you should be able to see the robot iterations. Um,

**KG:** So you see um you you're doing attachment uh or the run iterations. Yeah, because I thought Flossy is doing the robot iterations or or

  
  

### 00:02:15

  

**Elliot Newman:** uh attachment

**KG:** have I misunderstood.

**Elliot Newman:** iterations.

**KG:** Okay.

**Elliot Newman:** I'm sorry.

**Guhan Karthicraja:** I mean I I have something. So while Elliot tries to get into his account, I can do my thing as well. Although I'm not sure if this is the one that you are doing as well because like I there's some stuff that was

**Elliot Newman:** Okay.

**KG:** Okay.

**Guhan Karthicraja:** already done which does not sound like I did it.

**Elliot Newman:** Are you able to share the screen on

**Guhan Karthicraja:** Um, I share my screen then.

**KG:** Elliot, do you want Gohan to go

**Guhan Karthicraja:** Is this the one you were doing?

**KG:** first?

**Elliot Newman:** Oh, yes. That's the one I was doing. I finished all of

**Guhan Karthicraja:** Yeah, I Yeah,

**Elliot Newman:** them.

**Guhan Karthicraja:** I filled in most of the like

**Elliot Newman:** I finished all of them except the images.

**KG:** All right. So Gohan, you know Elliot was supposed to do

**Guhan Karthicraja:** Wait, what? What? Elliot,

**KG:** that.

**Guhan Karthicraja:** why don't why don't you do it from just from my screen, you can tell me when to move.

  
  

### 00:03:34

  

**Elliot Newman:** Uh,

**KG:** Whose document is this?

**Elliot Newman:** look.

**KG:** Is

**Elliot Newman:** This doesn't look like my Is this my changes or is this

**KG:** this

**Guhan Karthicraja:** No, I I did most of these.

**Elliot Newman:** yours?

**Guhan Karthicraja:** It was I think you might have your own copy.

**KG:** not this is not yours to do,

**Guhan Karthicraja:** That's probably it.

**KG:** right? This is for Elliot to do.

**Guhan Karthicraja:** Wait, but I did

**KG:** Sorry, that's,

**Guhan Karthicraja:** it.

**KG:** you know, keep it to yourself. If Elliot needs any help, you can help. Okay,

**Guhan Karthicraja:** I think Elliot has his own copy of this.

**KG:** so let Elliot do this.

**Elliot Newman:** Are you able to show the slides? Not yet. Did you not press? I did. So, where's the slides?

**KG:** Is there any other way you can share Elliot? Is it u you have a local copy?

**Elliot Newman:** Uh, my internet doesn't seem to be working. It says I lost connection. That's your internet. Your internet's working. It says here though.

  
  

### 00:05:44

  

**Elliot Newman:** Trying to reconnect. anymore, right? Yeah. Uh, sorry guys, I have it now.

**KG:** All right.

**Elliot Newman:** What? What? A window. Yes. What are you doing now? Oh, I'm just putting it on to here so I can share it on the same uh Could you guys see it?

**KG:** Yeah, we can see. Maybe you want to go all the way up and start from the

**Elliot Newman:** Um,

**KG:** beginning.

**Elliot Newman:** I needed help on run one because it was like half filled in, but um, I wasn't sure about the rest cuz it was such a big attachment. Um, I have I have two questions that I'd like to ask. Um, what are the pre- regional iterations to run one the dual emitted arm? Uh,

**KG:** question.

**Guhan Karthicraja:** Uh yeah, one second. I'm just checking. Uh I mean what I have on my copy is that we we made

**Elliot Newman:** anyone

**KG:** Yeah.

**Guhan Karthicraja:** the arm lighter uh so that it's easier to control.

  
  

### 00:07:31

  

**Guhan Karthicraja:** Um Oh,

**Elliot Newman:** Yeah.

**Guhan Karthicraja:** no. That was that was post. Uh yeah, we'll talk about

**Elliot Newman:** Uh, is there any changes to the code at all?

**Guhan Karthicraja:** I'll sing. No, that was after the region. It's hard to say for the code for regionals cuz like I don't think there is

**Elliot Newman:** Okay. Um, I'd also like Oh,

**Guhan Karthicraja:** also uh for post regionals for the code you could say we did the sand

**Elliot Newman:** sorry.

**Guhan Karthicraja:** first or design I don't know which one it really I mean no uh post regionals

**Elliot Newman:** Oh, post regions. We're going to have after. Okay.

**Guhan Karthicraja:** Oh yeah.

**Elliot Newman:** Uh, any others?

**KG:** You had a Gohan. You had a a wheelchair for the the flag,

**Guhan Karthicraja:** Oh, wait. I know what we did in the regionals.

**KG:** the

**Guhan Karthicraja:** We added the wheels, the side wheels.

**KG:** you had a table,

**Elliot Newman:** Oh,

**KG:** but also you you know for the flag you had a seat and

  
  

### 00:09:01

  

**Elliot Newman:** sorry.

**Guhan Karthicraja:** Oh, yeah. That was post regionals,

**KG:** Okay.

**Guhan Karthicraja:** not pre-regionals.

**Elliot Newman:** Uh, I'd also like to ask about post nationals. What happened then? If anyone would care to answer,

**KG:** I

**Elliot Newman:** okay. Um, never mind.

**Guhan Karthicraja:** Oh, wait.

**KG:** am.

**Elliot Newman:** Um,

**Guhan Karthicraja:** Um, I do have one for post national. Oh, yes. Not yet. Um, so we um we we made the wheels go down like we made it go

**Elliot Newman:** okay.

**Guhan Karthicraja:** lower. That's the train.

**Elliot Newman:** Okay. Yeah, that's a good one. Uh, is there any changes to the code at all or Oh, yeah. Besides Oh, no. That's in post regionals.

**KG:** The stall prevention.

**Elliot Newman:** Uh,

**KG:** When did we prevention

**Elliot Newman:** that's post regionals.

**KG:** implemented?

**Elliot Newman:** post regions.

**KG:** Okay.

**Elliot Newman:** Um, that's fine. We can go on to run two. Um, I had, um, the three questions to ask. Um, by the way, I don't have any images.

  
  

### 00:10:28

  

**Elliot Newman:** I couldn't find them on any of the presentations. Um, I found some but runs

**KG:** Let's uh just a second. Gohan,

**Elliot Newman:** two.

**Guhan Karthicraja:** Yeah,

**KG:** is there anything else for run one?

**Guhan Karthicraja:** the I think he has one. Oh, also we changed the um So, do you know the thing that raises the raises the ship? We made it thinner. Oh,

**Elliot Newman:** Okay.

**Guhan Karthicraja:** yeah.

**Elliot Newman:** Oh, yeah. We did.

**Guhan Karthicraja:** Now we do.

**Elliot Newman:** Um

**KG:** And I think uh there were times I thought this when you pulled the sand it got trapped. So you guys made an adjustment so that it doesn't get trapped,

**Elliot Newman:** Okay.

**KG:** right?

**Guhan Karthicraja:** adjustment so it doesn't get dragged.

**KG:** Now the when you pull the sand cover,

**Elliot Newman:** Awesome.

**KG:** right? Sometimes it just slipped through and it was not falling.

**Guhan Karthicraja:** Yeah,

**KG:** That was okay.

**Guhan Karthicraja:** we we just That was code changed.

**KG:** But also I

**Guhan Karthicraja:** No, no, no, no, no, no, no, no.

  
  

### 00:11:49

  

**Elliot Newman:** Oh,

**KG:** remember

**Guhan Karthicraja:** Don't just It was minor changes to the um to the sand uh method, but like we also like it was mainly with speed changes in the code.

**KG:** There was another one I remember Gohan failed.

**Elliot Newman:** that's

**Guhan Karthicraja:** LPS. Oh yeah,

**KG:** When it failed once,

**Guhan Karthicraja:** LP.

**KG:** we found that the frame was actually hitting the um the the lever for the sand,

**Guhan Karthicraja:** Oh, wait,

**KG:** right?

**Guhan Karthicraja:** wait. One thing before Elliot, wait.

**KG:** That was

**Guhan Karthicraja:** For pre-

**Elliot Newman:** Yeah.

**Guhan Karthicraja:** regionals, um before we went to the dual mode arm,

**Elliot Newman:** Yeah.

**Guhan Karthicraja:** um we had like this other way where we do both missions separately and go around and then go to the other side. Um but then we change the geomet.

**Elliot Newman:** Okay.

**Guhan Karthicraja:** And that's just

**Elliot Newman:** Okay. Uh, I'll put that in my notes to add that you did both missions separately. Okay.

**KG:** Guhan,

**Elliot Newman:** Mission

**KG:** when did you make this change where you know if the sand mission failed then you couldn't reach the flag because it was stuck somewhere and we removed some parts.

  
  

### 00:13:04

  

**KG:** I remember there was a frame or something that you built so that it could lodge

**Guhan Karthicraja:** Oh yeah, we just moved the whole thing back.

**KG:** better.

**Guhan Karthicraja:** Yeah, I I think remove the frame.

**Elliot Newman:** Stop.

**Guhan Karthicraja:** It was Alia's idea or something.

**KG:** Okay, make a note of that too because one of the

**Guhan Karthicraja:** Was it? We removed No. No. Did we remove the frame? Yeah.

**KG:** fail

**Guhan Karthicraja:** We did. And then we like thinned everything out.

**Elliot Newman:** Uh, pardon. Can you say that again,

**Guhan Karthicraja:** Well, I think it's best if you explain it, Daddy.

**Elliot Newman:** please?

**Guhan Karthicraja:** But it's I I don't really know how to

**KG:** Um I think when the you know if the sand mission failed um then the it it was blocking the robot from um lodging itself correctly. So we needed to remove any of those uh blockers along the passage and therefore it could it can always have a free movement into the mission.

**Elliot Newman:** Okay, thank Thank you. Uh, is there any more or can we go into round

  
  

### 00:14:22

  

**KG:** Anybody else? Um,

**Elliot Newman:** two?

**KG:** who else we have in the call? Alia, Flossy, that's I see eight. 1 2 3 4 5 6 7. Who is the other person? Oh, that's all us. Okay, I think that that won't everything, I guess.

**Elliot Newman:** Thank you. Um, next to run two, I have all the access and passive components. However, the pre-regional, post regional, and post national I wasn't able to do. Um, can we start with the pre-regional um, please? Does anyone know about

**KG:** Uh Gohan,

**Elliot Newman:** that?

**KG:** this is run two. Yeah, this is the what is that? The map reveal.

**Elliot Newman:** Yeah. Oh, no. One and two. Um,

**KG:** Yeah. Yeah. That's map reveal.

**Elliot Newman:** okay.

**KG:** Is that no picking the brush and map reveal?

**Elliot Newman:** Oh, yeah. Yeah. Sorry.

**KG:** I think the first time I I don't even remember how it was the first time.

**Elliot Newman:** Yeah.

**KG:** the first time I think um it was unlocking the m you know the I don't know what it is Gohan you see those green green

  
  

### 00:16:02

  

**Guhan Karthicraja:** green what?

**KG:** right no this is this is your run

**Guhan Karthicraja:** Green cubes. Yeah, I know.

**KG:** too yeah yeah yeah why don't you explain what was there for

**Guhan Karthicraja:** Map reveal.

**Elliot Newman:** Um,

**KG:** regionals and what change you made for um post

**Guhan Karthicraja:** So um in the regionals what we had was pre-reg wait is there

**KG:** regionals.

**Guhan Karthicraja:** pre-regionals pre-regionals is the same? No, no, pre-regionals we had um we had a detachable um it was

**Elliot Newman:** It's

**Guhan Karthicraja:** a a detachable piece onto the um onto the robot which would which would come out after completing miss um after completing mission two. Wait, wait, wait. No. Uh I can explain that. Um so it was a detachable piece which had um something that uh it was a detachable piece um which would complete mission two passively. Um, and we would have two motors to pick up the top soil and the and in fact back then actually um back then no two active components. They were actually like two like prongs sort of uh which collected them.

  
  

### 00:17:32

  

**Guhan Karthicraja:** Uh this was our very first iteration. Um, and then after that, um, instead of having prongs, we'd have like a nest of axles which we'd slam upon it. Wait, Elliot,

**Elliot Newman:** Yeah.

**Guhan Karthicraja:** um, you know how you like drive in you can drive into the brush and wait, you can drive into the brush and pick it up like that, right?

**Elliot Newman:** Like what?

**Guhan Karthicraja:** That's sort of So, so here's the brush.

**Elliot Newman:** Sorry.

**Guhan Karthicraja:** around like what? Okay, here's the brush and here's the prong. You do that and then pick it up like an arm.

**Elliot Newman:** Oh, yes.

**Guhan Karthicraja:** That's our first one. Yeah, that is our second one was like a bed of axles which you like slam on top of it like we do today. Second one is the one the second one was the one where we had that rubber band that went down like that. Um, the second one went like that, right? And then with a bunch of axles and it pick it up.

  
  

### 00:18:30

  

**Elliot Newman:** Yeah.

**Guhan Karthicraja:** The third one for the brush, we had like two angled beams with a rubber band uh slightly in front,

**Elliot Newman:** Oh my god.

**Guhan Karthicraja:** which we would use a rack and pinion to lower into which would complete everything as well. It would complete the whole of mission one, right? And then for the final edition, we uh just we made the rubber band truck, but three regionals. Um the detachable piece was still there for the the regional and

**Elliot Newman:** Um when you say a rack and pinion to complete um the

**Guhan Karthicraja:** also

**Elliot Newman:** whole mission one,

**Guhan Karthicraja:** so mission two was always the same.

**Elliot Newman:** what did mission two how did you complete mission two?

**Guhan Karthicraja:** It was This is all for the brush.

**Elliot Newman:** Okay.

**Guhan Karthicraja:** Mission two was using that detachable piece and an arm.

**Elliot Newman:** Okay.

**Guhan Karthicraja:** Wait,

**Elliot Newman:** Okay, thank

**Guhan Karthicraja:** I I have a video I can show you of one of them just to get like an

**Elliot Newman:** you.

**KG:** any

**Elliot Newman:** Um,

  
  

### 00:19:27

  

**Guhan Karthicraja:** understanding.

**Elliot Newman:** okay.

**KG:** if if Elliot has what he wants to No, then you can move on. We don't want to waste time. Also,

**Elliot Newman:** Okay.

**KG:** do you have everything you want Elliot or you want to take a look at

**Elliot Newman:** Um uh we could take a look at it after I

**KG:** it

**Elliot Newman:** finished all my things

**KG:** and send it over to Elliot whoever has that?

**Elliot Newman:** possibly.

**KG:** Okay. I think another um important change um post regionals was

**Elliot Newman:** Yeah.

**KG:** the aligner, right? And you don't you remove that detachable attachment that I think as number two. Number three, you reduce the length of the arc um for the one that lifts the um sample soil sample and then you're reaching out you know reaching out the brush from the side and you

**Elliot Newman:** No.

**KG:** manage to save quite a bit of time on there.

**Aaliya Mohamed:** After

**KG:** Correct.

**Elliot Newman:** Okay.

**KG:** Anything more?

**Aaliya Mohamed:** Guhan and Elliot could present mission analysis.

**KG:** What are you saying, Alia?

**Aaliya Mohamed:** Is it okay that after Guhan and Elliot could I present mission analysis?

  
  

### 00:20:57

  

**KG:** Okay.

**Elliot Newman:** Uh-huh.

**KG:** So I'm I'm just thinking see you approach the brush from a different angle. Initially I think it was slamming and you needed to wait for the brush to uh you know settle because it was wave it was oscillating. So you needed to wait and then they you know they wanted to save the time. So he's now doing it from the from the side angle and because the brush is moved at the very beginning itself by the time um you are reaching

**Elliot Newman:** There you go.

**KG:** up for the brush it's already the you know the oscillation has already cover everything I don't think any more post nationals

**Elliot Newman:** Nothing

**KG:** Gohan. Gohan.

**Guhan Karthicraja:** He's talking with

**Elliot Newman:** wrong.

**Guhan Karthicraja:** auntie post

**KG:** Okay. What is the change you guys made post nationals?

**Guhan Karthicraja:** nationals 4 on two. Um, we haven't we haven't really made anything other than um stabilizing the um stabilizing the rubber band trap by adding um instead of one arm holding the rubber band trap, we added two.

**KG:** Okay.

**Elliot Newman:** Uh, thank you.

  
  

### 00:22:45

  

**Elliot Newman:** Um, any changes to the code?

**Guhan Karthicraja:** All right.

**KG:** I think they they have um um two things I remember. um they are slowing down right before it reaches or slams onto the brush. Um because when you approach it from a longer arc um it it failed a couple of times, right? So when you when you slam it from, you know, with a longer arc. So what they're doing is they're going very close to the brush and stop it there for a fraction of a second and then they approach it again. So they're slowing down a bit and uh they are approaching it from a much um smaller radius.

**Elliot Newman:** Okay. Thank you. Uh well, the rest I actually have completed the rest. However, the rest go through the rest of um I'd like you to check um all of them to see if they're okay. Go through the rest. Um I'll say them out loud and then you can if um you can stop me if you have anything to say. Um so first missions three which has missions involved missions three and four.

  
  

### 00:24:17

  

**Elliot Newman:** Um, the ISO from passive components, a prong that moves in a circular movement to pick up the precious jewel and lift it up. Um, um, I think um, I added a bit here that's supposed to say the arm lifts the mic up. Um, I might have added that in the um, post nationals, but I'm not sure. Um so the pre-regionals iterations the design a claw to pick up the precious artifact for careful recovery and a lifting arm to complete mission explorer uh code. We would go forwards and then do a turn and then move too much forwards to so we could reverse um into the forum to complete mission three and four. Uh is there anything wrong with that?

**Guhan Karthicraja:** Wait. Um,

**Elliot Newman:** Um

**Guhan Karthicraja:** what do you mean by a turn and two move too much forward? Oh, yeah. No, I know what you mean. I know what you mean. No.

**Elliot Newman:** so okay.

**Guhan Karthicraja:** Yeah, I know. Because you make that second turn back.

  
  

### 00:25:22

  

**Guhan Karthicraja:** Um,

**KG:** What is what is too much?

**Elliot Newman:** Yeah.

**KG:** Too much is

**Guhan Karthicraja:** no. Daddy,

**KG:** um

**Guhan Karthicraja:** what would happen is he'd go there, complete like an uh like a onehe turn, right? And All right. Um, we would a lifting arm to complete mine shaft, a claw to pick up. Um, I I don't know. Maybe for the claw you could just just give a bit more detail like a rubber band powered claw or

**Elliot Newman:** Okay. Any

**Guhan Karthicraja:** something.

**Elliot Newman:** questions?

**KG:** It's

**Guhan Karthicraja:** Oh, and also we've um we haven't said anything about the prongs either.

**KG:** Um

**Guhan Karthicraja:** The prongs or the rack and pinion.

**Elliot Newman:** Oh. Um, yeah, I said that in my notes. I I've put it in here, but I wasn't really sure how to. Um, should I put an extra page in to add that bit,

**KG:** I think I think the very

**Elliot Newman:** or should I um Sorry.

**KG:** important aspect of that attachment Elliot you've got the you know up and down movement through your rack and pinion the grabbing itself was a passive attachment isn't it?

  
  

### 00:26:34

  

**KG:** So you are using some set of a pressure to sense the artifact is right behind and it triggers um the cloud to hold on to it

**Elliot Newman:** Yeah. Okay. I've added that about the rock. Um

**KG:** and post regionals.

**Elliot Newman:** uh I'll say I'm sorry.

**KG:** So

**Elliot Newman:** um a design um prongs to open and close around the precious artifact and a lifting arm to complete mine shaft explorer. We go in with a curve into the side of mission three and four.

**KG:** yeah. So you have made two changes. One for both the missions, right? So lifting up the Minecraft. So you have you have a new design um and also to pick up the artifact. The the biggest problem that we have overcame is that the artifact um because it's a it's a lighter object. It it tends to move. So you needed to be very very precise. Um so you approached it with a wider um you know arm that can shrink or you know uh constrict and hold on to that.

  
  

### 00:28:04

  

**KG:** So that is the design behind it right and you needed to extract that artifact through that particular space. Um any other way would have been you know would have would have spilled it out. So you needed to approach through the exact gap that was available and open and uh open the arm, go close to the artifact, close it and then pull it back. That was um mission three.

**Elliot Newman:** Okay. So,

**KG:** Surely

**Elliot Newman:** for the post nationals, I mean, is there anything else for the post regionals?

**KG:** the code also has changed. Um I don't know um maybe you can take you know take a look at the code because quite a bit would have changed. Um but coming into the post nationals so we have two we pursued two design no three designs actually right. So one was to somehow provide a lift to the previous okay the challenge with the nationals was you needed you were able to

**Elliot Newman:** Ocean.

**KG:** get hold of the artifact but you couldn't take it out because um you know when you move out at the same height uh there were more barriers for it to tip over.

  
  

### 00:29:34

  

**KG:** So um one of the idea was you know after you grabbed it

**Elliot Newman:** Good.

**KG:** if you can lift the same uh prong um slightly and create some level of height. So that was one approach I think flossy what what was your design do you want to explain that that is you know let's say option

**Florence Ingram:** Uh yeah. So my design is a very simple just basically lifting arm with two prongs at the side that comes in just lifts it up and reverses. It comes in from the side. So I would say the main advantage of my design is the fact that it's able to lift.

**KG:** Mhm.

**Elliot Newman:** Stop.

**Florence Ingram:** Whereas most of our designs have focused on closing around it and then because we need that lift to get it out. That's quite hard to achieve. But the main drawback is you have to be so precise with your angles with your movements because you don't have any like wiggle room to close it around the artifact.

**Elliot Newman:** Okay.

**KG:** Yeah.

**Florence Ingram:** Um I would say

  
  

### 00:30:32

  

**KG:** Yeah. So take a note of that. Um Elliot.

**Elliot Newman:** Yeah,

**KG:** So that's all

**Elliot Newman:** I'm putting it all in a word document. All the different um ones to the ones I

**KG:** right.

**Elliot Newman:** said.

**KG:** The option three which is I think we have a much be better success is the circular lift.

**Elliot Newman:** Uh yeah, that's the one I've said. um the prongs that move in circular movement which have axles that have elastic bands to pick

**KG:** So

**Elliot Newman:** up the precious jewel and lifts mission three up. Um we move forwards and then we only move the left drive to turn into the

**KG:** yeah.

**Elliot Newman:** mission.

**KG:** So the main thing is the the circular movement we designed in a way that uh it also it provides constriction. Therefore it can close onto the um the artifact. So any the challenge for example Flossy said that could be overcome because you have lot large space to maneuver and secondly it also provides a bit of a lift. So you have two advantages because you are able to move in a circular path and the attachment is also quite simple comparatively and uh I think we should mention this.

  
  

### 00:31:55

  

**KG:** I have not seen anyone else has done that. So you should uh call that out. Look, this is

**Guhan Karthicraja:** I know um the idea that art been made is very very very good,

**KG:** a

**Guhan Karthicraja:** isn't it?

**KG:** naughty Gohan. He's not giving credit to me. I gave that design idea.

**Elliot Newman:** Um

**KG:** See, I think um you copied because I gave that idea to Flossy.

**Guhan Karthicraja:** What? Daddy, I made this idea.

**KG:** Okay, fine. Let's move

**Elliot Newman:** okay. So um going on to run four um the active and passive components.

**KG:** on.

**Elliot Newman:** The passive is collector. Um where I put a colon is where we're supposed to have images which I can find in the presentations. Um uh also a flag dropper guard. Um it's another passive component. And the two active components are a flag dropper and a lift arm to do mission three 13 sorry. Um the missions involved were a half of 15, um a third of 14 and um the full of 13. The reasons I put like halves and thirds is because it only does a part.

  
  

### 00:33:23

  

**Elliot Newman:** For example, in mission 15, I mean mission 14, it's the three sites. However, run four only puts it in one. Um so is that okay?

**Guhan Karthicraja:** Um, there's like a few designs that you've like missed. Um, I don't know if the flag dropper guards counters the box for the flag, but if it doesn't, that also should be added. Um,

**Elliot Newman:** Uh, it sorry, I should have said

**Guhan Karthicraja:** okay. Um,

**Elliot Newman:** that.

**Guhan Karthicraja:** and also there was a design uh we made where it would swing round sort of like the run six um sort of like the run six uh oneway system. It swings around like that and then it would place the flag and then it would come back. But we removed that. That was post regionals. Post regionals. Oh no, it's post regionals. We didn't do this after the nationals. Oh, you did that buffalo.

**Elliot Newman:** Okay, I put a note of that. Um, just to ask, when I'm doing all these extra um, designs that were not the ones that we used for the competition, where do I put them?

  
  

### 00:34:42

  

**Elliot Newman:** Cuz there's not enough space to put them in the table. So, should I add an extra slide or extra page about that um,

**Guhan Karthicraja:** You you should you should make um you should make that column slightly longer

**Elliot Newman:** design?

**Guhan Karthicraja:** and then edit the text box like yeah sort of like that except like not that

**KG:** Yeah.

**Elliot Newman:** Okay.

**KG:** Yeah.

**Guhan Karthicraja:** much.

**KG:** Yeah. See, why don't you try and put some bullet points?

**Guhan Karthicraja:** No.

**KG:** You could you could actually put put some footnotes and I don't know how this table works in Canva. What you can do is Elliot what you can you know you can create a text box and put it at the footer okay for the whole length and

**Guhan Karthicraja:** It's amazing.

**KG:** then you can give some further explanation and then you can reference that back in your um text. Yeah. So for example,

**Elliot Newman:** Okay.

**KG:** column for you wanted to say something, you can put in a little star and then um have a

**Elliot Newman:** Yeah.

**KG:** text box right below that slide where you can put in the same star or note.

  
  

### 00:35:55

  

**KG:** Um and then you can give that explanation there. If you have something more to

**Elliot Newman:** Okay. Thank you. Um, can we go on to the designs that I found that we used for the

**KG:** I think this one went through a lot of coding changes as I recall Gohan in terms of where

**Elliot Newman:** competitions?

**KG:** it eventually uh stops and how it turns into a particular degree and therefore it was not uh undoing the uh the statute. You you also had a lot of problems of you know when you the mission eight actually pushing out the objects that you put in at you know run four u you know run eight actually undid run four. Can you explain those

**Guhan Karthicraja:** What?

**KG:** details?

**Guhan Karthicraja:** No. But daddy, one one more thing. Uh oh, wait. Fine. Just explain details. Wait, should I should I do it?

**KG:** Yeah. Who are you

**Guhan Karthicraja:** Um, so I think this comes more under run eight instead of run

**KG:** asking?

**Guhan Karthicraja:** four. But the main thing that run 8 did for run four is that it would push out the artifacts that um run four put in. So what we did was uh in the code we made it so that it avoided the artifacts and go somewhere nearer to the statue.

  
  

### 00:37:29

  

**KG:** Yeah,

**Elliot Newman:** Uh,

**KG:** that was done. And also Gohan,

**Elliot Newman:** okay.

**KG:** you came up with that loose um attachment for positioning the flag so that when you go back to the red area, red home or whatever the other home area, it was um it was not disturbing any other mission. So that design,

**Guhan Karthicraja:** Yeah,

**KG:** can you explain how did he arrive at that and what was there before this?

**Guhan Karthicraja:** it was actually like an accidental uh thing. Uh we were trying to make something that would just raise up and um we couldn't really find a way to uh stabilize it. So we we just un uh didn't stabilize it and like we found out that um instead we found out that it actually helped us um in not undoing any of the missions. And so instead of trying to rectify it and keeping everything stable, we decided to keep it.

**KG:** Mhm.

**Guhan Karthicraja:** Stop the videos if I

**KG:** I think it is a unique idea. You should name it dancing, you know, prongs or something like that.

  
  

### 00:39:02

  

**KG:** Right. I don't think you know anyone has that design either. Uh it's a free flowing um holder or a box or a anyway. So that is one and um the angle in which the uh parts are pushed

**Elliot Newman:** Sweet.

**KG:** in run eight. So that's number two. you know that is because you didn't want to undo the three uh run four and run four how you place those objects because during the regionals are I don't know when it was regionals right or nationals it actually pushed all the oh yes it was nationals so it actually tried to push uh the um sand samples and then pull it back we lost 15 points otherwise we would we would have been we would have been 500 in in the nationals We got 485 because those three parts, the brush, um the the sand, um soil collection, you know, soil sample, they they that came back with the mission. How did you fix that, Gohan?

**Guhan Karthicraja:** Sorry,

**KG:** How did you fix that issue?

**Guhan Karthicraja:** wait. Could you Oh, wait,

**KG:** What?

**Guhan Karthicraja:** wait, wait, wait.

  
  

### 00:40:26

  

**Guhan Karthicraja:** We're thinking. We're thinking. Wait. What was the issue again?

**KG:** Okay. So, can you come here because I think you're not paying attention and we would be very productive.

**Guhan Karthicraja:** All right. All right. I'm on video

**KG:** Yeah. Stay on the video. So in you know during the nationals

**Guhan Karthicraja:** now.

**KG:** um the soil sample that you picked up from mission run to and the brush that did not get delivered into the arena. It came back with a attachment.

**Guhan Karthicraja:** Oh, yep. Yep. I know. Um so basically uh it we used the physics to

**KG:** How did you fix it?

**Guhan Karthicraja:** solve it. Uh so uh what we found that is when the arm is longer it ends up traveling at a higher

**KG:** Not that one that you're explaining run two.

**Guhan Karthicraja:** speed.

**KG:** I'm saying run four.

**Guhan Karthicraja:** Oh my god.

**KG:** Remember during the during the nationals the brush as well as

**Guhan Karthicraja:** What am I doing?

**KG:** the grass sample that you picked you tried to deliver into arena but it did not and it came back with the attachment and it went to the other home area.

  
  

### 00:41:39

  

**Guhan Karthicraja:** Oh. Oh, yeah. We had to change the positioning of the artifacts. Um, we also Does that go under design or code? We also had to um

**KG:** The thing is it the first place it it got trapped because of the friction. So I asked you guys to reduce the friction and

**Guhan Karthicraja:** What? I remember changing.

**KG:** I

**Guhan Karthicraja:** Yeah, because so we made the inside smoother. Yeah. So that it would release easier and wouldn't get stuck on anything. Um, we also made the area bigger so that it wouldn't get stuck on each other and like get captive. And it also went

**KG:** Okay. Yeah.

**Elliot Newman:** Um,

**KG:** Post

**Elliot Newman:** did we also did we also make a code change as well when we um this

**KG:** national.

**Elliot Newman:** problem to fix this problem we lifted the arm a bit more I think or less um to fix that problem as well so things don't get stuck or like

**KG:** One of the I saw was the robot now reverses before it approaches

  
  

### 00:42:42

  

**Elliot Newman:** hit

**KG:** the other home area. So it goes in reverse, you know, instead of running forward. Um why why was it Arvin? No, the the after the run four, after you everything in the arena,

**Guhan Karthicraja:** Yeah.

**KG:** the robot reverses itself and then goes forward to the next home area.

**Guhan Karthicraja:** Um, so what you're asking is why why did it reverse? Oh, so it reversed because it would would have got stuck on um mission um the

**KG:** Yeah.

**Guhan Karthicraja:** angler artifacts because um it had had like it had like a little gap in it that would that could get the prongs stuck in it. So what we did, we reversed and that would more that would brush over everything else instead of

**KG:** Okay. All right.

**Guhan Karthicraja:** uh music.

**KG:** Let's move on. I think that's enough of

**Guhan Karthicraja:** You need to get on

**KG:** information.

**Guhan Karthicraja:** video.

**Elliot Newman:** Um, okay. Thank you. Uh, next going on to round five. Uh, I'll say this. Uh, missions involved were missions five, six, and seven.

  
  

### 00:44:01

  

**Elliot Newman:** Um, active and passive components. The passive were the aligner, the one-way system, the collector, the collector of the boulders, the axle that completes mission six. Active were arms to collect the millstones and rack and pinion to release the boulders. Is that right?

**Guhan Karthicraja:** Yo,

**Elliot Newman:** Or am I missing something?

**Guhan Karthicraja:** could you count um as the passive element? Could you count the um did you count could you count the uh little thing that the the uh I don't have to explain the thing on the floor to collect the boulders? Would you count that as a passive element or it's just a holder? Yeah, holder.

**Elliot Newman:** Oh,

**Guhan Karthicraja:** Would you come?

**Elliot Newman:** I said the collector of the collector of the boulders or something

**Guhan Karthicraja:** Oh, that that's Yeah. Yeah. The holder. Yeah. Yeah. Yeah. The holder.

**Elliot Newman:** else.

**Guhan Karthicraja:** Yeah. Uh the axle that completes mission six. Axle collected. Oh, collected. Wait, you I think you mean mission seven for the axle that completes mission

  
  

### 00:44:59

  

**Elliot Newman:** Oh, sorry.

**Guhan Karthicraja:** six.

**Elliot Newman:** I think I got that.

**Guhan Karthicraja:** No,

**Elliot Newman:** Let me

**Guhan Karthicraja:** the axle does complete mission.

**KG:** I think for

**Guhan Karthicraja:** Wait, what axle are you talking about? The one that goes like turns this way.

**Elliot Newman:** stop.

**Guhan Karthicraja:** This way on the uh No,

**KG:** three.

**Guhan Karthicraja:** that's mission five. That's mission five. I thought you were talking about the one that goes and lifts the item. Yeah, it's mission five, not

**KG:** So I remember for regionals did we have uh aligners for

**Guhan Karthicraja:** six.

**Elliot Newman:** Okay.

**KG:** regional

**Guhan Karthicraja:** I think we did have a we line up for a region. Oh, yeah.

**Elliot Newman:** Yeah, we did.

**Guhan Karthicraja:** Yeah.

**Elliot Newman:** I looked back at the um regional competition video, one of the runs. We did have a line for

**Guhan Karthicraja:** Video.

**KG:** Yeah, I thought we didn't have and also you know for lifting

**Elliot Newman:** that.

**KG:** heavier um we we had a single pin at the end of that uh lift arm.

  
  

### 00:45:49

  

**KG:** Right now you have two. So that is one change.

**Guhan Karthicraja:** Yes. Okay. Just the

**KG:** And uh I think the gear ratio also has changed because I remember it was those um you know

**Guhan Karthicraja:** luck.

**KG:** four pin gears. Remember that one with with you have like the cross rather than the gears that you have,

**Elliot Newman:** Is this for the arm or the rack and pinion?

**KG:** right? The long arm which not the rack and pinion the

**Guhan Karthicraja:** Um,

**Elliot Newman:** Oh, okay. Yeah.

**KG:** long and

**Elliot Newman:** Um, I put that in the post regionals that the changed

**KG:** and I also remember um that the rack and pinion moved out.

**Elliot Newman:** ratio.

**KG:** So we needed to stop from entirely moving

**Guhan Karthicraja:** wait. One more thing. Um,

**KG:** out.

**Guhan Karthicraja:** you know that same arm

**Elliot Newman:** All right.

**Guhan Karthicraja:** it um same arm.

**Elliot Newman:** Yeah.

**Guhan Karthicraja:** This is pre-regionals um as well. So um it used to it used to have like one axle which did it

  
  

### 00:46:49

  

**Elliot Newman:** Okay.

**Guhan Karthicraja:** but sometimes it would like miss. So we added a second one so it doesn't like a second axle uh

**KG:** That's regionals.

**Guhan Karthicraja:** collector increase the consistency.

**KG:** Yes. Yeah. And post nationals I think only the you know post regionals you also had the parabolic turn

**Elliot Newman:** Good.

**KG:** implemented. So that's on the coding front but it also has the physics element of it.

**Elliot Newman:** Yeah, I put

**KG:** So you and post nationals I think the um the

**Elliot Newman:** that.

**KG:** only thing is the oneway lock right we got the

**Elliot Newman:** Yeah, I've put that for design.

**KG:** oneway lock and uh then I think after the

**Elliot Newman:** Yeah.

**KG:** regionals the position the the le levers or what do you call the the levelers right where you can position um with a pre you know You can set a preset position. What do you call those extra pin extra length um beams? I have seen that that is just to make sure that you're um you know you're always positioning correctly and um I remember we had a lot of issues with u pushing the our blocks.

  
  

### 00:48:16

  

**KG:** Sometimes it didn't release, sometime it was flipping over to the other side. And um so how did we solve that? I think I think we solved that um by extending the length of that lever. So which is okay, you know, which is a minor change. You understand, Elliot? So you know quite a few times even though it actually the

**Elliot Newman:** What what le you talking about? Sorry.

**KG:** the rack and pinion for releasing the or block okay and that didn't work

**Elliot Newman:** Oh.

**KG:** um you know several times um because it was not engaging it was not on the right level so we fixed that and also we added some more uh depth to that attachment and therefore it can always engage and u I think initially Yeah, I think that's

**Guhan Karthicraja:** Um,

**KG:** enough.

**Guhan Karthicraja:** I also have one thing, but I don't really know when this was added, but it's like it's not really a thing that helps complete the missions, but there's someone added a little hook at the end of

**Elliot Newman:** Uh, yeah, that was Toby.

**Guhan Karthicraja:** mission hook

  
  

### 00:49:25

  

**Elliot Newman:** That was Toby. Um, and that was at the post regions. Post regions. Um,

**Guhan Karthicraja:** at the like a hook and it

**Elliot Newman:** I should probably add that. Are you talking about like the thing on the left side,

**Guhan Karthicraja:** like

**Elliot Newman:** the left bottom of the attachment that's supposed to like collect the boulders or like be a

**Guhan Karthicraja:** No. Oh yeah,

**Elliot Newman:** backup?

**Guhan Karthicraja:** there's that little axle on the bottom. And I'm also I'm talking about something else,

**Elliot Newman:** Yeah.

**Guhan Karthicraja:** but like that's one thing also.

**Elliot Newman:** Oh, okay.

**Guhan Karthicraja:** Yeah. Um there's It doesn't help with the mission,

**Elliot Newman:** Okay.

**Guhan Karthicraja:** but it's to help like put the mission on the table. So there's like a little hook. Oh yeah,

**Elliot Newman:** Oh, yeah. The hanger.

**Guhan Karthicraja:** that hanger.

**Elliot Newman:** The hanger I've put that I had added. um for the boulders um and added hanger onto the side of the table.

**Guhan Karthicraja:** Oh, now I see it.

  
  

### 00:50:06

  

**Elliot Newman:** Yeah,

**Guhan Karthicraja:** Sorry.

**Elliot Newman:** I put that. Thank you. Um okay,

**KG:** Okay.

**Elliot Newman:** so we're going to run six or any Okay.

**KG:** Yeah.

**Elliot Newman:** Um so run six is missions 10 to 11. Um uh we have passive and active components. passive one-way system which collects the scale pan, the jig, the aligner that raises the market. Sorry, I don't know why that says flags. um active components, the arm that which hits the bucket to unlock the scale pan and the rotational movement um for the scale pan like the for the rack and I mean oneway system um the rotational movement for that is active. Um, so pre-regionals one used three beams to create the one-way system. The jig it was it used a singular pin to align and a big gear to hit the bucket with the arm. The arm the arm had a claw to lift the market um um like it had two beams, sorry, and then it would lock in between them and hit it. Um um and the code we go down with the arm first before collecting the scale pan with the oneway system.

  
  

### 00:51:32

  

**Elliot Newman:** We use the arm to raise the market. Any other changes want to be made or was that okay?

**KG:** But this is after regionals. Yeah.

**Elliot Newman:** Uh, no before

**KG:** Oh, before regionals.

**Elliot Newman:** regionals.

**KG:** Okay. That's anything else.

**Elliot Newman:** Um, can I go into post regionals?

**KG:** Yeah.

**Elliot Newman:** Okay. Uh, used two axles. Design used two axles for the oneway system. The jig, it used a blue long panel to align to mission 101. Uh, has a the arm has a small stable stopper. And to hit the bucket, we use two beams connected by a 3x3 panel. Um, code. We do not use the arm to do the tiny market wares and do it in run seven. That's the only change I noticed. Um, anything else?

**KG:** Um, no, that's about right. And, um, you had a C, you had a gear to, um, press the bucket, right? What is it called?

**Elliot Newman:** Uh, that was for pre-regionals. We changed that in post national.

  
  

### 00:53:09

  

**KG:** Okay. And yeah, that's

**Elliot Newman:** Okay. Um, post nationalations,

**KG:** fine.

**Elliot Newman:** we used two smaller axles for the oneway system. We used a jig to align mission 10 11 and it is used upside down. We added an aligner to do the market wares and aligned to mission 11. Um, code changes. We go with the one-way system before hitting the bucket and we do a slight turn to do the market wares. Uh, anything

**KG:** So it's also the stall it you know this mission has stalled a few times.

**Elliot Newman:** else?

**KG:** So um who has implemented the stall prevention for this? I asked um can you check with Gohan? has he implemented?

**Guhan Karthicraja:** Um I don't think you've done that yet.

**KG:** So then you should do that. We we don't have time.

**Guhan Karthicraja:** Yeah.

**KG:** You're doing the visuals today, but you know um we we can't leave that.

**Guhan Karthicraja:** Yeah.

**KG:** Yeah.

**Guhan Karthicraja:** We forgotten this. Oh s\*\*\*.

**KG:** Add that Elliot and uh make sure that that is done.

  
  

### 00:54:22

  

**Elliot Newman:** Okay.

**KG:** So

**Elliot Newman:** Okay. Thank you. Can I go on to miss run seven? Okay. Run seven.

**KG:** yeah.

**Elliot Newman:** Uh mission eight active components. Well, there's only active u one hammer and one rotational arm. That was for post regionals. I just added that because um that was something that we used uh pre-regional iterations. Uh design using four small wheels to counterweight. We used two heavy black wheels for the hammer and we had no rotational arm. Is that right?

**KG:** Yeah.

**Elliot Newman:** Um

**KG:** See also the gear ratio has changed as a when you have a heavier object uh you have the larger gears.

**Elliot Newman:** and

**KG:** when you made a single um single wheel fitted. Now you have um No,

**Elliot Newman:** Oh, I said that. I said that in post reg post

**KG:** not I'm I'm talking about the gears.

**Elliot Newman:** regionals.

**KG:** You have a different

**Elliot Newman:** Yeah. increase I said in post regionals that um and increase the speed instead of the

  
  

### 00:55:39

  

**KG:** gear.

**Elliot Newman:** torque. In the regional competition, we actually used two heavy black wheels to hear um mission eight, but in nationals we used a tiny wheel and we focused on speed instead of torque. Um we also had a rotational arm in nationals that would hit the market wares. Um, and we used a small blue wheel. Um, in code we put both active components as a fast speed so we can complete them with power. Is that

**KG:** Yeah, that that's a good explanation.

**Elliot Newman:** right?

**KG:** See the the one thing you um you may want to write carefully is the correlation between speed and torque. um you know torque is the is more the force speed is the result of it right so if you have a you know sometimes you need a higher higher torque to get things started or sometimes you have a lower torque to get things started so in this case because you've used the gear ratio it is a lower torque and therefore it automatically reaches a higher speed very quickly yeah so for example hypothetically let's say 10 kilometer

  
  

### 00:56:58

  

**Elliot Newman:** Yeah.

**KG:** If you have if you need a higher torque, it might take you know 1 second to reach 10 km speed. But with a lower t lower gear ratio, lower torque, it reaches even you know faster and that is why you get that speed.

**Elliot Newman:** Okay. Yeah. Uh I'll talk about that a bit more. Um and in post nationals uh our design we took away the rotational arm as

**KG:** Okay.

**Elliot Newman:** we were not doing it in run six and we did not change the arm to the hammer. Sorry. Um code we took the rotational part away from the code. Um anything

**KG:** No,

**Elliot Newman:** else?

**KG:** I think that's good.

**Guhan Karthicraja:** Oh, I just wanted to add I think we we added some counterweights. Um Oh, yeah.

**Elliot Newman:** Oh,

**Guhan Karthicraja:** We added counterweight.

**Elliot Newman:** you've added cancel.

**Guhan Karthicraja:** Yeah, we Yeah,

**Elliot Newman:** Okay,

**Guhan Karthicraja:** like just now.

**Elliot Newman:** that's one

**KG:** Did he fix the issue he called out last time that he he couldn't put

  
  

### 00:58:00

  

**Guhan Karthicraja:** Oh,

**Elliot Newman:** key.

**Guhan Karthicraja:** what?

**KG:** the

**Guhan Karthicraja:** hit with the pin. Yeah. Well, we're not too sure what that pin is.

**KG:** Yeah.

**Guhan Karthicraja:** The the pin was Oh, yeah. Yeah. Yeah. Yeah. That's it. Yeah. Yeah. Yeah. We fixed that. We fixed that.

**Elliot Newman:** Okay, thank you.

**KG:** Can you take a photo and share it with Elliot so that he knows whatever he thought

**Elliot Newman:** Uh, could you also send it with is a nice call?

**KG:** about?

**Elliot Newman:** Um, could you also send it to her? Um, please so she knows. Okay, thank you. Um,

**KG:** Last

**Elliot Newman:** oh,

**KG:** one.

**Elliot Newman:** sorry. Can I go on to run eight?

**KG:** Yeah.

**Elliot Newman:** Okay, so um run eight. Um it has a half of mission three. So mission three actually has the part where the minecart from the opposing team side comes onto our side. Um and it does a um a third of mission 15 which is the sites.

  
  

### 00:59:05

  

**Elliot Newman:** Um and it does a half of 14 which is the forum. Um the active and passive components uh passive wheel cover. Uh we found this issue in regionals. Um and we fixed it in post regionals. Um, active fought to live mine cart flag dropper and dropper was all collected artifacts from the blue side. That good.

**KG:** Um,

**Elliot Newman:** Anything

**KG:** how did the m see the Minecraft curcy improved

**Elliot Newman:** else?

**KG:** post?

**Guhan Karthicraja:** say um oh uh we added like um a piece uh to the flag uh which stops it from like moving about when it's dropped and it also takes the impact so just in case it Yeah. So the flag the flag doesn't break anymore as well.

**KG:** Yeah, I think I sent it.

**Elliot Newman:** Is that in post nationals?

**Guhan Karthicraja:** Yeah. Yeah.

**Elliot Newman:** Oh,

**Guhan Karthicraja:** And Robin,

**KG:** It's It's only after you guys uh after you guys.

**Guhan Karthicraja:** it was a great idea.

**Elliot Newman:** okay.

**KG:** Oh, naughty Gohan. remember you guys said the flag dropping was not okay.

  
  

### 01:00:17

  

**Guhan Karthicraja:** idea.

**KG:** It was bouncy. So,

**Elliot Newman:** Wait

**Guhan Karthicraja:** Oh yeah,

**KG:** um let's

**Guhan Karthicraja:** something about like elastic bounce and like and then like force equals to the mass

**KG:** go.

**Guhan Karthicraja:** times the acceleration.

**Elliot Newman:** a

**Guhan Karthicraja:** So if you uh deep trace the acceleration or increase the mass uh

**Elliot Newman:** second.

**Guhan Karthicraja:** it will bounce less.

**KG:** Um

**Guhan Karthicraja:** Yeah. All right. Can

**KG:** That's that's I think you had a different explanation early on Buhan I think which was actually correct. Um because it's uh it's not you know I checked later it's not within one of those Newton laws. Uh you said something else. Um but let's uh let's clarify that part later.

**Elliot Newman:** Oh,

**KG:** Why? Basically you have elastic bounce. What is elastic bounce? Um if you throw anything when there is a collision the force transfers between

**Elliot Newman:** we

**KG:** two objects you know what you know the moving object transfers its force to the other one the other one transfer it back. So if you have a rubber and you throw it on a grass surface it bounces less but if you have a rubber a ball and you throw it on a on a steel surface or a metal it bounces more.

  
  

### 01:01:39

  

**KG:** Right? So that is the concept behind it. Um and the flag is has been bouncy. So you needed something to increase the surface. Um therefore um you know the energy transfer is better. So that's what we have done. I think um let let me discuss that and then we'll write it back on the um in the WhatsApp group. Okay.

**Elliot Newman:** Okay. Uh, can I go into post regionals and then we'll finish up on post nationals? Um, minor changes to the flag dropper and the artifact dropper.

**KG:** Mhm.

**Elliot Newman:** Change gear ratio in the fork which made it more accurate. um code change code for the fork and the reverse out and move forward into the forum or mission 14.

**KG:** Yeah. And you also needed to carefully avoid at all cost that you are not uh launching yourself into the mission mission three isn't it because you have a equipment constraint there um so that is one thing and I also gave the challenge that if the Minecraft from you know was pelted away by the other team into your map and it came in the way of run eight then what happens so I You guys have to work that out.

  
  

### 01:03:09

  

**KG:** Okay. And um see some of the concepts I I think you're you're not filling up the physics there. But the flag drop is uh is gravity, isn't it? So your calculations are all based on the gravity. So when you increase the mass and gravity is the force and then what happens? And same thing with um with with your CEO as well. You know, just because you added the wheel, why did it generate more force, right? You're also benefiting from the gravity.

**Elliot Newman:** I was going to do physics.

**KG:** And yeah,

**Elliot Newman:** explain with a nicer just so

**KG:** you can you can discuss that with her.

**Elliot Newman:** okay.

**KG:** Okay.

**Elliot Newman:** Uh finally post nationals uh design added a better wheel cover and hangs the flag dropper. Um sorry uh improvement improve the flag dropper um change the pins in the collector as well as adding a stopper to the fork. Um and minor change minor code changes. Is that

**KG:** What other code changes?

**Elliot Newman:** right?

**KG:** Um okay I think the speed at which this mission is uh at each stage um there's a lot of tuning up as far as as far as I recall Guhan you argued

  
  

### 01:04:51

  

**Elliot Newman:** Oh yeah.

**KG:** with me about how fast it should move and so on. So, do you have anything to say on

**Elliot Newman:** Uh, Luhan, do you remember doing that thing in post I mean pre I mean post regionals where we

**KG:** that?

**Elliot Newman:** like crazily um decrease the time of run eight um by

**Guhan Karthicraja:** Yeah. Yeah. Yeah. Yeah.

**Elliot Newman:** adding by adding like a bunch of multitasks and

**Guhan Karthicraja:** Um so Oh yeah. So we did that but also uh during that same period um

**Elliot Newman:** That's

**Guhan Karthicraja:** what we did was we like drastically increased the speed. Um and that was not just the speed of the flag drop and that wasn't because of it just not it's for saving time purposes. What we found was when you dropped it quicker, uh, it would go slightly further.

**Elliot Newman:** Uh

**Guhan Karthicraja:** And when it dropped slightly short because, uh, we have, um, the prongs, they aren't too long, but they're like they they do like drop the

**Elliot Newman:** the back

**Guhan Karthicraja:** flag properly.

  
  

### 01:05:59

  

**Guhan Karthicraja:** But if you drop it fast, it will go better properly into the circle, I mean the square or the area. Um uh than if you did it slowly because if when you we did it slowly we found that it half the time it would drop

**KG:** Yeah.

**Guhan Karthicraja:** short

**KG:** See that that's another important physics where you have a parabolic path when it slides from you know certain height into a path it maintains that momentum. So if it slides faster then you reach further. if it slide uh you know slower the if the release point was slower then it it doesn't travel too far. So that is one of the thing but I think there was another challenge if you needed to get the speed exactly right because if it dropped too close to the attachment even if it is perfect I think when you lifted up that prong it just threw it again threw it away again or lifted it back as well in some cases. So um you needed that uh correct calculations for it.

**Elliot Newman:** Okay.

**KG:** All right. I

  
  

### 01:07:05

  

**Elliot Newman:** Uh, thank you

**Adjoa Appiah:** Hi Cartik,

**KG:** think

**Adjoa Appiah:** can I just ask um with this piece of work, is it going to be presented in a file to the judges or is

**KG:** yeah I think it will be

**Adjoa Appiah:** it slides? What is it for?

**KG:** twofold. So what we have here will go into the files. So they have a you know a clear explanation of everything that they have and also there will be a there will be one um slide in the poster uh which might summarize all the different because iteration is something that they have to talk about. So they may have a slide but they may pick um maybe run two three and uh seven seven isn't it? Now six which were the the old blocks which has a parabolic so they can talk about that as an example. So firstly we did this and we you know we came up with this parabolic idea and run three went through so many iterations. So they may pick up one or two and then talk about it with one anchor slide but all these details will go into the uh the files.

**Adjoa Appiah:** Okay, thank

**KG:** I think the important thing is you know now everyone has hear the same thing. So they would be able to recall u this or pass the same message if at all a question was asked you know maybe they they asked somebody very specifically um who were talks um through that slide if they asked that question to that person who is speaking about iteration is it flossy you are talking about iterations

**Florence Ingram:** Uh potentially I would have to have the script for me to

**KG:** so yeah if they pointed you and asked that question then you have all the answers Now so you know whatever we have documented please do go through all of you so you're all on the same page all right that's very good

**Guhan Karthicraja:** You are not catching me. I I wasn't talking.

**KG:** that's all children I think we are 10 minutes uh overrun but uh this is brilliant very good work all of

**Guhan Karthicraja:** Um,

**KG:** Okay,

**Elliot Newman:** Thank you.

**KG:** bye.

**Elliot Newman:** Bye.

**Aaliya Mohamed:** Thank you. Bye.

  
  

### Transcription ended after 01:09:35

  

*This editable transcript was computer generated and might contain errors. People can also change the text after it was cre