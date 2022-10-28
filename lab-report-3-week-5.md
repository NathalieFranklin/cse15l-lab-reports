# Lab Report 3
## 1. grep :
### grep -m

With -m flag we must also pass in the number of lines to be printed within a file that match with the passed in search word for grep. Keep in mind line read and thus printed on the terminal must contain the key word. As you can see I only chose one line that means the lines your seeing are the first lines in those text files to have the word "the". This helps decluter your command line when you just want the first occurance.
```
[cs15lfa22es@ieng6-201]:technical:180$ grep -m 1 "the"  911report/*.txt
911report/chapter-1.txt:    Tuesday, September 11, 2001, dawned temperate and nearly cloudless in the eastern United States. Millions 
of men and women readied themselves for work. Some made their way to the Twin Towers, the signature structures of the World Trade Center complex in New York City. Others went to Arlington, Virginia, to the Pentagon. Across the Potomac River, the United States Congress was back in session. At the other end of Pennsylvania Avenue, people began to line up for a White House tour. In Sarasota, Florida, President George W. Bush went for an early morning run.
911report/chapter-10.txt:            After the attacks had occurred, while crisis managers were still sorting out a number
911report/chapter-11.txt:            In composing this narrative, we have tried to remember that we write with the benefit
911report/chapter-12.txt:                become, beyond any doubt, the top national security priority for the United States.
911report/chapter-13.1.txt:            As presently configured, the national security institutions of the U.S. government
911report/chapter-13.2.txt:            For simplicity, we have adopted the following citation conventions in these endnotes.
911report/chapter-13.3.txt:            3. Usama Bin Ladin, "Declaration of War Against the Americans Occupying the Land of
911report/chapter-13.4.txt:            1. Though KSM and Bin Ladin knew each other from the anti-Soviet campaign of the
911report/chapter-13.5.txt:            1. Muhammad Mani Ahmad al Kahtani. Currently in custody, he is the last known Saudi
911report/chapter-2.txt:            In February 1998, the 40-year-old Saudi exile Usama Bin Ladin and a fugitive Egyptian
911report/chapter-3.txt:            In chapter 2, we described the growth of a new kind of terrorism, and a new terrorist
911report/chapter-5.txt:            By early 1999, al Qaeda was already a potent adversary of the United States. Bin
911report/chapter-6.txt:            In chapters 3 and 4 we described how the U.S. government adjusted its existing
911report/chapter-7.txt:            In chapter 5 we described the Southeast Asia travels of Nawaf al Hazmi, Khalid al
911report/chapter-8.txt:                reports about threats. Indeed, there appeared to be possible threats almost
911report/chapter-9.txt:            Emergency response is a product of preparedness. On the morning of September 11,
911report/preface.txt:            We present the narrative of this report and the recommendations that flow from it to
```


---

### grep -v

