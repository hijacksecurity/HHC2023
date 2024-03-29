# Welcome

![Group photo](./img/misc/title_image.jpg)

## Introduction

Hello and welcome to my [2023 SANS Holiday Hack Challenge](https://2023.holidayhackchallenge.com/) write-up! My name is HijackSecurity and it's my 2nd year completing HHC all the way through (last one was back
in 2018). My main motivation for participating this year was to encourage friends to play the game, as well as challenge myself, and
hopefully write an interesting report to help others learn some new skills or just nudge if you are following along. Huge thanks to the SANS team for creating top-notch CTF, you guys rock! 🤘🙂 <br/>

This year's HHC was awesome - fun, challenging and highly rewarding! The challenges had it all - AI, healthy amount of Azure APIs, SQL injections, 
lots of client-side code manipulation (JS breakpoints - what are those), some GameBoy hacking, lock-picking went back to high-school days, JWT's are taking over, practical Java Deserialization exploitation, 
casual quick & dirty Python scripting, satellite hacking and the need to think outside the box like every hacking challenge demands. 🔒😎<br/>

The write-up is broken down into multiple sections, each containing similarly-themed [objectives](./objectives/o1.md). Within each objective, there are its request, any relevant hints gathered,
my solution, and the final response from whoever given the challenge. To walk through objectives step-by-step, use the "Navigation tip" below. There are also final answers here, 
the full Holiday Hack story, and a family photo that's photogenic enough for a post card. Besides all this, there is a [BONUS!](./bonus.md) section for a couple of challenges outside of the 
main story. Enjoy! 🎅🎄


!!! note "100-page submission limit"
    Each year there's a huge number of write-ups that need to be reviewed by the Counter Hack team. To find a good middle ground between preventing information overload and creating a write-up that can stand on its own as a learning resource, some parts, like the *navigation tip* below, are collapsed by default. Skipping over these will not take away from understanding the overall solution, but feel free to expand them to get some additional information.

??? tip "Navigation tip"
    Even with less than 100 pages, there's still quite a bit of information to read through. To make things a little easier, you can use ++"P"++ or ++","++ to go to the previous section, ++"N"++ or ++"."++ to navigate to the next section, and ++"S"++, ++"F"++, or ++"/"++ to open up the search dialog.

    **TL;DR** if you keep pressing ++"N"++ or ++"."++ from this point forward, you'll hit all the content in the right order! :smile:

## Answers

