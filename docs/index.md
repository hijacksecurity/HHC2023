# Welcome

![Group photo](./img/misc/title_image.jpg)

## Introduction

Welcome to the wild and wacky world of the [2023 SANS Holiday Hack Challenge](https://2023.holidayhackchallenge.com/) write-up! Imagine Santa traded his sleigh for a cybersecurity keyboard and elves started coding instead of making toys. Yep, that's the vibe!

This annual bash, courtesy of the brainy folks at SANS Institute, is like a holiday party for hackers. But instead of sharing eggnog recipes, we're diving deep into festive-themed puzzles that would make even Rudolph scratch his antlers in confusion.

In this report, we're spilling the digital cocoa on what went down. Expect tales of epic hacks, brain-teasing challenges, and maybe a reindeer or two trying to figure out a firewall. It's all fun, games, and a sprinkle of tech magic.

So, buckle up, grab your elf hat (or your favorite tech gadget), and let's unwrap the adventures of the 2023 SANS Holiday Hack Challenge! 🎅🔒🎉<br/>

---

Wow [ChatGPT](https://chat.openai.com/) sure is pretty good at writing report intros! 😊 A little bit of personal touch about this year's challenge. My name is HijackSecurity, it's my 2nd year fully completing Holiday Hack Challenge and writing the report.
Hats off to SANS team, thank you - you guys did an amazing job creating this challenge, HHC seems to somehow only keep getting better and better!<br/>

This year's game was awesome - fun, challenging and highly rewarding! The challenges had it all - AI, healthy amount of Azure APIs, SQL injections, 
lots of client-side code manipulation (JS breakpoints - what are those), some GameBoy hacking, lock-picking went back to high-school days, JWT's are cool, practical Java Deserialization exploitation, 
casual quick & dirty Python scripting, satellite hacking and the need to think outside the box like every hacking challenge demands.<br/>

Please give this write-up a read - you can follow along through all the [objectives](./objectives/o1.md). Use "Navigation tip" to easily walk through challenges step-by-step. Each Section has a set
of Objectives which contain what the Objective is, Solution (including official Answer) and Response after completion, along with other supplemental information to stay true to the Holiday Hack story. 

!!! note "100-page submission limit"
    Each year there's a huge number of write-ups that need to be reviewed by the Counter Hack team. To find a good middle ground between preventing information overload and creating a write-up that can stand on its own as a learning resource, some parts, like the *navigation tip* below, are collapsed by default. Skipping over these will not take away from understanding the overall solution, but feel free to expand them to get some additional information.

??? tip "Navigation tip"
    Even with less than 100 pages, there's still quite a bit of information to read through. To make things a little easier, you can use ++"P"++ or ++","++ to go to the previous section, ++"N"++ or ++"."++ to navigate to the next section, and ++"S"++, ++"F"++, or ++"/"++ to open up the search dialog.

    **TL;DR** if you keep pressing ++"N"++ or ++"."++ from this point forward, you'll hit all the content in the right order! :smile:

## Answers

!!! success "1. Holiday Hack Orientation - :fontawesome-solid-star::fontawesome-regular-star::fontawesome-regular-star::fontawesome-regular-star::fontawesome-regular-star:"
    Follow [Jingle Ringford's instructions](./objectives/o1.md) to get your bearings at Geese Islands.

!!! success "2. Snowball Fight - :fontawesome-solid-star::fontawesome-solid-star::fontawesome-regular-star::fontawesome-regular-star::fontawesome-regular-star:"
    Beat elfs and Santa at [Snowball Fight](./objectives/o2.md) by tinkering with client-side variables and parameters.

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
    [Hunt down the elfs](./objectives/o7.md) by tikering with JWT token and client-side variables.

!!! success "9. The Captain's Comms - :fontawesome-solid-star::fontawesome-solid-star::fontawesome-solid-star::fontawesome-solid-star::fontawesome-solid-star:"
    [Frequency: 10426 HZ Go-Date: 1224 Go-Time: 1200](./objectives/o9.md)

!!! success "10. Luggage Lock - :fontawesome-solid-star::fontawesome-regular-star::fontawesome-regular-star::fontawesome-regular-star::fontawesome-regular-star:"
    [5 - 1 - 7 - 4](./objectives/o19.md)  

!!! success "11. Game Cartridges: Vol 1 - :fontawesome-solid-star::fontawesome-regular-star::fontawesome-regular-star::fontawesome-regular-star::fontawesome-regular-star:"
    [santaconfusedgivingplanetsqrcode](./objectives/o11.md) 

!!! success "12. Game Cartridges: Vol 2 - :fontawesome-solid-star::fontawesome-solid-star::fontawesome-solid-star::fontawesome-regular-star::fontawesome-regular-star:"
    [GL0RY](./objectives/o12.md) 
    
!!! success "13. Game Cartridges: Vol 3 - :fontawesome-solid-star::fontawesome-solid-star::fontawesome-solid-star::fontawesome-regular-star::fontawesome-regular-star:"
    [!tom+elf!](./objectives/o13.md) 

!!! success "14. Linux PrivEsc - :fontawesome-solid-star::fontawesome-solid-star::fontawesome-solid-star::fontawesome-regular-star::fontawesome-regular-star:"
    [santa](./objectives/o16.md)  

!!! success "15. Na'an - :fontawesome-solid-star::fontawesome-solid-star::fontawesome-regular-star::fontawesome-regular-star::fontawesome-regular-star:"
    Beat cheating Shifty at Card Shuffle by [cheating yourself](./objectives/o17.md) via Python NaN Injection.

!!! success "16. Hashcat - :fontawesome-solid-star::fontawesome-solid-star::fontawesome-regular-star::fontawesome-regular-star::fontawesome-regular-star:"
    [IluvC4ndyC4nes!](./objectives/o18.md)

!!! success "17. KQL Kraken Hunt - :fontawesome-solid-star::fontawesome-solid-star::fontawesome-regular-star::fontawesome-regular-star::fontawesome-regular-star:"
    [Beware the Cube that Wombles](./objectives/o14.md)

!!! success "18. Phish Detection Agency - :fontawesome-solid-star::fontawesome-solid-star::fontawesome-regular-star::fontawesome-regular-star::fontawesome-regular-star:"
    [](./objectives/o15.md)


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