In the case of -v flag for grep it takes the key word you want to search for and returns to you every line that doesn't contain the aformantiened key word. Don't believe I want you to scan the text below from chapter 10 and try to find any lower case "the". This help when you know what you don't want and thus can ignore it from the text.
```
cs15lfa22es@ieng6-201]:technical:183$ grep -v "the"  911report/chapter-10.txt



            WARTIME
                of unnerving false alarms, Air Force One flew to Barksdale Air Force Base in
                White House Situation Room that morning.

                advisers, and Vice President Cheney were strongly advising against it. President
                Bush reluctantly acceded to this advice and, at about 10:10, Air Force One changed
                course and began heading due west. The immediate objective was to find a safe
                Barksdale Air Force Base as an appropriate interim destination.

                situation with superiors in Washington. The President completed his statement, which
                Offutt Air Force Base in Nebraska was chosen because of its elaborate command and
                control facilities, and because it could accommodate overnight lodging for 50
                days, if necessary.

            Air Force One arrived at Offutt at 2:50 P.M. At about 3:15, President Bush met with
                his principal advisers through a secure video teleconference.


                an increased state of military readiness.

                narrowly escaped direct attack. Extraordinary security precautions were put in place
                have him return to Washington and ordered Air Force One back to Andrews Air Force
                . ." No American, he said,"will ever forget this day."

            Following his speech, President Bush met again with his National Security Council
                (NSC), expanded to include Secretary of Transportation Norman Mineta and Joseph

            IMMEDIATE RESPONSES AT HOME
                Bolten chaired a temporary "domestic consequences" group.

            The agenda in those first days is worth noting, partly as a checklist for future

                Organizing federal emergency assistance. One question was what kind of public

                Compensating victims. They evaluated legislative options, eventually setting
                    run it.
                Determining federal assistance. On September 13, President Bush promised to

                    airspace reopened for use by airports that met newly improvised security
                    standards.
                    September 17.

                Deciding when and how to return border and port security to more normal
                    operations.
                    liability.

                government organization dedicated to assessing vulnerabilities and handling problems
                task, none had security as its primary mission. By September 14, Vice President
                Cheney had decided to recommend, at least as a first step, a new White House entity
                Pennsylvania governor Tom Ridge-in his address to a joint session of Congress on
                September 20.

            Beginning on September 11, Immigration and Naturalization Service agents working in
                attacks. Eventually, 768 aliens were arrested as "special interest" detainees. Some
                (such as Zacarias Moussaoui) were actually in INS custody before 9/11; most were
                arrested after. Attorney General John Ashcroft told us that he saw his job in
                attacks and to prevent a subsequent attack. Ashcroft ordered all special interest
                80 days.

            We have assessed this effort to detain aliens of "special interest." The detainees
                were lawfully held on immigration charges. Records indicate that 531 were deported,
                162 were released on bond, 24 received some kind of immigration benefits, 12 had
                    treated.

                detainee list, noting that two (including Moussaoui) were linked directly to a

                files and deportation of nonpermanent residents, forced al Qaeda to operate less

                communities, was not a priority before 9/11. Guidelines on this subject issued in
                August 2001 by Deputy Attorney General LarryThompson essentially recapitulated prior

                chapter 3). Ashcroft told us he was determined to take every conceivable action,
                additional attacks.

            The administration developed a proposal that eventually passed both houses of
                Congress by large majorities and was signed into law on October 26.

                nationals take place before national airspace reopened on September 13, 2001? (2)
            First, we found no evidence that any flights of Saudi nationals, domestic or
                after national airspace reopened.

            Second, we found no evidence of political intervention. We found no evidence that
                it would be fine with me." Clarke added,"I have no recollection of clearing it with

            Although White House Chief of Staff Andrew Card remembered someone telling him about
                did not ask anyone to do anything about it. The President and Vice President told us
                matter from any political appointee.



                attacks and have since found no evidence to change that conclusion. Our own

            PLANNING FOR WAR
                domestic department heads broke up, President Bush chaired a smaller meeting of top
                advisers, a group he would later call his "war council."33This group usually
                included Vice President Cheney, Secretary of State Powell, Secretary of Defense
                become chairman) General Myers, DCI Tenet, Attorney General Ashcroft, and FBI
                time to act was now. He said we would need to build a coalition. The President noted
                    assemble.


                United States would need to integrate diplomacy, financial measures, intelligence,
                and military actions into an overarching strategy. The principals also focused on
                    risk.

                wanted Pakistan to take seven steps:

                to stop al Qaeda operatives at its border and end all logistical support for
                    Bin Ladin;
                    necessary military and intelligence operations;
                to provide territorial access to U.S. and allied military intelligence and
                    to Afghanistan; and,


            Pakistan made its decision swiftly. That afternoon, Secretary of State Powell
                U.S. embassy in Islamabad confirmed that Musharraf and his top military commanders
                had agreed to all seven demands." Pakistan will need full US support as it proceeds
                making substantial concessions in allowing use of its territory and that he would
                pay a domestic price. His standing in Pakistan was certain to suffer. To
                counterbalance that he needed to show that Pakistan was benefiting from his
                    decisions."


                Pakistan and Afghanistan." The paper took it as a given that Bin Ladin would
                Taliban knew about al Qaeda and its operations; close all terrorist camps; free all
                imprisoned foreigners; and comply with all UN Security Council resolutions.

                Defense would plan to build an international coalition to go into Afghanistan. Both
                terrorists, work with a coalition to eliminate terrorist groups and networks, and
                avoid malice toward any people, religion, or culture.
            
                to invade Afghanistan with ground troops.

                Afghanistan. The existing Infinite Resolve options did not, in his view, amount to
                such a plan.

                15-16, as President Bush convened his war council at Camp David.

            Present were Vice President Cheney, Rice, Hadley, Powell, Armitage, Rumsfeld,
                Ashcroft, Mueller, Tenet, Deputy Secretary of Defense Paul Wolfowitz, and Cofer
            Tenet described a plan for collecting intelligence and mounting covert operations. He
                proposed inserting CIA teams into Afghanistan to work with Afghan warlords who would
                military's Special Operations units. President Bush later praised this proposal,
                saying it had been a turning point in his thinking.

                possible significant use of ground forces- and that is where President Bush
                reportedly focused his attention.

                morning, September 17. "The purpose of this meeting," he recalled saying,"is to

                President Bush charged Ashcroft, Mueller, and Tenet to develop a plan for homeland
                defense. President Bush directed Secretary of State Powell to deliver an ultimatum
                State Department was also tasked to develop a plan to stabilize Pakistan and to be
                prepared to notify Russia and countries near Afghanistan when hostilities were
                    imminent.

            In addition, Bush and his advisers discussed new legal authorities for covert action

                ultimatum. The President also tasked Rumsfeld to ensure that robust measures to
                protect American military forces against terrorist attack were implemented
                worldwide. Finally, he directed Treasury Secretary Paul O'Neill to craft a plan to
                target al Qaeda's funding and seize its assets.

            NSC staff members had begun leading meetings on terrorist fund-raising by September
                    18.

            Also by September 18, Powell had contacted 58 of his foreign counterparts and
                received offers of general aid, search-and-rescue equipment and personnel, and
                medical assistance teams.


            The pre-9/11 draft presidential directive on al Qaeda evolved into a new directive,
                determination to use military force if necessary to end al Qaeda's sanctuary in
                Afghanistan had already begun-included new material followed by annexes discussing
                each targeted terrorist group. The old draft directive on al Qaeda became, in


            "PHASE TWO" AND THE QUESTION OF IRAQ

                some of his staff to explore possible Iraqi links to 9/11. "See if Saddam did this,"
                incorrect, President Bush acknowledged that he might well have spoken to Clarke at
                some point, asking him about Iraq.

            Responding to a presidential tasking, Clarke's office sent a memo to Rice on
                September 18, titled "Survey of Intelligence Information on Any Iraq Involvement in
                concurred in its conclusion that only some anecdotal evidence linked Iraq to al
                Iraqi intelligence officer (discussed in chapter 7) and a Polish report that
                unconventional weapons.

                instructed General Myers to obtain quickly as much information as possible. The
                notes indicate that he also told Myers that he was not simply interested in striking
                options and possibilities. The secretary said his instinct was to hit Saddam Hussein
                responsible party.


                was cited, along with its interest in weapons of mass destruction.

            Secretary Powell recalled that Wolfowitz-not Rumsfeld-argued that Iraq was ultimately

            Powell said that Wolfowitz was not able to justify his belief that Iraq was behind
                with," Powell told us." And he saw this as one way of using this event as a way to
                Wolfowitz's argument "much weight." Though continuing to

                15 afternoon session, which dealt solely with Afghanistan.



                Baghdad acted against U.S. interests, with plans to include possibly occupying Iraqi
                oil fields.

                dealing with Iraq. Writing to Rumsfeld on September 17 in a memo headlined
                1995 Manila air plot in crashing an explosives-laden plane into CIA headquarters,
                attempted hijacking of a Gulf Air flight. Given this background, he wondered why so
                of imagination" and a mind-set that dismissed possibilities.

                Qaeda, and Afghanistan.

                leader should do.

                and al Qaeda in Afghanistan. But, he told us, he now wondered how that action was
                connected to what might need to be done in Somalia, Yemen, or Iraq.


            Franks told us that he was pushing independently to do more robust planning on
                for a full invasion of Iraq during this period, Franks said.) The CENTCOM commander
                moves shortly after 9/11, both because he personally felt that Iraq and al Qaeda
                might be engaged in some form of collusion and because he worried that Saddam might
                    request.

            Having issued directives to guide his administration's preparations for war, on
                that had already been conveyed privately." The Taliban must act, and act
                was not with Islam: "The enemy of America is not our many Muslim friends; it is not
                our many Arab friends. Our enemy is a radical network of terrorists, and every

                every terrorist group of global reach has been found, stopped, and defeated." The
                States." This is civilization's fight," he said. "We ask every nation to join
                    us."

            President Bush approved military plans to attack Afghanistan in meetings with Central
                    Freedom."

            The plan had four phases.

                    region and arrange to operate from or over neighboring countries such as
                In Phase Two, air strikes and Special Operations attacks would hit key al
                    Qaeda and Taliban targets. In an innovative joint effort, CIA and Special
                    7. The basing arrangements contemplated for Phase One were substantially
                    regime and eliminate al Qaeda's sanctuary in Afghanistan. Mazar-e-Sharif, in
                    Taliban.

            In December 2001, Afghan forces, with limited U.S. support, engaged al Qaeda elements
                force of al Qaeda jihadists. The three-week battle was substantially successful, and
                almost all remaining al Qaeda forces took refuge in Pakistan's equally mountainous
                and lightly governed frontier provinces. As of July 2004, Bin Ladin and Zawahiri are
                still believed to be at large.


                aircraft and a much larger infrastructure of intelligence and support efforts, had
                provided intelligence, experience, cash, covert action capabilities, and entr�e to
                logistics, and communications.

                Islamist terrorism became a different kind of struggle.
                
```
                