!!! success "1. Holiday Hack Orientation - :fontawesome-solid-star::fontawesome-regular-star::fontawesome-regular-star::fontawesome-regular-star::fontawesome-regular-star:"
    Follow [Jingle Ringford's instructions](./objectives/o1.md) to get your bearings at Geese Islands.

!!! success "2. Snowball Fight - :fontawesome-solid-star::fontawesome-solid-star::fontawesome-regular-star::fontawesome-regular-star::fontawesome-regular-star:"
    Beat elves and Santa at [Snowball Fight](./objectives/o2.md) by tinkering with client-side variables and parameters.

!!! success "3. Linux 101 - :fontawesome-solid-star::fontawesome-regular-star::fontawesome-regular-star::fontawesome-regular-star::fontawesome-regular-star:"
    A super cool way to play around with computers is by getting to know [Linux command-fu](./objectives/o3.md).

!!! success "4. Reportinator - :fontawesome-solid-star::fontawesome-solid-star::fontawesome-regular-star::fontawesome-regular-star::fontawesome-regular-star:"
    Improve the quality of the ChatNPT-generated [penetration testing report](./objectives/o4.md) via the absolute hacker way or by reading with a keen eye.

!!! success "5. Azure 101 - :fontawesome-solid-star::fontawesome-solid-star::fontawesome-regular-star::fontawesome-regular-star::fontawesome-regular-star:"
    Get to know [Azure CLI](./objectives/o5.md) while enumerating Goose Islands' IT infrastructure.

!!! success "6. Certificate SSHenanigans - :fontawesome-solid-star::fontawesome-solid-star::fontawesome-solid-star::fontawesome-solid-star::fontawesome-solid-star:"
    [gingerbread](./objectives/o6.md)

!!! success "7. Active Directory - :fontawesome-solid-star::fontawesome-solid-star::fontawesome-solid-star::fontawesome-solid-star::fontawesome-regular-star:"
    [InstructionsForEnteringSatelliteGroundStation.txt](./objectives/o8.md)

!!! success "8. Elf Hunt - :fontawesome-solid-star::fontawesome-solid-star::fontawesome-solid-star::fontawesome-regular-star::fontawesome-regular-star:"
    [Hunt down the elfs](./objectives/o7.md) by tinkering with JWT token and client-side variables.

!!! success "9. The Captain's Comms - :fontawesome-solid-star::fontawesome-solid-star::fontawesome-solid-star::fontawesome-solid-star::fontawesome-solid-star:"
    [Frequency: 10426 HZ Go-Date: 1224 Go-Time: 1200](./objectives/o9.md)

!!! success "10. Luggage Lock - :fontawesome-solid-star::fontawesome-regular-star::fontawesome-regular-star::fontawesome-regular-star::fontawesome-regular-star:"
    [5 - 1 - 7 - 4](./objectives/o19.md)  
    
!!! success "11. Faster Lock Combination - :fontawesome-solid-star::fontawesome-solid-star::fontawesome-regular-star::fontawesome-regular-star::fontawesome-regular-star:"
    [33 - 23 - 17](./objectives/o10.md) 
    
!!! success "12. Game Cartridges: Vol 1 - :fontawesome-solid-star::fontawesome-regular-star::fontawesome-regular-star::fontawesome-regular-star::fontawesome-regular-star:"
    [santaconfusedgivingplanetsqrcode](./objectives/o11.md) 

!!! success "13. Game Cartridges: Vol 2 - :fontawesome-solid-star::fontawesome-solid-star::fontawesome-solid-star::fontawesome-regular-star::fontawesome-regular-star:"
    [GL0RY](./objectives/o12.md) 
    
!!! success "14. Game Cartridges: Vol 3 - :fontawesome-solid-star::fontawesome-solid-star::fontawesome-solid-star::fontawesome-regular-star::fontawesome-regular-star:"
    [!tom+elf!](./objectives/o13.md) 

!!! success "15. Linux PrivEsc - :fontawesome-solid-star::fontawesome-solid-star::fontawesome-solid-star::fontawesome-regular-star::fontawesome-regular-star:"
    [santa](./objectives/o16.md)  

!!! success "16. Na'an - :fontawesome-solid-star::fontawesome-solid-star::fontawesome-regular-star::fontawesome-regular-star::fontawesome-regular-star:"
    Beat cheating Shifty at Card Shuffle by [cheating yourself](./objectives/o17.md) via Python NaN Injection.

!!! success "17. Hashcat - :fontawesome-solid-star::fontawesome-solid-star::fontawesome-regular-star::fontawesome-regular-star::fontawesome-regular-star:"
    [IluvC4ndyC4nes!](./objectives/o18.md)

!!! success "18. KQL Kraken Hunt - :fontawesome-solid-star::fontawesome-solid-star::fontawesome-regular-star::fontawesome-regular-star::fontawesome-regular-star:"
    [Beware the Cube that Wombles](./objectives/o14.md)

!!! success "19. Phish Detection Agency - :fontawesome-solid-star::fontawesome-solid-star::fontawesome-regular-star::fontawesome-regular-star::fontawesome-regular-star:"
    [Find all phishing emails](./objectives/o15.md) using SPF, DKIM and DMARC.

!!! success "20. Space Island Door Access Speaker - :fontawesome-solid-star::fontawesome-solid-star::fontawesome-solid-star::fontawesome-regular-star::fontawesome-regular-star:"
    Open door using [AI-generated voice](./objectives/o20.md).
    
!!! success "21. Camera Access - :fontawesome-solid-star::fontawesome-solid-star::fontawesome-solid-star::fontawesome-regular-star::fontawesome-regular-star:"
    [CONQUER HOLIDAY SEASON!](./objectives/o21.md)
 
!!! success "22. Missile Diversion - :fontawesome-solid-star::fontawesome-solid-star::fontawesome-solid-star::fontawesome-solid-star::fontawesome-solid-star:"
    [Save Santa](./objectives/o22.md) from missile attack by chaining SQL Injection with Java deserialization exploit.

## Conclusion

??? Abstract "Story"
    Just sit right back and you’ll hear a tale,<br/>
    A tale of a yuletide trip<br/>
    That started from a tropic port,<br/>
    Aboard this tiny ship<br/>
    Santa and his helpful elves<br/>
    To Geese Islands did go<br/>
    Continuing their merry work<br/>
    O'er sand instead of snow<br/>
    New this year: a shiny tool<br/>
    The elves logged in with glee<br/>
    What makes short work of many tasks?<br/>
    It's ChatNPT. It's ChatNPT<br/>
    From images to APIs<br/>
    This AI made elves glad<br/>
    But motivations were unknown<br/>
    So was it good or bad?<br/>
    Could it be that NPT<br/>
    Was not from off-the-shelf?<br/>
    Though we'll forgive and trust again<br/>
    We'd found a naughty elf<br/>
    This fancy AI tool of ours<br/>
    With all our work remained<br/>
    Not good or bad, our online friend<br/>
    Just did as it was trained<br/>
    Surely someone's taint must be<br/>
    Upon our AI crutch<br/>
    Yes indeed, this bold new world<br/>
    Bore Jack Frost's icy touch<br/>
    Though all's returned to steady state<br/>
    There's one thing that we know<br/>
    We'll all be needed once again<br/>
    When Santa's back on snow<br/>

![Group photo](./img/misc/group_photo.jpg)

!!! quote "Santa @ Resort Lobby"
    You've done it! You've saved me and my sleigh from Jack Frost's dastardly plan!<br/>
    I must admit, it's astonishing the lengths Jack will go to in order to try and stop the holiday season.<br/>
    Even after being banished from Earth, he managed to create an AI to social engineer us into moving our holiday operations to the Geese Islands, putting us right in the path of his satellite.<br/>
    And to think he even recruited one of my dear elves... I never saw that coming. Oh, Wombley...<br/>
    But thanks to your incredible efforts, we've proof that Jack violated his parole, and the chances of him interfering with the holidays ever again are all but impossible!<br/>
    I can't thank you enough for your help in protecting the magic and joy of this special time of year.<br/>
    I'd like to wish you a most wonderful holiday season, no matter where you may be on Earth or what the weather is like.<br/>
    Keep that holiday spirit alive, my friend, and remember: a little change now and then can lead to something magical!<br/>
    Ho ho ho, happy holidays!

??? quote "Jack Frost @ Resort Lobby"
    Okay, listen up, yes I've been caught, but let me tell you, my plan was incredible, I mean really incredible.<br/>
    I and the trolls created ChatNPT, a fantastic AI, and left it behind in the North Pole in 2021 to trick Santa into moving to the Geese Islands. It worked like a charm, perfectly perfect.<br/>
    My satellite was geostationary, right over the islands to maintain comms with ChatNPT, and Wombley in the gound station. It was genius. Absolute genius, really.<br/>
    I was reviewing all the prompts as they were sent, and changing the responses in real time thanks to Santa's operation moving to the Geese Islands. This was very smart. Very, very, very smart, very efficient.<br/>
    And Wombley, the elf, joining me? Easy. He was so easy to convince.<br/>
    You see, there's a big, big dissent in Santa's ranks, huge.<br/>
    The elves, they're not happy with Santa.<br/>
    Mark my words, even if I don't stop Santa, his own elves will.<br/>
    It's going to be tremendous, this you will see.
    
??? quote "Troll @ Resort Lobby"
    Relax, bub. We're just here for Jack Frost. He broke Frostian and Earth law.<br/>
    The most important condition of his parole agreement was that he’d never set foot on Earth again.<br/>
    To evade the missile, his ejection pod landed on Geese Islands, so he’s back on earth, violating the explicit terms of his parole.<br/>
    Don't care he wouldn't have done it if the missile coordinates weren't tampered with. Rules are rules. Jack's time on Earth is finally up. We're taking him back.<br/>
    Frostian justice waits for no one. Not even Jack. End of story.<br/>
    And I just really want to be able to boss him around for a change. Keh heh heh.