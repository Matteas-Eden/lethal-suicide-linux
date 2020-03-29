Lethal Suicide Linux
-------------

*Suicide Linux* was originally created by [qntm](https://qntm.org/) as one of their many maybe-someday-useful projects. The extract below from their website sums it up quite well:

>You know how sometimes if you mistype a filename in Bash, it corrects your spelling and runs the command anyway? Such as when changing directory, or opening a file.
>
>I have invented Suicide Linux. Any time - any time - you type any remotely incorrect command, the interpreter creatively resolves it into rm -rf / and wipes your hard drive.
>
>It's a game. Like walking a tightrope. You have to see how long you can continue to use the operating system before losing all your data.

-- https://qntm.org/suicide

Sounds fun, right? Well, I decided it was really cool, but I thought `rm -rf /` was a little *tame*. We could do better. We have the technology.

Introducing... `dd if=/dev/zero of=/dev/sd* bs=4M status=none`

With the changes from this fork, you can be assured that any typo you make with *Lethal Suicide Linux* installed will be the death of any file in a `/*` radius. Mass disk destruction ensured. **Please run this in a VM. This is NSFM - Not Safe For Machines**.

<!-- ![screenshot](screenshot.png) -->

Running
-------

> Instructions yet to be added