### grep -i
The -i flag for grep will help metigate the capital The capital "The" we encounter when we tried to skip all the lines with "the" in ourprevious command. Don't believe try to find a "the" in the output below. That is because -i will ignore the case. This helps when you don't want to type out every case version for every thing you want to search. 
```
 WARTIME
                of unnerving false alarms, Air Force One flew to Barksdale Air Force Base in
                White House Situation Room that morning.

                advisers, and Vice President Cheney were strongly advising against it. President
                Bush reluctantly acceded to this advice and, at about 10:10, Air Force One changed
                Barksdale Air Force Base as an appropriate interim destination.

                Offutt Air Force Base in Nebraska was chosen because of its elaborate command and
                control facilities, and because it could accommodate overnight lodging for 50
                days, if necessary.

            Air Force One arrived at Offutt at 2:50 P.M. At about 3:15, President Bush met with
                his principal advisers through a secure video teleconference.


                an increased state of military readiness.

                narrowly escaped direct attack. Extraordinary security precautions were put in place
                have him return to Washington and ordered Air Force One back to Andrews Air Force
                . ." No American, he said,"will ever forget this day."

            Following his speech, President Bush met again with his National Security Council
                (NSC), expanded to include Secretary of Transportation Norman Mineta and Joseph

            IMMEDIATE RESPONSES AT HOME
                Bolten chaired a temporary "domestic consequences" group.


                Organizing federal emergency assistance. One question was what kind of public

                    run it.
                Determining federal assistance. On September 13, President Bush promised to

                    airspace reopened for use by airports that met newly improvised security
                    standards.
                    September 17.

                Deciding when and how to return border and port security to more normal
                    operations.
                    liability.

                government organization dedicated to assessing vulnerabilities and handling problems
                task, none had security as its primary mission. By September 14, Vice President
                Cheney had decided to recommend, at least as a first step, a new White House entity
                Pennsylvania governor Tom Ridge-in his address to a joint session of Congress on
                September 20.

            Beginning on September 11, Immigration and Naturalization Service agents working in
                attacks. Eventually, 768 aliens were arrested as "special interest" detainees. Some
                (such as Zacarias Moussaoui) were actually in INS custody before 9/11; most were
                arrested after. Attorney General John Ashcroft told us that he saw his job in
                attacks and to prevent a subsequent attack. Ashcroft ordered all special interest
                80 days.

                were lawfully held on immigration charges. Records indicate that 531 were deported,
                162 were released on bond, 24 received some kind of immigration benefits, 12 had
                    treated.

                detainee list, noting that two (including Moussaoui) were linked directly to a

                files and deportation of nonpermanent residents, forced al Qaeda to operate less

                communities, was not a priority before 9/11. Guidelines on this subject issued in
                August 2001 by Deputy Attorney General LarryThompson essentially recapitulated prior

                chapter 3). Ashcroft told us he was determined to take every conceivable action,
                additional attacks.

                Congress by large majorities and was signed into law on October 26.

                nationals take place before national airspace reopened on September 13, 2001? (2)
            First, we found no evidence that any flights of Saudi nationals, domestic or
                after national airspace reopened.

            Second, we found no evidence of political intervention. We found no evidence that
                it would be fine with me." Clarke added,"I have no recollection of clearing it with

            Although White House Chief of Staff Andrew Card remembered someone telling him about
                matter from any political appointee.



                attacks and have since found no evidence to change that conclusion. Our own

            PLANNING FOR WAR
                domestic department heads broke up, President Bush chaired a smaller meeting of top
                advisers, a group he would later call his "war council."33This group usually
                included Vice President Cheney, Secretary of State Powell, Secretary of Defense
                become chairman) General Myers, DCI Tenet, Attorney General Ashcroft, and FBI
                    assemble.


                United States would need to integrate diplomacy, financial measures, intelligence,
                    risk.

                wanted Pakistan to take seven steps:

                to stop al Qaeda operatives at its border and end all logistical support for
                    Bin Ladin;
                    necessary military and intelligence operations;
                to provide territorial access to U.S. and allied military intelligence and
                    to Afghanistan; and,


            Pakistan made its decision swiftly. That afternoon, Secretary of State Powell
                U.S. embassy in Islamabad confirmed that Musharraf and his top military commanders
                had agreed to all seven demands." Pakistan will need full US support as it proceeds
                making substantial concessions in allowing use of its territory and that he would
                pay a domestic price. His standing in Pakistan was certain to suffer. To
                counterbalance that he needed to show that Pakistan was benefiting from his
                    decisions."


                Taliban knew about al Qaeda and its operations; close all terrorist camps; free all
                imprisoned foreigners; and comply with all UN Security Council resolutions.

                Defense would plan to build an international coalition to go into Afghanistan. Both
                terrorists, work with a coalition to eliminate terrorist groups and networks, and
                avoid malice toward any people, religion, or culture.

                to invade Afghanistan with ground troops.

                such a plan.

                15-16, as President Bush convened his war council at Camp David.

            Present were Vice President Cheney, Rice, Hadley, Powell, Armitage, Rumsfeld,
                Ashcroft, Mueller, Tenet, Deputy Secretary of Defense Paul Wolfowitz, and Cofer
            Tenet described a plan for collecting intelligence and mounting covert operations. He
                proposed inserting CIA teams into Afghanistan to work with Afghan warlords who would
                military's Special Operations units. President Bush later praised this proposal,
                saying it had been a turning point in his thinking.

                possible significant use of ground forces- and that is where President Bush
                reportedly focused his attention.


                President Bush charged Ashcroft, Mueller, and Tenet to develop a plan for homeland
                defense. President Bush directed Secretary of State Powell to deliver an ultimatum
                State Department was also tasked to develop a plan to stabilize Pakistan and to be
                prepared to notify Russia and countries near Afghanistan when hostilities were
                    imminent.

            In addition, Bush and his advisers discussed new legal authorities for covert action

                protect American military forces against terrorist attack were implemented
                worldwide. Finally, he directed Treasury Secretary Paul O'Neill to craft a plan to
                target al Qaeda's funding and seize its assets.

            NSC staff members had begun leading meetings on terrorist fund-raising by September
                    18.

            Also by September 18, Powell had contacted 58 of his foreign counterparts and
                received offers of general aid, search-and-rescue equipment and personnel, and
                medical assistance teams.


                determination to use military force if necessary to end al Qaeda's sanctuary in
                Afghanistan had already begun-included new material followed by annexes discussing



                some of his staff to explore possible Iraqi links to 9/11. "See if Saddam did this,"
                incorrect, President Bush acknowledged that he might well have spoken to Clarke at
                some point, asking him about Iraq.

            Responding to a presidential tasking, Clarke's office sent a memo to Rice on
                September 18, titled "Survey of Intelligence Information on Any Iraq Involvement in
                concurred in its conclusion that only some anecdotal evidence linked Iraq to al
                Iraqi intelligence officer (discussed in chapter 7) and a Polish report that
                unconventional weapons.

                notes indicate that he also told Myers that he was not simply interested in striking
                responsible party.


                was cited, along with its interest in weapons of mass destruction.

            Secretary Powell recalled that Wolfowitz-not Rumsfeld-argued that Iraq was ultimately

            Powell said that Wolfowitz was not able to justify his belief that Iraq was behind
                with," Powell told us." And he saw this as one way of using this event as a way to
                Wolfowitz's argument "much weight." Though continuing to

                15 afternoon session, which dealt solely with Afghanistan.



                Baghdad acted against U.S. interests, with plans to include possibly occupying Iraqi
                oil fields.

                dealing with Iraq. Writing to Rumsfeld on September 17 in a memo headlined
                1995 Manila air plot in crashing an explosives-laden plane into CIA headquarters,
                attempted hijacking of a Gulf Air flight. Given this background, he wondered why so
                of imagination" and a mind-set that dismissed possibilities.

                Qaeda, and Afghanistan.

                leader should do.

                and al Qaeda in Afghanistan. But, he told us, he now wondered how that action was
                connected to what might need to be done in Somalia, Yemen, or Iraq.


            Franks told us that he was pushing independently to do more robust planning on
                moves shortly after 9/11, both because he personally felt that Iraq and al Qaeda
                might be engaged in some form of collusion and because he worried that Saddam might
                    request.

            Having issued directives to guide his administration's preparations for war, on
                our many Arab friends. Our enemy is a radical network of terrorists, and every

                States." This is civilization's fight," he said. "We ask every nation to join
                    us."

            President Bush approved military plans to attack Afghanistan in meetings with Central
                    Freedom."


                    region and arrange to operate from or over neighboring countries such as
                In Phase Two, air strikes and Special Operations attacks would hit key al
                    Qaeda and Taliban targets. In an innovative joint effort, CIA and Special
                    regime and eliminate al Qaeda's sanctuary in Afghanistan. Mazar-e-Sharif, in
                    Taliban.

            In December 2001, Afghan forces, with limited U.S. support, engaged al Qaeda elements
                almost all remaining al Qaeda forces took refuge in Pakistan's equally mountainous
                and lightly governed frontier provinces. As of July 2004, Bin Ladin and Zawahiri are
                still believed to be at large.


                aircraft and a much larger infrastructure of intelligence and support efforts, had
                provided intelligence, experience, cash, covert action capabilities, and entr�e to
                logistics, and communications.

                Islamist terrorism became a different kind of struggle.
               
```
---
---

## less

# less -n
 Unlike before -n flag in less removes the numbers that track the lines. Though this might seem counterintuitive at first, it helps declutter the terminal and help people who find the numbers distracting.
``` 
less -n 911report/chapter-10.txt
   WARTIME
            After the attacks had occurred, while crisis managers were still sorting out a number
                of unnerving false alarms, Air Force One flew to Barksdale Air Force Base in
                Louisiana. One of these alarms was of a reported threat against Air Force One
                itself, a threat eventually run down to a misunderstood communication in the hectic
                White House Situation Room that morning.

            While the plan at the elementary school had been to return to Washington, by the time
                Air Force One was airborne at 9:55 A.M. the Secret Service, the President's
                advisers, and Vice President Cheney were strongly advising against it. President
                Bush reluctantly acceded to this advice and, at about 10:10, Air Force One changed
                course and began heading due west. The immediate objective was to find a safe
                location-not too far away-where the President could land and speak to the American
                people. The Secret Service was also interested in refueling the aircraft and paring
                down the size of the traveling party. The President's military aide, an Air Force
                officer, quickly researched the options and, sometime around 10:20, identified
                Barksdale Air Force Base as an appropriate interim destination.

            When Air Force One landed at Barksdale at about 11:45, personnel from the local
                Secret Service office were still en route to the airfield. The motorcade consisted
                of a military police lead vehicle and a van; the proposed briefing theater had no
                phones or electrical outlets. Staff scrambled to prepare another room for the
                President's remarks, while the lead Secret Service agent reviewed the security
                situation with superiors in Washington. The President completed his statement, which
                for security reasons was taped and not broadcast live, and the traveling party
                returned to Air Force One. The next destination was discussed: once again the Secret
                Service recommended against returning to Washington, and the Vice President agreed.
                Offutt Air Force Base in Nebraska was chosen because of its elaborate command and
                control facilities, and because it could accommodate overnight lodging for 50
                persons. The Secret Service wanted a place where the President could spend several
                days, if necessary.

            Air Force One arrived at Offutt at 2:50 P.M. At about 3:15, President Bush met with
                his principal advisers through a secure video teleconference.

            Rice said President Bush began the meeting with the words, "We're at war," and that Director of Central Intelligence George Tenet said
                the agency was still assessing who was responsible, but the early signs all pointed
                to al Qaeda.6That evening the Deputies Committee returned to the pending
                presidential directive they had labored over during the summer.

            The secretary of defense directed the nation's armed forces to Defense Condition 3,
                an increased state of military readiness.

            For the first time in history, all nonemergency civilian aircraft in the United
                States were grounded, stranding tens of thousands of passengers across the country.
                Contingency plans for the continuity of government and the evacuation of leaders had
                been implemented. 9 The Pentagon had been struck; the White House or the Capitol had
                narrowly escaped direct attack. Extraordinary security precautions were put in place
                at the nation's borders and ports.
            In the late afternoon, the President overruled his aides' continuing reluctance to
            
            
```
---

# less - p 
The falg -p when fallowed with a search word will start at the line that has the first instance of that word in the text file. This is very helpful when you are intrsted in a certain section or definition because it prevenets time waisting through searchig what you really want. As you can see below the first line contains the word plane which is my search word.

```
less -p plane  911report/chapter-10.txt
 1995 Manila air plot in crashing an explosives-laden plane into CIA headquarters,
                and about information from a foreign government regarding Iraqis' involvement in the
                attempted hijacking of a Gulf Air flight. Given this background, he wondered why so
                little thought had been devoted to the danger of suicide pilots, seeing a "failure
                of imagination" and a mind-set that dismissed possibilities.

            On September 19, Rumsfeld offered several thoughts for his commanders as they worked
                on their contingency plans. Though he emphasized the worldwide nature of the
                conflict, the references to specific enemies or regions named only the Taliban, al
                Qaeda, and Afghanistan.

            Shelton told us the administration reviewed all the Pentagon's war plans and
                challenged certain assumptions underlying them, as any prudent organization or
                leader should do.

            General Tommy Franks, the commanding general of Central Command, recalled receiving
                Rumsfeld's guidance that each regional commander should assess what these plans
                meant for his area of responsibility. He knew he would soon be striking the Taliban
                and al Qaeda in Afghanistan. But, he told us, he now wondered how that action was
                connected to what might need to be done in Somalia, Yemen, or Iraq.

            On September 20, President Bush met with British Prime Minister Tony Blair, and the
                two leaders discussed the global conflict ahead. When Blair asked about Iraq, the
                President replied that Iraq was not the immediate problem. Some members of his
                administration, he commented, had expressed a different view, but he was the one
                responsible for making the decisions.

            Franks told us that he was pushing independently to do more robust planning on
                military responses in Iraq during the summer before 9/11-a request President Bush
                denied, arguing that the time was not right. (CENTCOM also began dusting off plans
                for a full invasion of Iraq during this period, Franks said.) The CENTCOM commander
                told us he renewed his appeal for further military planning to respond to Iraqi
                moves shortly after 9/11, both because he personally felt that Iraq and al Qaeda
                might be engaged in some form of collusion and because he worried that Saddam might
                take advantage of the attacks to move against his internal enemies in the northern
                or southern parts of Iraq, where the United States was flying regular missions to
                enforce Iraqi no-fly zones. Franks said that President Bush again turned down the
                    request.

            Having issued directives to guide his administration's preparations for war, on
                Thursday, September 20, President Bush addressed the nation before a joint session
                of Congress." Tonight," he said, "we are a country awakened to danger." The President blamed al Qaeda for 9/11 and the 1998
                embassy bombings and, for the first time, declared that al Qaeda was "responsible
                for bombing the USS Cole." He reiterated the ultimatum
                that had already been conveyed privately." The Taliban must act, and act
                immediately," he said." They will hand over the terrorists, or they will share in
                their fate." The President added that America's quarrel
                was not with Islam: "The enemy of America is not our many Muslim friends; it is not
                our many Arab friends. Our enemy is a radical network of terrorists, and every
                government that supports them." Other regimes faced hard choices, he pointed out:
                "Every nation, in every region, now has a decision to make: Either you are with us,
                or you are with the terrorists."
```
---
# less -m 
The -m flag for less will display at the bottom left of the terminal how far along you are in the text by a percentage sign out of a 100%. This is very useful to keep track of how much reading is left so you can budget your time or prepare your self for a heavy text. While line numbers can help bookmark you don't know what line it is out of what until you scroll to the last line. 
```
 less -m 911report/chapter-10.txt
     WARTIME
            After the attacks had occurred, while crisis managers were still sorting out a number
                of unnerving false alarms, Air Force One flew to Barksdale Air Force Base in
                Louisiana. One of these alarms was of a reported threat against Air Force One
                itself, a threat eventually run down to a misunderstood communication in the hectic
                White House Situation Room that morning.

            While the plan at the elementary school had been to return to Washington, by the time
                Air Force One was airborne at 9:55 A.M. the Secret Service, the President's
                advisers, and Vice President Cheney were strongly advising against it. President
                Bush reluctantly acceded to this advice and, at about 10:10, Air Force One changed
                course and began heading due west. The immediate objective was to find a safe
                location-not too far away-where the President could land and speak to the American
                people. The Secret Service was also interested in refueling the aircraft and paring
                down the size of the traveling party. The President's military aide, an Air Force
                officer, quickly researched the options and, sometime around 10:20, identified
                Barksdale Air Force Base as an appropriate interim destination.

            When Air Force One landed at Barksdale at about 11:45, personnel from the local
                Secret Service office were still en route to the airfield. The motorcade consisted
                of a military police lead vehicle and a van; the proposed briefing theater had no
                phones or electrical outlets. Staff scrambled to prepare another room for the
                President's remarks, while the lead Secret Service agent reviewed the security
                situation with superiors in Washington. The President completed his statement, which
                for security reasons was taped and not broadcast live, and the traveling party
                returned to Air Force One. The next destination was discussed: once again the Secret
                Service recommended against returning to Washington, and the Vice President agreed.
                Offutt Air Force Base in Nebraska was chosen because of its elaborate command and
                control facilities, and because it could accommodate overnight lodging for 50
                persons. The Secret Service wanted a place where the President could spend several
                days, if necessary.
6%
```

---
---

## find
# find -maxdepth 
The -maxdepth flag is fallowed by a number telling the find command how deep to look for it's output paths. Sometimes to find is a couple of layers deep in a hundreds of layer of directories. Inorder not to be overwhelmed by child directories this can be quite useful to narrow doen the results.
```
find 911report -maxdepth 0
911report
```
---

# find path_type -f
The path_type return paths only to either files when fallowed by -f or directories when fallowed by -d. This is usefull when you know that youre looking for files so paths ending in directories just cluter the command line.
```
technical:218$  find 911report -type f
911report/chapter-1.txt
911report/chapter-10.txt
911report/chapter-11.txt
911report/chapter-12.txt
911report/chapter-13.1.txt
911report/chapter-13.2.txt
911report/chapter-13.3.txt
911report/chapter-13.4.txt
911report/chapter-13.5.txt
911report/chapter-2.txt
911report/chapter-3.txt
911report/chapter-5.txt
911report/chapter-6.txt
911report/chapter-7.txt
911report/chapter-8.txt
911report/chapter-9.txt
911report/preface.txt
```
---

# find -mtime
The -mtime helps us narrow down the files outputed due to the time they were last updated -mtime -2 ( less then 2 days ago) -mtime +2 (more then 2 days ago) -mtime 2(exactly 2 days ago). When we might have an ideo of when the document we searched for was made or used we can use this flag to help narrow down our search.
```
find  911report -mtime -2
911report
911report/chapter-1.txt
911report/chapter-10.txt
911report/chapter-11.txt
911report/chapter-12.txt
911report/chapter-13.1.txt
911report/chapter-13.2.txt
911report/chapter-13.3.txt
911report/chapter-13.4.txt
911report/chapter-13.5.txt
911report/chapter-2.txt
911report/chapter-3.txt
911report/chapter-5.txt
911report/chapter-6.txt
911report/chapter-7.txt
911report/chapter-8.txt
911report/chapter-9.txt
911report/preface.txt
```
